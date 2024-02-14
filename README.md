# Assignment-1-vaddelli12-
Project Readme: 
Processing XML, 
Resizing and Cropping Images, 
and Comparing Histograms.
Project Overview:
This project uses scikit-image for various image processing algorithms, XML processing, and image cropping and resizing. 
Parsing XML data and obtaining pertinent information from it are steps in the processing of XML.
Reading XML files, navigating the XML structure, and extracting particular components or properties are a few examples of this.
The primary features include converting standard photos to grayscale, showing grayscale images alongside the accompanying pixel intensity histograms, computing edge histograms, applying the Sobel edge filter, and comparing histograms using various metrics. 
Select an image processing library and programming language that allow for the computation and comparison of histograms. 
Popular options include JavaScript with libraries like `ImageMagick` or `opencv4nodejs`, or Python with libraries like `OpenCV` or `matplotlib`.
To compute histograms for your photos, utilize the provided code or library. 
Use an appropriate histogram comparison technique, like the correlation coefficient or Chi-Squared distance. 
Principal Component Analysis (PCA) is used to reduce dimensionality and the Histogram of Oriented Gradient (HOG) feature descriptor is also utilized.
Prerequisites:
Ensure you have the following dependencies installed before running the project:
- Python (>= 3.6)
- scikit-image
- NumPy
- Matplotlib
Installation sites:
pip install scikit-image numpy matplotlib.
PYCharm : https://www.jetbrains.com/pycharm/download/?section=windows

Usage
1.Git clone 
https://github.com/yourusername/yourproject.git cd project to start cloning the repository.
2. Execute Python main.py, the main script.
The pipeline—which includes XML processing, image editing, and histogram comparisons—will be carried out in full by the script.

Project Organization:

 - {data/}: Holds input photos and XML files.
 - The source code files are stored at `src/}.
  - Processing of XML is handled by `xml_processor.py`.
  - `image_processor.py}: This script includes routines to calculate edge histograms, crop images, resize them, convert them to grayscale, and apply Sobel edge filters.
  - `histogram_comparison.py}: This script compares histograms using the Cosine, Manhattan, and Euclidean distances.
  - The `hog_descriptor.py} script calculates the Oriented Gradient (HOG) Histogram of features.
  - `pca_reduction.py}: Reduces dimensionality by using Principal Component Analysis (PCA).
  - {main.py}: The primary script, which carries out the entire 
the process.
Acknowledgments : 
image processing pipeline and unifies all modules.
- "results/": Holds the plots and photos produced as a result of
- The project relies on the scikit-image library for image processing tasks.
- Various image processing techniques are applied based on scikit-image documentation and examples.
License:
This project is licensed under the MIT License - License: BSD License (Files: * Copyright: 2009-2022 the scikit-image.

System Requirements:
Operating Systems: windows 9 and above, linux, and mac
The performance is better at windows 10 and 11 with i5 and advanced generations.
Storage Required: 1gb and above.
Generation : i4 and above.
