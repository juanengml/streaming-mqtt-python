# mqtt-camera-streamer
```
$ (base) python3 -m venv venv
$ (base) source venv/bin/activate
$ (venv) pip3 install -r requirements.txt
```

To check which OpenCV cameras are detected run:
```
$ (venv) python3 scripts/check-opencv-cameras.py
```

## Configuration using `config.yml`

```
$ (venv) python3 scripts/validate-config.py
```

## Publish camera frames

Publica no mqtt

```
$ (venv) python3 scripts/opencv-camera-publish.py
```

## Camera display
To view the camera stream with Streamlit:

```
$ (venv) streamlit run scripts/viewer.py
```
