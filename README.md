# Image-Similarity-Computation-Using-Graph-Based-Methods
Image Similarity Computation Using Graph-Based Methods by me and @neutrino225

This repository contains code for developing a graph-based model to compute image similarity. The project explores various techniques for quantifying image similarity and compares their performance against traditional metrics.

Here’s an overview of the code structure:

**1.Data Loading and Preprocessing:**

Read images.
Preprocess images by resizing and normalizing.

**2.Extract Patches:**

Divide images into smaller patches.
Visualize patches for inspection.


**4.Color Histogram Comparison:**

Calculate color histograms for each patch.
Compare histograms using methods like Bhattacharyya distance.

**5.Mean Pixel Intensity:**

Compute the mean pixel intensity for each patch.
Compare patches based on intensity differences.

**6.Texture Features (LBP):**

Extract Local Binary Patterns (LBP) features.
Compare patches using histogram intersection.

**7.Simple Structural Features (Number of Edges):**

Detect edges using edge detection algorithms.
Compare patches based on the number of edges.

**8.Grid-based Similarity:**

Divide images into grids.
Compute grid-level features and compare similarities.

**9.Graph Construction and Matching:**

Build graphs with nodes representing patches.
Add edges based on similarity scores.

**Graph Matching:**

Implement graph matching algorithms.
Evaluate and print similarity scores between images.

**10.Metrics Evaluation:**

Compute SSIM, RMSE, PSNR, and ISSM for the images.
Compare the results with graph-based methods.

**11.Results**

Compute and display metrics like accuracy, confusion matrix, and F1-score.
Visualize and interpret the results for different image pairs.
