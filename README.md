# Wolfenstein 3D in Scratch
![wolflogo](https://github.com/nickplj12/wolf3d-scratch/assets/78268270/d2f59643-86cf-48de-bf30-2445a7a8cf9b)

recreating the wolfenstein 3d engine in scratch* one step at a time.

###### *specifically, this is meant to be played in TurboWarp, a faster version of playing scratch games.

builds would be in [releases](https://github.com/nickplj12/wolf3d-scratch/releases).

or, compile yourself at https://packager.turbowarp.org/

## Features
* Mouselook
* Pointerlock
* Texture mapping
* Gamepad support (wooah)
* Runs at 60 frames per second (or custom, compile yourself)
* Infinite clones
* raycasting!
* No loading times except for the initial bootup
* y-shearing
* Widescreen (16:9)
* MEIN LEBEN

## Install
get the latest build from releases. on windows/mac/linux it should work by default.
### freebsd
for freebsd, you have to do some setup first. this **does not work fully** yet, and might get you stuck on an error! if this does not work for you, just use the HTML build.

change ./start.sh's **first** line to be:
```bash
#!/usr/local/bin/bash
```
then run
```bash
cd <dir where "wolfscratch" file is>
sudo pkg install linux-c7-atk linux-c7-at-spi2-atk linux-c7-cups-libs linux-c7-gtk3 ffmpeg ffmpeg4
sudo chown root chrome-sandbox
sudo chmod 4755 chrome-sandbox
```

## Screenshots
<img width="494" alt="shot1" src="https://github.com/nickplj12/wolf3d-scratch/assets/78268270/2f7b4dd9-6fa7-487f-bc7f-7099ac222f5b">
<img width="493" alt="shot2" src="https://github.com/nickplj12/wolf3d-scratch/assets/78268270/935365f6-2fd5-4b65-97f2-c2aa1c2cd8a7">
<img width="378" alt="shot3" src="https://github.com/nickplj12/wolf3d-scratch/assets/78268270/4894abc9-5cff-434d-b824-5d5d250a3d72">
<img width="503" alt="shot4" src="https://github.com/nickplj12/wolf3d-scratch/assets/78268270/49a19334-9c9d-4e95-bf60-6bc4501188c2">
