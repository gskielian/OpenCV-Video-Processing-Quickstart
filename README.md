## README

From the extensive searching, I found a tutorial which works with my version of opencv:

http://opencv-python-tutroals.readthedocs.org/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html


## Description of files:

a) webcam-greyscale
b) play-a-video
c) webcam-capture-invert-save


For the last program, we modified the code slightly (change below) for it to work on my Ubuntu linux box:

```python
#prev code: 
#fourcc = cv2.VideoWriter_fourcc(*'XVID')

#working code:
fourcc = cv2.cv.CV_FOURCC(*'XVID')
```



