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

