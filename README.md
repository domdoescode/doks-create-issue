Code generated for Doks project that does not run.

* Node version: v18.18.2
* NPM version: 9.8.1

Recreation steps:

```sh
npm create hyas@latest -- --template doks
cd hyas-project
npm install
npm run dev
```

Output:

```sh
$ npm run dev              

> hyas-project@0.0.0 dev
> exec-bin node_modules/.bin/hugo/hugo server --bind=0.0.0.0 --disableFastRender --baseURL=http://localhost --noHTTPCache

Watching for changes in /home/dom/Projects/hyas-project/{config,content,i18n,node_modules,package.json,static,themes}
Watching for config changes in /home/dom/Projects/hyas-project/config/_default, /home/dom/Projects/hyas-project/config/_default/hyas, /home/dom/Projects/hyas-project/config/_default/menus
Start building sites … 
hugo v0.119.0-b84644c008e0dc2c4b67bd69cccf87a41a03937e+extended linux/amd64 BuildDate=2023-09-24T15:20:17Z VendorInfo=gohugoio

WARN  [Hugo SEO] assets/favicon.png does not exist. Add a file that's at least 512x512 pixels (or your largest defined icon size)
WARN  [Hugo SEO] assets/mask-icon.svg does not exist.
WARN  [Hugo SEO] assets/favicon.ico does not exist.
WARN  [Hugo SEO] Missing default image for og:image - assets/cover.png does not exist. Use a high-quality image with dimensions of at least 1200 x 630 pixels, while keeping the file size under 8 MB.
WARN  [Hugo SEO] Missing default image for og:image - Add 'images: ['cover.png']' to your hugo.yaml
WARN  [Hugo SEO] Unsupported schema type: %!s(<nil>). Set Organization or Person in .Site.Params.seo.schemas.type
Built in 402 ms
Error: error building site: render: failed to render pages: render of "home" failed: "/home/dom/Projects/hyas-project/node_modules/@hyas/doks-core/layouts/home.searchindex.json:2:11": execute of template failed: template: home.searchindex.json:2:11: executing "home.searchindex.json" at <len site.Params.doks.searchExclKinds>: error calling len: reflect: call of reflect.Value.Type on zero Value
```
