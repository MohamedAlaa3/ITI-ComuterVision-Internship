# ITI Computer Vision Internship

Labs from the ITI computer vision program (2022). Python first, then NumPy, then OpenCV. Two small projects at the end:

- Project 1: analog clock drawn with OpenCV
- Project 2: snake game in an OpenCV window

## Demo

https://mohamedalaa3.github.io/ITI-ComuterVision-Internship/

The snake below is a browser version of the same idea as Project 2.

## Run the notebooks

```bash
pip install numpy opencv-python matplotlib jupyter
jupyter notebook
```

A few Day 4 / Day 7 cells expect image files that are not in the repo. The clock and snake need a display (`cv2.imshow`).

## Cursor Cloud Agent

A ready-to-use environment is committed at [`.cursor/environment.json`](.cursor/environment.json). It installs Python, NumPy, headless OpenCV, Matplotlib, and Jupyter.
