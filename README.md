# HTTP Live Streaming

- [HTTP Live Streaming](https://www.slideshare.net/aurot/http-live-streaming-10069443)
- [An Introduction To HLS](https://www.slideshare.net/rmcore/an-introduction-to-hls-http-live-streaming-48353016)

## RTMP Server

```
docker pull alfg/nginx-rtmp
docker run -it -p 1935:1935 -p 8099:80 --rm alfg/nginx-rtmp
```

## Live Stream Encoder

Android App [nanoStream Live Video Encoder](https://play.google.com/store/apps/details?id=net.nanocosmos.nanoStream)

## Client

### ffplay

```
ffplay rtmp://localhost:1935/stream/live
```

### VLC / videojs

http://localhost:8099/hls


