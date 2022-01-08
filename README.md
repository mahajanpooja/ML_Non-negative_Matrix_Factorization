# Non-Negative Matrix Factorization

1 Objective

The objective of this assignment is to implement Non-negative Matrix Factorization (NMF) algorithms and analyze the robustness of NMF algorithms when the dataset is contaminated by large magnitude noise or corruption. More specifically, two NMF algorithms have been implemented and their robustness has been compared.

2 Dataset description

The NMF algorithms have been implemented on two real-world face image datasets: (1) ORL dataset; (2) Extended YaleB dataset.

• ORL dataset: it contains 400 images of 40 distinct subjects (i.e., 10 images per subject). For some subjects, the images were taken at di erent times, varying the lighting, facial expressions and facial details (glasses / no glasses). All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position. All images are cropped and resized to 92 112 pixels.

• Extended YaleB dataset: it contains 2414 images of 38 subjects under 9 poses and 64 illumination conditions. All images are manually aligned,
cropped, and then resized to 168 192 pixels.

3 Tasks

1. Need to implement at least two Non-negative Matrix Factorization (NMF) algorithms (e.g., L1-Norm Based NMF, Hypersurface Cost Based NMF, L1-Norm Regularized Robust NMF, and L2;1-Norm Based NMF).

2. For each algorithm, you need to describe the definition of the objective function as well as the optimization methods used in your implementation.

3. You need to analyze the robustness of each algorithm on two datasets:

4. You need to demonstrate each type of noise used in your experiment (show the original image as well as the image contaminated by noise).

5. To compare the performance and robustness of di erent NMF algorithms, we provide three evaluation metrics: (1) Relative Reconstruction Errors; (2) Average Accuracy (optional); (3) Normalized Mutual Information (optional). For all experiments, you need to use at least one metric, i.e., Relative Reconstruction Errors. 


