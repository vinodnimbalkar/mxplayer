# mxplayer

<i>A posix script that helps you open video (with out API) using mpv.</i>
<hr>
<p align="center">
  <img src=.assets/mxplayer.gif width="100%">
</p>

## Dependencies
- [mpv](https://github.com/mpv-player/mpv)
- [curl](https://github.com/curl/curl)

## Installation
This one-line installation does not support every OS
```bash
curl -sL "https://raw.githubusercontent.com/vinodnimbalkar/mxplayer/main/mxplayer" | sudo tee ~/.local/bin/mxplayer >/dev/null && sudo chmod +x ~/.local/bin/mxplayer
```

## Usage
```bash
$ mxplayer <url>
```

### How do I run locally

- Clone this repository `git clone https://github.com/vinodnimbalkar/mxplayer.git`
- `cd mxplayer`
- `chmox +x mxplayer`
- `./mxplayer https://www.mxplayer.in/show/watch-melting-heart-hindi-dubbed/season-1/episode-1-online-f249da5a4b170cedf239dea762094c27`

## Contributing

Feel free to open an issue (or even better, send a Pull Request). Contributions are very welcome!! 😄
