# Emopy-Models

Emotion recognition using facial expression demo.

## How to run demo
### Image demo

```
python -m demo --mtype np --ttype image --path /path-to-image/image-file 
```
Where ```--mtype``` is model type. It can be either np(neutral positive classifier) or ava(basic seven emotion classifier including neutral). ```--ttype``` is type of of demo either ```image``` , ```video``` or ```webcam```. ```--path``` is full path to image. 

### video demo
```
python -m demo --mtype np --ttype video --path /path-to-video/video-file 
```
### web demo
```
python -m demo --mtype np --ttype webcam 
```

### Dependancies

* tensorflow >= 1.0
* keras
* opencv >= 3.0
* dlib 
* numpy

opencv should be compiled with ffmpeg support.