# FacePlusPlus Python SDK

This is the Face++ python SDK suite. Note that python3 has not been supported
yet.

## 1. cmdtool.py
This is an interactive command line tool which could be used to experiment
with Face++ APIs. It is recommended to have ipython installed so that you can
have tab-completion and some other nice features.

Please put your API key/secret in apikey.cfg before starting this program.
Then you can write something like

    `api.detection.detect(img = File(r'<path to the image file>'))`

Note that `api` here is a global variable.

## 2. hello.py
This is a comprehensive demo for Face++ APIs. See the comments in the source
code for details.

## 3. facepp.py

This is the underlying API implementation.
