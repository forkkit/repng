
# repng

React component to PNG converter, built with [Puppeteer][puppeteer]

![](examples/repng.png)

```sh
npm i -g repng
```

```sh
repng Icon.js --width 512 --height 512 --out-dir assets
```

```
Usage
  $ repng <ReactComponent>

Options
  -d --out-dir    Directory to save file to
  -f --filename   Specify a custom output filename
  -w --width      Width of image
  -h --height     Height of image
  -p --props      Props in JSON format (or path to JSON file) to pass to the React component
  -t --type       Type of ouptut (png default) (pdf, jpeg or png)
  --css           Path to CSS file to include
  --webfont       Path to custom webfont for rendering
  --puppeteer     Options for Puppeteer in JSON format
```

### Related

- [Puppeteer][puppeteer]

MIT License

[puppeteer]: https://github.com/GoogleChrome/puppeteer
