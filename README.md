# Our School Pages Styler

Customize your styles by creating a [CustomHeader page](https://ourschoolpages.com/Help/Topic/26805/Custom-Header-Footer-Favicon).

Create a `web` folder on the  `Image library` and upload your favicon, e.g: `web/favicon2.ico`.

Within the `CustomHeader` page:

* Set the `Custom Meta Header` to:
```html
<link rel="icon" type="image/x-icon" href="/Image/web/favicon2.ico" />
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
```

* Under `Content`, click `View` and then `Source Code` and set it to:
```html
<style>

PASTE_HERE

</style>
```
* Replace `PASTE_HERE` with the content of `dist/custom.css`, see below.


# Installation

```sh
npm install -g yarn@latest
yarn install
```

# Usage

```sh
yarn build
# open dist/custom.css
```

## Contributing

Pull requests are welcome.

## License

[MIT](../main/LICENSE)
