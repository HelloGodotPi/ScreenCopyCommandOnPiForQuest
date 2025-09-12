# Screen Copy Command On Pi For Quest

Useful terminal command for Quest3 and phone on Raspberry Pi with SCRCPY

https://github.com/EloiStree/HelloRaspberryPi/issues/62


## Example: stream camera and screen of the Quest

```
scrcpy --max-size 800 --video-bit-rate 2M --max-fps 15 --stay-awake --no-audio
```

<img width="1526" height="497" alt="Image" src="https://github.com/user-attachments/assets/b68d1600-6fcb-4644-933b-e95a19419494" />

```
scrcpy --video-source=camera  --max-size 800 --video-bit-rate 2M --max-fps 15 --no-audio --camera-id=0
```
https://github.com/Genymobile/scrcpy/blob/master/doc/camera.md

<img width="1580" height="696" alt="Image" src="https://github.com/user-attachments/assets/987acbff-07c1-41e5-9fe4-d6f377e3db12" />

My gosh I can use both camera and screen

<img width="1766" height="1000" alt="Image" src="https://github.com/user-attachments/assets/1fd07612-b768-4686-a6ba-ef634ca4c80d" />
(But still not the two camera at the same time xD)
