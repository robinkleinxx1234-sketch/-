# SpotifySkipper

A lightweight, background-running utility that allows you to skip Spotify tracks using custom global hotkeys. Designed to work seamlessly while gaming or working, featuring a system tray interface for easy configuration without editing config files.

## Features

- **Global Hotkeys:** Skip tracks even when Spotify is not in focus (works in games, browsers, etc.).
- **Tray UI:** Easy-to-use system tray menu to change hotkeys on the fly. No need to edit text files or code.
- **Background Mode:** Runs silently in the background with no visible console window.
- **Customizable:** Set your own keys for "Next Track" and "Previous Track".
- **Privacy Friendly:** Uses GitHub's no-reply email structure for commits (if contributing).

## Usage

1. **Download:** Get the latest `SpotifySkipper.exe` from the [Releases](../../releases) page.
2. **Run:** Double-click the `.exe` file. (Windows may ask for Administrator permission; this is required for global keyboard hooks).
3. **Configure:**
   - Look for the icon in your system tray (bottom-right corner near the clock).
   - **Right-click** the icon.
   - Select **"Set Next Key"** or **"Set Prev Key"**.
   - Press the desired key on your keyboard.
4. **Enjoy:** The app will now listen for your key presses and skip tracks automatically.

## Building from Source

If you prefer to build the application yourself or want to modify the code:

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/SpotifySkipper.git
   cd SpotifySkipper   