# -Vehicle-Speed-Detection-using-YOLO-ByteTrack

## 📌 Overview
This project performs **vehicle detection, tracking, and speed estimation** using YOLO and ByteTrack. It calculates vehicle speed based on the time taken to cross two virtual reference lines on the road in a video.

---

## 🎯 Features
- Vehicle detection (car, bus, truck, motorcycle)
- Multi-object tracking using ByteTrack
- Speed estimation in km/h
- Road segmentation (Road A & Road B)
- Direction detection (Up / Down)
- Vehicle counting per road
- Annotated output video generation

---

## 🧠 How It Works
1. Load input video frame-by-frame
2. Detect vehicles using YOLO
3. Track vehicles using ByteTrack
4. Define two virtual lines on the road
5. Measure time taken to cross both lines
6. Compute speed using distance/time formula
7. Display results on video

---

## 📐 Speed Formula

v = (d / t) × 3.6

Where:
- `d` = distance between two lines (meters)
- `t` = time (seconds)
- `3.6` converts m/s to km/h

---
