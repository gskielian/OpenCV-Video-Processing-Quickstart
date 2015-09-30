## README

From the extensive searching, I found a tutorial which works with my version of opencv:

http://opencv-python-tutroals.readthedocs.org/en/latest/py_tutorials/py_gui/py_video_display/py_video_display.html


## Description of files:

1. webcam-greyscale.py
2. play-a-video.py
3. webcam-capture-invert-save.py


For the last program, we modified the code slightly (change below) for it to work on my Ubuntu linux box:

```python
#prev code: 
#fourcc = cv2.VideoWriter_fourcc(*'XVID')

#working code:
fourcc = cv2.cv.CV_FOURCC(*'XVID')
```



