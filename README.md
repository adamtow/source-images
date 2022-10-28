# Source Iamges

Graphics for use with the Multiview Switcher in MixEffect 1.7.0 and higher.

You can specify images to represent your input sources when using the Multiview Switcher. You set these images in your Switcher Connection Edit section by following these steps:

1. Tap on a **Switcher Connection** in the MixEffect Navigation View.
2. Tap **Edit**.
3. Scroll down to the **Source Images** section.

Each input should be entered on its own line using the following format:

`X COLOR: URL`

where:

- **X**: 1-based index for the video source
- **COLOR (Optional)**: Hex value for the background (inc. the # symbol). If you do not specify a background color, black will be used.
- **URL**: is a publicly accessible URL (via HTTPS) to the image

The image should be formatted to a 16:9 aspect ratio and should be no larger that 1920x1080 in size.
For instance, the following Source Images are defined for an ATEM Mini Extreme ISO that has 6 inputs configured as follows:

```
1: https://adamtow.github.io/source-images/5d4.png
2: https://adamtow.github.io/source-images/ipad.png
3: https://adamtow.github.io/source-images/ios.png
4: https://adamtow.github.io/source-images/macmini.png
5: https://adamtow.github.io/source-images/appletv.png
6: https://adamtow.github.io/source-images/xbox.png
```

![Manually Setting Source Images](https://1539191236-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MaiI5oKYEXGU01L5yjC%2Fuploads%2FdS1GOaSf499gRq0oWqr9%2Fsource-images-edit.png?alt=media&token=4c65efc4-4f09-4e2e-bafa-12b567bedec0)

Adding a color to your Source Images looks like this:

```
1 #FFCCFF: https://adamtow.github.io/source-images/5d4.png
2 #333333: https://adamtow.github.io/source-images/ipad.png
3 #AAAAAA: https://adamtow.github.io/source-images/ios.png
4 #FF0000: https://adamtow.github.io/source-images/macmini.png
5 #00FF00: https://adamtow.github.io/source-images/appletv.png
6 #0000FF: https://adamtow.github.io/source-images/xbox.png
```

## Using Shortcuts to Quickly Change Source Images

Use the [Set Source Images action](https://docs.mixeffect.app/automate/shortcuts/actions/set-source-images) in Shortcuts to quickly update or clear out the source images for a given Switcher Connection. 

![Set Source Images Shortcut](https://1539191236-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F-MaiI5oKYEXGU01L5yjC%2Fuploads%2Fvjh7Dwtmr9pVqXFAGkHd%2Fset-source-images.gif?alt=media&token=f0647aad-0c72-4abe-b6cd-d9d4ba0a5f56)

