# HiHello (Alphabetical Sign Language Detection)

## Prerequisites
- Python
- Jupyter Notebook
- Anaconda

## Create Environment (cmd)
Create a Python virtual environment using the `command line`. A virtual environment isolates your project's dependencies from other projects, ensuring consistent behavior.
```shell
> python -m venv env
> env\Scripts\activate
> (env) ... command
```

## Anaconda Prompt
Commands to manage environments using [Anaconda](https://www.anaconda.com/download), a popular distribution for scientific computing to manage dependencies and `Python` versions easily.
```powershell
> conda env list
> conda create -n <environment-name>
> conda activate -n <environment-name>
```

## PIP installation
PIP installation using a script. A Python package manager that is essential for installing and managing Python packages.
```powershell
> curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
> python get-pip.py
> pip --version
```

## Packages
Commands to install essential Python packages, including `scikit-learn` for machine learning, `opencv-python` for computer vision, `numpy` for numerical operations, and other essential packages.

- Sklearn &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install scikit-learn`
- OpenCV &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install opencv-python`
- NumPy &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install numpy`
- Matplotlib &nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install matplotlib`
- Mediapipe &nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install mediapipe`
- Pickle &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;&nbsp;&nbsp;`> pip install pickle`

## Dataset

The [American Sign Language (ASL) Alphabet Dataset](https://www.kaggle.com/datasets/debashishsau/aslamerican-sign-language-aplhabet-dataset/data) contains images representing hand gestures of the American Sign Language alphabet. Each image corresponds to a specific letter of the alphabet (A-Z), including gestures for other common signs used in the ASL system. The dataset is widely used for training machine learning models for hand gesture recognition tasks.

### Key Features:
- **Image Size:** Each image is 200x200 pixels, providing a standardized format for processing.
- **File Format:** The dataset is in `.jpg` format, which ensures lossless compression of image data.
- **Classes:** 29 classes (26 alphabets A-Z, and 3 additional signs for space, delete, and nothing).
- **Training Data:** 87,000 images are available for training, with an equal distribution across the classes.

This dataset is well-suited for projects involving computer vision and gesture recognition, especially for creating systems that can interpret sign language alphabet gestures. It can be used to train models to detect and classify hand gestures, which makes it useful in projects like **HiHello**, an alphabetical sign language detection system.

## Demo Video
![HiHello Demo](https://www.youtube.com/watch?v=F2z51vJ0Lk8 "HiHello Demo")