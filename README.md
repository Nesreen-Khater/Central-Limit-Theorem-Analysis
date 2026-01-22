# Central Limit Theorem Simulation and Analysis

## Description
This project investigates the Central Limit Theorem (CLT) using an exponentially distributed population. Samples of different sizes are generated to examine how the distribution of sample means converges to a normal distribution as the sample size increases. The project combines simulation, visualization, and hypothesis testing to demonstrate the CLT in practice.

---

## Objectives
- Understand the properties of the exponential distribution.
- Apply the Central Limit Theorem to non-normal populations.
- Analyze the effect of sample size on the distribution of sample means.
- Perform hypothesis testing on sample means.
- Visualize the convergence toward a normal distribution.

---

## Dataset
- **Type:** Simulated data
- **Distribution:** Exponential
- **Description:** Random samples are generated from an exponential distribution to study the behavior of sample means under different sample sizes.

---

## Methodology
1. Generate an exponential population distribution.
2. Draw random samples with different sample sizes.
3. Compute sample means for each sample.
4. Analyze the distribution of sample means.
5. Compare sample mean distributions with the normal distribution.
6. Conduct hypothesis testing on population and sample means.

---

## Statistical Concepts Used
- Exponential Distribution
- Central Limit Theorem (CLT)
- Sample Mean
- Variance and Standard Deviation
- Hypothesis Testing
- Normal Distribution Approximation

---

## Visualizations
The notebook includes:
- Histogram of the exponential population distribution
- Histograms of sample means for different sample sizes
- Visual comparison showing convergence to normality
- Plots illustrating the effect of increasing sample size

These visualizations demonstrate how increasing the sample size improves the normal approximation of sample means.

- CLT for different types of data
  [Titanic-Dataset.csv](https://github.com/user-attachments/files/24789551/Titanic-Dataset.csv)<img width="1490" height="1190" alt="image" src="https://github.com/user-attachments/assets/68f6b774-d9fe-4cb8-b7a9-32639deae129" />


---

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Math
- Jupyter Notebook

---

## How to Run
1. Clone the repository
2. Open `CLT analysis`
3. Run all cells sequentially to reproduce the simulations and plots

---

## Discussion
The results confirm the Central Limit Theorem by showing that even when the population distribution is non-normal (exponential), the distribution of sample means approaches a normal distribution as the sample size increases. Larger sample sizes lead to reduced variability and more symmetric distributions.
