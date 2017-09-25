# VSC Optimize Images

<p align="center">
	<img src="https://raw.githubusercontent.com/fabiospampinato/vscode-optimize-images/master/resources/logo-128x128.png" alt="Logo">
</p>

Optimize one or all the images in your project using your favorite app.

## Install

Run the following in the command palette:

```shell
ext install vscode-optimize-images
```

## Usage

It adds 1 command to the command palette:

```js
Optimize Images: Optimize All // Optimize all images found in the current project
```

You can also right click a single image and only optimize that one.

## Settings

```js
{
  "optimizeImages.app": "", // Name of the app to use for optimizating the images
  "optimizeImages.imageRegex": ".*\\.(png|gif|jpe?g)$", // Regex used for matching images. Requires double escaping
  "optimizeImages.searchDepth": 10, // Maximum depth to look at when searching images
  "optimizeImages.searchStartingPath": ".", // Path relative to the root where to start searching images
  "optimizeImages.searchIgnoreFolders": [".git", ...] // Ignore these folders when searching images
}
```

## Recommended Apps

#### Mac

- [ImageOptim](https://imageoptim.com/mac): Removes bloated metadata. Saves disk space & bandwidth by compressing images without losing quality.

#### Windows

_Contact me if you have an app to suggest for this section._

#### Linux

_Contact me if you have an app to suggest for this section._

## Demo

![Demo](resources/right_click.png)

## License

Icon: GPL v2 © [ImageOptim](https://github.com/ImageOptim/ImageOptim)


Extension: MIT © Fabio Spampinato