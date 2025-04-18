# video_to_wide_angle_image
# 📷 Capture the Scene - Panorama Creator

This Python script captures frames from a video file and stitches them together to create a panorama image using OpenCV.

---

## 🔧 Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy

Install dependencies (if not already installed):

```bash
pip install opencv-python numpy
```

---

## 📁 Files

- `capture_the_scene.py`: The main script to extract and stitch frames.
- `video.mp4`: The input video file (make sure it's in the same directory).
- `panorama.jpg`: The output panorama image (created after running the script).

---

## 🚀 How to Run

1. Place your `video.mp4` file in the same directory as the script.
2. Run the script:

```bash
python capture_the_scene.py
```

3. If stitching is successful, a file named `panorama.jpg` will be saved in the directory.

---

## ⚙️ Settings (customizable)

- `frame_skip`: Controls how many frames are skipped between extractions (default is 15).
- `resize_factor`: Controls the size reduction of frames before stitching (default is 0.9).
- You can tune these parameters to optimize performance or results.

---

## 📝 Notes

- The stitching algorithm may fail if the scene lacks distinguishable features or has too much motion.
- Best results are obtained with videos captured from a slowly moving camera across a static scene.
