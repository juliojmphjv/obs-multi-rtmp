## Install On Ubuntu

```sh
./ci/install_ubuntu.sh
./build_linux.sh

sudo cp -r dist/usr/share/obs/obs-plugins/obs-multi-rtmp /usr/share/obs/obs-plugins
sudo cp build/obs-multi-rtmp.so /usr/lib/obs-plugins
```
