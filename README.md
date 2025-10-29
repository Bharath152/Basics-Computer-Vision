# Computer_vision

Simple collection of examples and exercises for basic computer vision using OpenCV and a Jupyter notebook.

## Contents
- `python_notebook.ipynb` — Notebook with examples: reading images, color spaces (RGB/HSV/Gray), channel splitting, resize/rotate/flip.
- `face_detection.py` — Webcam face detection using Haar cascade.
- images (e.g., `batman image.jpg`)

## Requirements
- Python 3.8+  
- Conda (recommended) or pip

## Setup (Conda) — recommended
1. Create environment:
   - conda create -n basic_cv python=3.10 -y
2. Activate:
   - conda activate basic_cv
3. Install packages:
   - conda install -c conda-forge opencv matplotlib jupyter -y
   - or using pip:
     - pip install opencv-python matplotlib jupyter

## Run the notebook
1. From project folder:
   - jupyter notebook
2. Open `python_notebook.ipynb` and run cells.

## Run face detection
1. Activate environment.
2. Run:
   - python face_detection.py
3. To stop webcam window, press `q`.
