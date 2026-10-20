# Image Clustering- K-Means and Spectral Clustering
 K-Means and Spectral Clustering on generated datasets and real images using Python.

## Course
BSCS 4388 – Computer Vision

## Project Description
This project applies two clustering algorithms, K-Means and Spectral Clustering, using Python. Both algorithms are tested on generated datasets and real images to see how they group data points and divide images into different regions.

## Objectives
- Apply K-Means clustering to generated data and a real image.
- Apply Spectral Clustering to generated data and a real image.
- Plot the data before and after clustering.
- Save the results as image files.

## Technologies Used
- Python 3
- NumPy
- Matplotlib
- Scikit-learn
- Scikit-image

## Datasets
### Lab 1: K-Means
1. **Generated Data:** 1,000 samples with 4 centers.
2. **Coffee Image:** The coffee image provided by `skimage.data.coffee()`.

### Lab 2: Spectral Clustering
1. **Generated Data:** 1,000 samples arranged in two circles.
2. **Coins Image:** The coins image provided by `skimage.data.coins()`.

## Project Files
- `kmeans_clustering.py` – Code for K-Means clustering.
- `spectral_clustering.py` – Code for Spectral Clustering.
- `BSCS_4388_Lab1_2_Clustering.ipynb` – Jupyter Notebook containing the lab steps and outputs.

## Output Images

### Lab 1: K-Means Clustering

**Generated Data - Before K-Means**
<img width="689" height="490" alt="Generated Data Before K-means" src="https://github.com/user-attachments/assets/73affcbb-bbea-478c-9452-71eb144106b2" />


**Generated Data - After K-Means**
(Generated%20Data%20After%20K-Means.png)

**Coffee Image - Before K-Means**
(Coffee%20Image%20Before%20K-Means.png)

**Coffee Image - After K-Means**
(Coffee%20Image%20After%20K-Means.png)


### Lab 2: Spectral Clustering

**Generated Circles - Before Spectral Clustering**
<img width="690" height="490" alt="Generated Circles Before Spectral Clustering" src="https://github.com/user-attachments/assets/728cbc04-c2c1-479a-85cf-eeff3c8cf616" />


**Generated Circles - After Spectral Clustering**
<img width="690" height="490" alt="Generated Circles After Spectral Clustering" src="https://github.com/user-attachments/assets/e463550f-7815-4a17-8fb4-7cf38e331ee4" />


**Coins Image - Before Spectral Clustering**
<img width="587" height="490" alt="Coins Image Before Spectral Clustering" src="https://github.com/user-attachments/assets/6417b505-fe61-451e-9415-c0b734510c6b" />

**Coins Image - After Spectral Clustering**
<img width="585" height="490" alt="Coins Image After Spectral Clustering" src="https://github.com/user-attachments/assets/bed5a8ba-dae7-4f04-98ea-ebb64aace949" />


## Installation
Install the required libraries by running:

```bash
pip install numpy matplotlib scikit-learn scikit-image
```

## How to Run
Run either Python script from the terminal:

```bash
python kmeans_clustering.py
```

```bash
python spectral_clustering.py
```

You can also open `BSCS_4388_Lab1_2_Clustering.ipynb` in Jupyter Notebook and run the cells in order.

## Conclusion
This lab helped me practice using K-Means and Spectral Clustering on generated datasets and real images. The results show how clustering can group similar data points and separate different regions in an image.
