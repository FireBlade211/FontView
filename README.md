# FontView

FontView is a simple and lightweight font previewer for Windows. It allows you to easily view and inspect fonts by opening `.ttf` (TrueType Font) and `.otf` (OpenType Font) files directly, without the need for installation. Just download the executable, and you’re good to go!

## Features

- **Font Preview**: View the selected font with different sample texts.
- **Command-Line Support**: Open font files directly from the command line as a quick preview.
- **No Installation Required**: Easily download and run the executable.
- **Cross-Platform Font Handling**: Supports both `.ttf` and `.otf` formats.
- **Lightweight and Easy to Use**: Just the essentials for font previewing without unnecessary features.

## Installation Guide
1. Download the `fontview.exe` file from the [releases page](https://github.com/FireBlade211/FontView/releases).
2. Double-click `fontview.exe` to launch FontView.

## Previewing Fonts

### Option 1: Opening via Font Gallery
1. Open FontView.
2. Scroll through the font gallery or use the search bar to find the font you want to preview.
3. Click on the font to preview it.

### Option 2: Preview a specific font file using the Open Font dialog
1. Open FontView.
2. Open the File menu on the menu bar
3. Select Open to browse and select a `.ttf` or `.otf` font file.
4. Press the Open button in the Open Font dialog to preview it. 

### Option 3: Open a font with the command-line
1. Open a Command Prompt or PowerShell window.
2. Run FontView with the font file as an argument, like this:
   ```sh
   fontview.exe "C:\path\to\your\font.ttf"
   ```
 or:
  ```sh
  fontview.exe "C:\path\to\your\font.otf"
  ```
## Contributions
Feel free to fork this project, submit issues, and create pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/FireBlade211/FontView/blob/main/LICENSE) file for details.
