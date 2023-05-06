# ocr2clip

Read text within a screen-grab and put it in your clipboard.

`ocr2clip` uses `tesseract` to perform text recognition and tries to remain package agnostic for additional tasks (see: Dependencies).

## Installation
```bash
# Install to /usr/local/bin
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/ulfnic/ocr2clip/main/ocr2clip
sudo chmod +x ./ocr2clip

# Test run
ocr2clip

# Satisfy dependencies if prompted to do so.

# Consider installing ffmpeg or mogrify (part of imagemagick) for improved accuracy.
```

## Dependencies
- `tesseract`

#### X11:
- `maim` or `import`
- `xclip` or `xsel`

#### Wayland:
- `grim`
- `slurp`
- `wl-copy`

#### Optional dependencies for improved accuracy:
- `ffmpeg` or `mogrify`

#### Note:
`import` and `mogrify` are part of `imagemagick`

## Troubleshooting

- Open up a terminal and run `ocr2clip`
- Make sure `/usr/local/bin` is in your $PATH

## License
Licensed under GNU Affero General Public License v3. See LICENSE for details.
