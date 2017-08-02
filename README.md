<h1 align="center">vlc-credit-skipper</h1>
<p align="center">Automatically skip intro/outro credit sequences in VLC.</p>
<p align="center"><a href="#readme"><img src="https://raw.githubusercontent.com/michaelbull/vlc-credit-skipper/master/preview.png" alt="Preview" /></a></p>

## Installation

Download the [`credit-skipper.lua`](credit-skipper.lua) file and place it in
your VLC extensions directory:

- Linux
    - `~/.local/share/vlc/lua/extensions/`
- Windows
    - `%APPDATA%\vlc\lua\extensions\`
- macOS
    - `/Users/<name>/Library/Application Support/org.videolan.vlc/lua/extensions/`

## Usage

1. Queue up media items within your playlist (<kbd>Ctrl+L</kbd>).
2. From the <kbd>V<u>i</u>ew</kbd> menu, select <kbd>Skip Intro/Outro
   Credits</kbd>.
3. If you have an existing profile, select it from the dropdown menu and press
   <kbd>Load</kbd>. This will populate the settings section with the values
   loaded from the selected profile.
4. The settings section can be used to configure an existing profile or to
   create a new one. Click the <kbd>Save</kbd> button to save your changes.
6. Profiles are saved as a file named `credit-skipper.conf` in your VLC [config
   directory][config-dir], alongside your `vlcrc` file.
7. Press the <kbd>Start Playlist</kbd> button to play the playlist with the skip
   settings applied.

## Contributing

Bug reports and pull requests are welcome on [GitHub][github].

## License

This project is available under the terms of the ISC license. See the
[`LICENSE`](LICENSE) file for the copyright information and licensing terms.

[github]: https://github.com/michaelbull/vlc-credit-skipper
[config-dir]: https://www.videolan.org/support/faq.html#Config
