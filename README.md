# Singular-Value-Decomposition-SVD-for-image-compression-and-analysis

Consider an image represented as a matrix:
A ∈ R
150×100 (grayscale image)
We aim to use the Singular Value Decomposition (SVD) for image compression and analysis. The task is divided into several parts for clarity.

(a) Perform SVD
Compute the Singular Value Decomposition of A:
A = UΣV
T
where U and V are orthogonal matrices, and Σ is a diagonal matrix containing singular values σ1 ≥ σ2 ≥ · · · ≥ σr, where r is rank of A.

(b) Reconstruction with Multiple Ranks
Construct rank-k approximations of A for k ∈ {5, 10, 20, 40, 60}:
Ak = UkΣkV
T
k
where Uk, Σk, Vk correspond to the top-k singular values and their corresponding singular vectors. Display the original image and each approximation side by side

(c) Error Analysis
For each k, compute the Frobenius norm of reconstruction error:
Ek = ∥A − Ak∥F
Plot Ek as a function of k.

(d) Energy Preservation
Compute the proportion of variance (energy) preserved by the top-k singular
values:
Energy(k) =
Pk
i=1 σ
2
P
i
r
i=1 σ
2
i
where r = rank(A). Plot Energy(k) vs. k.
