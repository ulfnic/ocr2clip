# ocr2clip
Read text within a screen-grab and put it in your clipboard.

## Example X11 Installation
```bash
sudo apt install tesseract-ocr maim xclip ffmpeg
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/ulfnic/ocr2clip/main/ocr2clip
sudo chmod +x ./ocr2clip
```

## Example Wayland Installation
```bash
sudo apt install tesseract-ocr grim slurp ffmpeg
cd /usr/local/bin
sudo wget https://raw.githubusercontent.com/ulfnic/ocr2clip/main/ocr2clip
sudo chmod +x ./ocr2clip
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
`import` and `mogrify` should be in the `imagemagick` package.

## License
Licensed under GNU Affero General Public License v3. See LICENSE for details.
