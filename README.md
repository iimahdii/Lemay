# Data Analysis on Beans Dataset

**Note on the Use of Techniques in this Notebook:**

Throughout this notebook, a variety of techniques and methodologies have been applied to the dataset for exploratory and analytical purposes. It's important to understand that not all techniques are universally suitable for every dataset. The choice of technique should ideally be based on the nature of the data, the underlying distribution, and the specific goals of the analysis.
The reason for showcasing a range of techniques in this notebook is to demonstrate familiarity and proficiency with them. In a real-world scenario, one would select techniques after careful consideration of the dataset's characteristics and the analysis's objectives.

## Setup

1. First, i have done this task through Google Colab. head over to [Google Colab](https://colab.research.google.com/) and set up a new notebook, if you want.

2. Run the following commands to install necessary dependencies:

```python
!pip install datasets
!pip install imagehash
```

3. Clone this repository into your Colab environment (or download the `.ipynb` notebook and upload it manually):

```python
!git clone https://github.com/iimahdii/Lemay.git
```

4. Open the `Data-Anlysis-Lemay.ipynb` notebook in Colab/Jupyter notebook.

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
