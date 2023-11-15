# Empty Video

<https://storage.yusanshi.com/empty.mp4>

https://trac.ffmpeg.org/wiki/Slideshow

```bash
ffmpeg -loop 1 -framerate 1 -i empty-%01d.png -t 3600 -vf format=yuv420p -y empty.mp4
scp empty.mp4 aliyun:/var/www/storage.yusanshi.com/
```
