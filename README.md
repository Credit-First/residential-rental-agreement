## Initial setup

Before you begin, make sure your development environment includes [Node.js](https://nodejs.org/en/).

## Install

```
git clone https://github.com/credit-first/residential-rental-agreement.git
cd residential-rental-agreement
npm install
```

## Run

```
npm start
```

After the app starts, you will be able to see WebViewer running on `localhost:3000`.

## Build

Run `npm run build` to build the project. The build artifacts will be stored in the `build/` directory. See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

To test the build directory locally you can use [serve](https://www.npmjs.com/package/serve) or [http-server](https://www.npmjs.com/package/http-server). In case of serve, by default it strips the .html extension stripped from paths. We added serve.json configuration to disable cleanUrls option.

```
WebViewer(
 {
   path: '/residential-rental-agreement/webviewer/lib',
   initialDoc: '/residential-rental-agreement/files/PDFTRON_about.pdf',
 },
 viewer.current,
).then((instance) => {
```

## WebViewer APIs

See [API documentation](https://www.pdftron.com/documentation/web/guides/ui/apis).

## Contributing

See [contributing](./CONTRIBUTING.md).

## License

See [license](./LICENSE).
![](https://onepixel.pdftron.com/residential-rental-agreement)
