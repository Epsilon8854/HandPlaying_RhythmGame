# HandPlaying_RhythmGame

## requirement
- MFC
- Opencv 4.0 <=

## Overview
---
This is a hand-playing rhythm game, using Hand detection & tracking

**The image is very big! Please wait a second..**

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
   
**The Image is very big! Please wait a second..**

![](image/Labeling.gif)

### Tracking
After finsh the detection(it will turn to Blue), I use *Mean-Shift Algorithm* to track Object

**The image is very big! Please wait a second..**

![](image/TrackAfterDetect.gif)

## CODE
Because of big size, I have attached a download link.

Thank you.
```
https://o365cbnu-my.sharepoint.com/:u:/g/personal/dlsgk2121_cbnu_ac_kr/ER_1txwMwrxNtl5nCiwYLWUBvrEUGgL4LSL7NTG8-KXiDw?e=nNDONO
```