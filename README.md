# Yolov7-Object-Counting


### Steps to run Code
- Clone the repository.
```
git clone https://github.com/noorkhokhar99/Yolov7-Cigarette-Censor.git
```
- Goto the cloned folder.
```
cd Yolov7-Cigarette-Censor

```
- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```
- Run the code with mentioned command below.

 python detect.py --weights cigarette.pt --conf 0.1 --source test2.jpeg --cigarette_blurrate 50 --shape_detector shape_predictor_68_face_landmarks.dat

 - Run for webcam
 
`python detect.py --weights best_cigarette.pt --conf 0.1 --source 0 --cigarette_blurrate 50 --shape_detector shape_predictor_68_face_landmarks.dat`


<p align="center">
<img src="https://github.com/noorkhokhar99/Yolov7-Cigarette-Censor/blob/main/Screen%20Shot%201444-04-12%20at%2011.51.38%20PM.png">
</p>






### Inference on a video:
https://www.youtube.com/c/pyresearch

