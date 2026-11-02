Laboratory exercises for the course *Digital Image Processing and Analysis* (*Digitalna obrada i analiza slike*) at the Faculty of Electrical Engineering and Computing (FER), University of Zagreb. All exercises are Jupyter notebooks written in Python and run in Google Colab. The task descriptions and notebook framework come from the course, and the solutions are mine.

## Contents

| Notebook | Topics | Status |
|---|---|---|
| `DIPA_LAB_1_KB.ipynb` | Image representations, unary and binary operations, digital angiography, linear convolution, quantization, sampling, pixelization, aliasing and the moiré effect | solved |
| `DIPA_LAB_2_KB.ipynb` | Discrete Fourier transform, frequency-domain filtering, discrete cosine transform and compression, histograms and equalization, histogram modeling, average and median filtering, unsharp masking | solved |
| `DIPA_LAB_3_KB.ipynb` | Image acquisition and restoration (inverse, pseudo-inverse and Wiener filter), image features, edge detection (Sobel, Prewitt, compass and Laplacian operators), texture features | partially solved |
| `DIPA_LAB_4_KB.ipynb` | Image segmentation (thresholding, automatic and local thresholds, edge and texture segmentation), image registration, optical flow | partially solved |

Parts of Lab 3 and Lab 4 are not finished, and the unsolved cells still contain the original placeholders.

## Technologies

Python, NumPy, SciPy, OpenCV, scikit-image, Matplotlib, Google Colab

## Running the notebooks

The notebooks mount Google Drive and read the test images from a folder named `Images` (e.g. `/content/drive/MyDrive/Images/`). To run them, upload the images from the course to that folder in your own Drive, or change the paths in the notebooks.

## Author

Karla Budimir
