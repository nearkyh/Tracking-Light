# Tracking Light
Project for tracking light


## Requirements

- Ubuntu 16.04
- Python 3.5
- OpenCV 3.2


## Dependencies

- sudo pip3 install imutils
- sudo pip3 install --upgrade scikit-image


## Getting Started

Demo :

- python3 tracking_light_demo.py --image {IMAGE_FILE_NAME}

Run :

- python3 tracking_light_app.py

  Traceback (most recent call last):
    File "tracking_light_app.py", line 59, in <module>
      cnts = contours.sort_contours(cnts)[0]
    File "/usr/local/lib/python3.5/dist-packages/imutils/contours.py", line 25, in sort_contours
      key=lambda b: b[1][i], reverse=reverse))
  ValueError: not enough values to unpack (expected 2, got 0)

  *** 카메라 연결후 실행시 위의 에러가 나타남, 현재 위의 에러를 해결해야 됨 ***
  
