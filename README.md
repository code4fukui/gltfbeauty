# gltfbeauty

[
![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)
](https://code4fukui.github.io/gltfbeauty/)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A client-side web tool for optimizing GLTF/GLB files by resizing and compressing their textures, making them suitable for web publishing.

## Demo

**[https://code4fukui.github.io/gltfbeauty/](https://code4fukui.github.io/gltfbeauty/)**


![gltfbeauty screenshot](https://code4fukui.github.io/gltfbeauty/gltfbeauty.png)


## Features

-   **Texture Optimization:** Compresses textures to JPEG format with adjustable quality and resizes them to a specified resolution (e.g., 1024x1024, 2048x2048).
-   **Format Conversion:** Choose between `.gltf` (text-based) and `.glb` (binary) for the output file.
-   **Batch Processing:** Drag and drop multiple files or an entire folder to process them all at once.
-   **Client-Side Processing:** All operations are performed directly in your browser. No files are uploaded to a server, ensuring privacy and speed.
-   **Color Space Control:** Option to enforce the sRGB color space for textures.

## How to Use

1.  Open the [gltfbeauty demo page](https://code4fukui.github.io/gltfbeauty/).
2.  Drag and drop your `.gltf` or `.glb` file(s) onto the designated area, or use the "Select File" button.
3.  Configure the output settings before dropping your files:
    -   **Texture Size:** Select the desired maximum texture width/height in pixels.
    -   **Quality:** Set the JPEG compression quality (a value from 0.0 to 1.0).
    -   **Force sRGB:** Check to enforce the sRGB color space.
    -   **glTF Output:** Check to convert the output to `.gltf` format; otherwise, it will be `.glb`.
4.  The conversion starts automatically. A single processed file will download directly. Multiple files will be downloaded as a single `.zip` archive.

## Credits

-   Author: [Taisuke Fukuno](https://fukuno.jig.jp/) (@taisukef)
-   Contributor: [@nknhb966](https://github.com/nknhb966)
-   Based on [GLTF.js](https://github.com/code4fukui/GLTF/)

## License

MIT License — see [LICENSE](LICENSE).