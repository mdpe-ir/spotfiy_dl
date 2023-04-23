<h1 align="center">Spotify_dl</h1>
<h4 align="center">A Music Downloader for Spotify Written In Pure Go</h4>

Spotifydl is a spotify media downloader.

It uses Youtube as the audio source and Spotify API for playlist/album/track details.

--- 

Make sure you have golang, ffmpeg installed. 

The library requires **libav** components to work:

- **libavformat**
- **libavcodec**
- **libavutil**
- **libswresample**
- **libswscale**

For **Arch**-based **Linux** distributions:

```bash
sudo pacman -S ffmpeg
```

For **Debian**-based **Linux** distributions:

```bash
sudo add-apt-repository ppa:savoury1/ffmpeg4
sudo apt install libswscale-dev libavcodec-dev libavformat-dev libswresample-dev libavutil-dev
```

For **macOS**:

```bash
brew install ffmpeg
```

For **Windows** see the [detailed tutorial](https://medium.com/@maximgradan/how-to-easily-bundle-your-cgo-application-for-windows-8515d2b19f1e).

