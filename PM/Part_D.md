# AI Prompt Evaluation - Probability Distributions

## 1. Prompt Given to AI

"Explain probability distributions (normal, uniform, binomial) with Python visualizations."

---

## 2. AI Output

Probability distributions describe how values are distributed in data.

### Normal Distribution

* Bell-shaped curve
* Symmetrical around mean

### Uniform Distribution

* All values have equal probability

### Binomial Distribution

* Discrete distribution
* Based on number of successes in trials

### Python Code

```python
import numpy as np
import matplotlib.pyplot as plt

normal_data = np.random.normal(0, 1, 1000)
plt.hist(normal_data, bins=30)
plt.title("Normal Distribution")
plt.show()

uniform_data = np.random.uniform(0, 1, 1000)
plt.hist(uniform_data, bins=30)
plt.title("Uniform Distribution")
plt.show()

binomial_data = np.random.binomial(n=10, p=0.5, size=1000)
plt.hist(binomial_data, bins=10)
plt.title("Binomial Distribution")
plt.show()
```

---

## 3. Evaluation

### Clarity and Correctness

The explanations are simple and mostly correct.

* Normal distribution is correctly described as bell-shaped and symmetric
* Uniform distribution explanation is correct
* Binomial distribution explanation is basic but correct

However, explanations are very short and do not include deeper understanding like variance or real-world examples.

---

### Visualization Quality

The visualizations are meaningful:

* Normal distribution shows bell shape
* Uniform distribution appears flat
* Binomial distribution shows discrete bars

But improvements can be made:

* Labels for axes are missing
* No legend is provided
* No comparison between distributions

---

## Final Conclusion

The AI response is correct and useful for basic understanding.
The code is runnable and generates proper graphs.

But it can be improved by:

* Adding more explanation
* Improving visualization with labels and titles
* Explaining results in more detail

Overall, it is good for beginners but not detailed.
