# iconset2icns

This is a really simple ruby script that can be used to pack iconset image files
to icns format.

The source image files are packed as-is so you should compress them beforehand
using a tool like pngquant and/or optipng.

## Usage

`iconset2icns <path>`

The tool looks for these filenames in `<path>`, and missing files are ignored.

    icon_16x16.png
    icon_16x16@2x.png
    icon_32x32.png
    icon_32x32@2x.png
    icon_64x64.png
    icon_128x128.png
    icon_128x128@2x.png
    icon_256x256.png
    icon_256x256@2x.png
    icon_512x512.png
    icon_512x512@2x.png

## Format

The icns format is very simple and documented at
https://en.wikipedia.org/wiki/Apple_Icon_Image_format

You can easily copy and modify this tool to fit your needs.
