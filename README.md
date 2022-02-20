MakeUofT 2022 project by Nathan Green and Mailyn Takayesu.

We created a pair of augmented reality glasses that allow you to view analog clocks as digital time by looking at them.

The machine learning model requires three files not included in this repo to run.

coco.names (https://github.com/pjreddie/darknet/blob/master/data/coco.names)
yolov3.cfg (https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
yolov3.weights (https://pjreddie.com/media/files/yolov3.weights)

These files must be downloaded and placed in /python/data/model for the program to run correctly.

Required python libraries are opencv-python and numpy.

The Arduino code has been tested with an AI Thinker ESP32 paired with an Adafruit 128x64 SSD1306 1.3" OLED display.