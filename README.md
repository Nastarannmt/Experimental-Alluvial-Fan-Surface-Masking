# Experimental-Alluvial-Fan-Surface-Masking
This repository contains a Python script for masking the surface of an experimental alluvial fan from images. The script processes images by converting them to grayscale, applying thresholding, morphological operations, and extracting the largest connected component (representing the fan). 

## Features

- **Automatic Background Removal:** Converts dark background areas to white for better processing.  
- **Gaussian Smoothing:** Reduces noise in the image before thresholding.  
- **Thresholding:** Creates an initial mask by separating the fan from the background.  
- **Mask Refinement:** Uses mathematical morphology and connected component analysis to remove noise and retain only the largest component.  
- **Final Mask Application:** Produces a cleaned-up image with only the fan visible.  
