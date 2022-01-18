# `youtube-dl` download tool

Open source tool https://youtube-dl.org

## Usage

- To download audio only

```
youtube-dl -f 'bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best' ${url}
```

- To download video and audio seperated files

```
youtube-dl -f 'bestvideo[ext=mp4]+bestaudio[ext=m4a]' ${url}
```

- To download video and audio merge to `mp4`

```
youtube-dl -f 'bestvideo[ext=mp4]+bestaudio[ext=m4a]/best[ext=mp4]/best' ${url}
```
