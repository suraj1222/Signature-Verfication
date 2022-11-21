# Signature-Verfication
Application is to verify the two signatures.

This Application helps mathematically evaluate similarity of two signatures. This provides both facilities of uploding a pitcure as well as capturing picture of both the signatures. Both the images will be displayed on the screen that are being evaluted and the person can also crosscheck if the results given are fair enough. Once the image is been canceled there will be a popup which will show the percentage match of the signatures. The signatures are evaluated using a method called structural_similarity in skimage.metrics package. https://scikit-image.org/docs/stable/api/skimage.metrics.html#skimage.metrics.structural_similarity

# Prerequisites
 1. Python >=3.6
 
 2. OpenCV
 
 3. Scipy
 
 4. Scikit-image

# Run
1. pip install requirements.txt
2. python main.py
