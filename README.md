# HandPlaying_RhythmGame

## requirement
- MFC
- Opencv 4.0 <=

## Overview
---
This is a hand-playing rhythm game, using Hand detection & tracking

![](image/HandPlayingGameExample.gif)
 

## Hand Detection & Tracking
---
### Detection
Detection is Proceeds with following Color-based algorhythm


1. Make binary image
2. Label it
3. Find biggest Obj
4. **For** 100 times
   1. Get biggest obj's histogram *H*
   2. backproject *H* to orginal image 
   3. From backprojected image, find biggest Obj
   
![](image/Labeling.gif)

### Tracking
After finsh the detection(it will turn to Blue), I use *Mean-Shift Algorithm* to track Object

![](image/TrackAfterDetect.gif)

