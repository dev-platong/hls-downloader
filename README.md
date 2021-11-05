hls-downloader
==============

Download all files as is from HLS (HTTP Live Streaming) VoD (Video on Demand) playlist m3u8 from <https://developer.apple.com/streaming/examples/>

![Python application](https://github.com/denex/hls-downloader/workflows/Python%20application/badge.svg)

If your playlist does not have `EXT-X-PLAYLIST-TYPE` tag, don't worry about that. It works. (It means Non VOD Playlist can be used by this scripts.)
But captured streams are snapshots at the time.

Python 3 suport
---------------

Usage:

```sh
python main.py 'http://some.m3u8' /some/dir/for/files/
```

Known Issues:

* No encryption/decryption supported yet
* Progress is not shown by downloading streams.
