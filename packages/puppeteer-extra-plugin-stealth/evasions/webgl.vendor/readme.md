## API

<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

#### Table of Contents

- [class: Plugin](#class-plugin)

### class: [Plugin](https://github.com/berstend/puppeteer-extra/blob/7a9082f9837f2403099e2181d639aa0065c51ba9/packages/puppeteer-extra-plugin-stealth/evasions/webgl.vendor/index.js#L16-L54)

- `opts` **[Object](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object)?** Options (optional, default `{}`)
  - `opts.vendor` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)?** The vendor string to use (default: `Intel Inc.`)
  - `opts.renderer` **[string](https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String)?** The renderer string (default: `Intel Iris OpenGL Engine`)

**Extends: PuppeteerExtraPlugin**

Fix WebGL Vendor/Renderer being set to Google in headless mode

Example data (Apple Retina MBP 13): {vendor: "Intel Inc.", renderer: "Intel(R) Iris(TM) Graphics 6100"}

---
