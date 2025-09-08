# qBittorrent Theme

A theme for qBittorrent, using `Segoe UI` and `Microsoft YaHei UI`.

Display CJK characters for users using English systems.

## Usage

1. Download the `.qbtheme` file from the [Releases][release] page, and save it in a convenient place, e.g. the qBittorrent installation folder.
2. In qBittorrent go to _Tools -> Options_ and in the left pane select _Behaviour_. In the right pane under _Interface_ check the box _Use custom UI Theme_.
3. Under _UI Theme file_ browse to the `.qbtheme` file.
4. Click **Ok**, and restart qBittorrent for the changes to take effect.

## Build

To build the theme, clone this repository and run `make.bat`. Alternatively run `make-resource.py` and supply the paths to the resources manually.

`make-resource.py` courtesy of [jagannatharjun/qbt-theme][qbt-theme].

[release]: https://github.com/akiirui/qBittorrent-theme/releases
[qbt-theme]: https://github.com/jagannatharjun/qbt-theme
