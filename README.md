# Data Analysis on Beans Dataset

## Setup

1. First, ya need to make sure you're on Google Colab. If not, head over to [Google Colab](https://colab.research.google.com/) and set up a new notebook.

2. Run the following commands to install necessary dependencies:

```python
!pip install datasets
!pip install imagehash
```

3. Clone this repository into your Colab environment (or download the `.ipynb` notebook and upload it manually):

```python
!git clone [Data_Anlysis_Lemay](https://github.com/iimahdii/Lemay.git)
```

4. Open the `Data-Anlysis-Lemay.ipynb` notebook in Colab.

## Running the Analysis

1. Execute each cell in sequence. The notebook will guide you through:
   - Loading the "beans" dataset
   - Understanding the dataset's structure
   - Visualizing sample images
   - Checking the class distribution
   - Applying image augmentations
   - Extracting and visualizing image features using PCA
   - Identifying duplicate images.

## Why the "Beans" Dataset?

I chose the "beans" dataset 'cause it's a relatively simple dataset that showcases the challenges in classifying agricultural products, which is super important in many parts of the world. With only 3 classes, it's easy to visualize and understand the data, but also offers enough complexity to demonstrate the power of modern machine learning techniques. Plus, the average image size being consistent shows the dataset's been preprocessed and is ready for analysis and model training.

## Troubleshooting

If you encounter any errors related to missing libraries or modules, make sure you've installed all the dependencies mentioned above.
