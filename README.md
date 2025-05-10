# Pytorch Custom Dataset Tutorial
This is a more detailed tutorial for loading a custom dataset based off of the [Quickstart Tutorial](https://docs.pytorch.org/tutorials/beginner/basics/quickstart_tutorial.html) by Pytorch. It loads Pytorch's MNIST dataset to train and my provided dataset to test. Code derived from the Quickstart Tutorial is slimmed down to focus more on the loading a custom dataset and smaller test values like "epochs" were minimized to "1" to debug for compatibility faster.

### Python Notebook Files
MyDatasetTutorial.zip - Jupyter notebook option. Includes all the dataset files in the directory stucture needed to run locally.<br>
dataloadingtutorial_2025.ipynb - Google Colab option

### The Dataset
MyImages.zip - The image dataset of personally handwritten 0's and 1's<br>
- Resolution: 32x32<br>
- Format: 8-bit greyscale JPEG<br>
- Items: 1000 images<br>

MyLabels.csv - References index to the image name and its (0 or 1) label
