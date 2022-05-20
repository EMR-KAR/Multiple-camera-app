# Multiple-camera-app
Install main libraries:
pip install opencv-python
pip install kivy
To setup cameras via config, enter your video path or ip camera url in 'config>ui_config.json'.
You can place your videos in mylib>videos or enter the url if its an ip camera. Example:

"camera_url": [
    "mylib/videos/1.mp4",
    "http://192.158.0.115:8050/video",
To setup cameras via ui, click settings>enter details>apply after running the code:

You could also setup a database if you ever want to.

To run: python run.py
