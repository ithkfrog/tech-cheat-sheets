# `youtube-dl` download tool

Open source tool https://youtube-dl.org

## Installation
```brew install youtube-dl```

## Dependencies
`ffmpeg` is tool to combine video and audio into signle file.
```brew install ffmpeg```

## Usage

- To download audio only

```
youtube-dl -f 'bestaudio[ext=m4a]' ${url}
```

- To download video and audio seperated files

```
youtube-dl -f 'bestvideo[ext=mp4]+bestaudio[ext=m4a]' ${url}
```

- To download video and audio merge to `mp4`

```
youtube-dl -f 'bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best' ${url}
```
