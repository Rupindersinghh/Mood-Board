Overview:
This project leverages deep learning and computer vision techniques to automatically generate artistic mood boards. The system uses a Convolutional Neural Network (CNN) for image classification and combines it with creative collage algorithms (including grid and masonry layouts) to arrange images into visually compelling mood boards. It’s designed for designers, creative technologists, and anyone interested in the intersection of AI and visual arts.

Key Features:

Automated Image Classification:
Uses a CNN (built with TensorFlow/Keras) to classify fashion-related images. The model is trained on datasets like Fashion MNIST and can be adapted for custom image sets.

Dynamic Collage Generation:
Implements multiple layout strategies:

Fixed Grid Layout: Uniformly resizes and arranges images in a neat grid.
Masonry Layout: Organizes images in columns of varying heights to create an organic, Pinterest-style collage.
Artistic Enhancements: Applies random scaling, rotation, contrast adjustments, and borders to images for a more dynamic, visually appealing output.
Customizability:
Easily tweak parameters such as board dimensions, number of columns, spacing, and transformation ranges to suit different aesthetic preferences.

Multi-Platform Support:
The code can run in Jupyter Notebook for rapid prototyping or as a standalone Python script from the command line, making it versatile for development and deployment.

Technologies Used:

Python 3.x
TensorFlow / Keras for CNN modeling
PIL/Pillow for image processing
Jupyter Notebook for interactive development
Usage Example:

Train or Load the CNN Model:
Train your model using Fashion MNIST (or another dataset) to classify images, then save the model for inference.

Generate a Mood Board:
Run the provided scripts to read images from specified folders, apply transformations, and generate a mood board. For example, the script uses a masonry layout to create a collage, which is then displayed or saved as an image file.

