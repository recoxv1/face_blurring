# Face Blurring
**Face detection + Face blurring**
+ Detect all the face from the input video
+ Blur all the detected faces
+ Save the blurred-face video

**Code Author: Shih-Yao (Mike) Lin**


## Platform
+ Ubuntu 16.04
+ GTX-1080

## Dependencies
+ OpenCV >= 3.2.0.8
+ Tensorflow >= 1.4.1
+ MTCNN 

## Installation

* Clone this repo

```bash
git clone https://github.com/mikeshihyaolin/face_blurring.git
```

## Quick Start
```
python face_blurring.py --source_video ./video.mp4 --output_video ./video_o.mp4 
```

## Visualization results
![](figs/blur1.png)
![](figs/blur2.jpg)

The face detection process is heavily borrowed from a MTCNN implementation ([Link](https://github.com/ipazc/mtcnn.git))
