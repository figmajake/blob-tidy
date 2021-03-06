# Blob Tidy

![](BlobTidyBanner.png)

A Figma and FigJam plugin that tidies your current selection in a bloblike fashion.

Check it out in [the Figma Community](https://www.figma.com/community/plugin/1128795550806441376/Blob-Tidy)!

This repo was created by @figma/create-widget

## Getting started with widget development

Run the following command to start building your widget

```bash
npm run dev
```

1. Log in to your account and open the Figma desktop app
2. You can open any existing FigJam document or create a new one.
3. Go to Menu > Widgets > Development > "Import widget from manifest..."
4. Select the manifest.json in this folder

## Organization

This widget uses:

- [esbuild](https://esbuild.github.io/) for bundling
- [typescript](https://www.typescriptlang.org/) for typechecking

| file/folder   | description                                                                      |
| ------------- | -------------------------------------------------------------------------------- |
| manifest.json | The widget's [manifest.json](https://www.figma.com/widget-docs/widget-manifest/) |
| widget-src/   | Contains the widget code                                                         |

### `npm run dev`

This is the only command you need to run in development. It will start the following processes for you:

- bundling
- typechecking

### `npm run build`

This runs bundling with minification turned on. You should run this command before releasing your widget.

### `npm run test`

This runs typechecking and makes sure that your widget builds without errors.
