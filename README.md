# Live

A simple live setup for Debian 11.

## Setup

```shell
apt install nginx libnginx-mod-rtmp
git clone https://github.com/TechCiel/Live.git
cp -r Live/fs/* /
systemctl daemon-reload
systemctl restart nginx
```

## License

The file `fs/var/www/html/hls.min.js` is from [video-dev/hls.js](https://github.com/video-dev/hls.js), which is licensed under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

The other parts in this repo is licensed under [WTFPL](./LICENSE).
