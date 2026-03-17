# AI Prompt Evaluation - Descriptive Statistics & Hypothesis Testing

## 1. Prompt Given to AI

"Explain descriptive statistics and hypothesis testing with a Python example using real-world data."

---

## 2. AI Output

Descriptive statistics are used to summarize and understand data. It includes measures like mean, median, variance, and standard deviation.

Hypothesis testing is used to make decisions about a population using sample data. It involves null hypothesis (no effect) and alternative hypothesis (there is an effect).

### Python Example

```python
import numpy as np
from scipy import stats

# real-world like data (student marks)
data = [45, 67, 89, 23, 90, 56, 78]

# descriptive statistics
mean = np.mean(data)
median = np.median(data)
std = np.std(data)

print("Mean:", mean)
print("Median:", median)
print("Standard Deviation:", std)

# hypothesis testing (one sample t-test)
# assume population mean = 60
t_stat, p_value = stats.ttest_1samp(data, 60)

print("t-statistic:", t_stat)
print("p-value:", p_value)

if p_value < 0.05:
    print("Reject null hypothesis")
else:
    print("Fail to reject null hypothesis")
```

---

## 3. Evaluation

### Clarity and Correctness

The explanation is simple and easy to understand. Basic concepts like mean, median and hypothesis testing are explained correctly. However, the explanation is a bit short and does not go into deep detail.

Overall, it is correct but could include more real-world explanation.

---

### Code Structure and Runability

The code is logically structured:

* First it calculates descriptive statistics
* Then it performs hypothesis testing

The code is easy to read and understand.

It is also runnable, but it requires:

* numpy
* scipy

If these libraries are installed, the code will run without issues.

---

## Final Conclusion

The AI response is mostly correct and useful for beginners. It explains basic concepts clearly and provides working code.

But it can be improved by:

* Adding more explanation
* Using a more realistic dataset
* Explaining output results in detail

Overall, it is good for learning but not very detailed.
