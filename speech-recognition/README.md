```
modprobe snd-bcm2835
docker run --rm -p 8000:8000 --device /dev/snd:/dev/snd speech-recognition:1.0.4-arm
```
