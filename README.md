# DDS

## Installation

```bash
pip install opencv-python
```
```bash
pip install scipy
```

```bash
pip install cmake
```

```bash
pip install dlib
```

### To detect faces in image:

```bash
python detect_faces.py --image pic_name.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```

### To detect faces in video:

```bash
python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel
```

### To detect blinks:

```bash
python detect_blinks.py --shape-predictor shape_predictor_68_face_landmarks.dat
```

### To detect Drowsiness:

```bash
python detect_drowsiness.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav
```
