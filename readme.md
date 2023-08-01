# lslive

Simple python script using [yt-dlp](https://github.com/yt-dlp/yt-dlp) to list live channels from streaming sites supported by yt-dlp

## Dependencies

This project uses [yt-dlp](https://github.com/yt-dlp/yt-dlp) and requires >=python3.11. Install with `pip install` or your system's package manager. 

Optionally, [pyperclip](https://github.com/asweigart/pyperclip) is used for clipboard access and [argcomplete](https://github.com/kislyuk/argcomplete) is used for shell completions.

## Install

Place `lslive` in your `$PATH` and give it executable permissions: `chmod a+x lslive`

Copy `config.toml` to `~/.config/lslive/config.toml` and add your desired channels.

For completions, see [argcomplete](https://github.com/kislyuk/argcomplete).

## Usage

Run `lslive --help`

## Todo
- Add a cache system for calls in quick succession
- More robust error handling for fetch_channels (and generally)
