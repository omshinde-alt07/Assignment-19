Github Link: https://github.com/omshinde-alt07/Assignment-19
# Probability & Statistics Assignment 

## About this assignment

This assignment covers basic concepts of probability distributions and statistics using Python. I have implemented:

* Normal, Uniform, and Binomial distributions
* Simple visualizations using matplotlib
* Basic understanding of how data behaves in each distribution

The goal was to understand the shape, spread, and behavior of different distributions with code.

---

## Files included

* `am.ipynb` → code for first part (basic distributions and plots)
* `pm.ipynb` → code for second part (analysis and additional tasks)

---

## Concepts covered

* Normal distribution (bell-shaped)
* Uniform distribution (equal probability)
* Binomial distribution (success/failure trials)
* Histogram plotting

---

## How to run the code

### 1. Install required libraries

```bash
pip install numpy matplotlib
```

(If using binomial with scipy, then install scipy also)

```bash
pip install scipy
```

---

### 2. Run the code (Jupyter Notebook)

Since the code is in an `.ipynb` file, follow these steps:

```bash
pip install notebook
jupyter notebook
```

* Open the `.ipynb` file in browser
* Click **Run All** or run cells one by one

---

### 3. Output

* Three plots will be shown:

  1. Normal distribution (bell shape)
  2. Uniform distribution (flat)
  3. Binomial distribution (discrete bars)

---

## Example code (main logic)

```python
import numpy as np
import matplotlib.pyplot as plt

# Normal
normal_data = np.random.normal(0, 1, 1000)
plt.hist(normal_data, bins=30)
plt.title("Normal Distribution")
plt.show()

# Uniform
uniform_data = np.random.uniform(0, 1, 1000)
plt.hist(uniform_data, bins=30)
plt.title("Uniform Distribution")
plt.show()

# Binomial
binomial_data = np.random.binomial(n=10, p=0.5, size=1000)
plt.hist(binomial_data, bins=10)
plt.title("Binomial Distribution")
plt.show()
```

---

## My observations (simple)

* Normal distribution is centered around mean
* Uniform distribution has equal values everywhere
* Binomial shows discrete outcomes

---

## Problems faced

* Initially confusion in binomial parameters (n and p)
* Plot looked unclear without proper bins

---

## Conclusion

This assignment helped me understand how different probability distributions look in real data and how to visualize them using Python. It also improved my understanding of randomness and data behavior.

---

## Note

Code is simple and beginner-friendly. Can be improved by adding labels, legends, and combining plots for better comparison.
