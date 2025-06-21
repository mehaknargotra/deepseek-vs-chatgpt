# 📊 Benchmarking DeepSeek vs. ChatGPT

## Overview
This project evaluates the performance of **DeepSeek** and **ChatGPT** across a diverse set of algorithmic problems. The analysis compares their **accuracy**, **execution time**, **memory usage**, and **robustness** to edge cases.

## 🔍 Key Findings
- **ChatGPT** achieved **35.6% higher accuracy** on hard algorithmic tasks.
- It was also **33% faster on average**, particularly in time-constrained or compute-intensive scenarios.
- **DeepSeek** consistently struggled with **string-related tasks** (e.g., *Group Anagrams*, *Longest Substring Without Repeating Characters*).
- **Hyperparameter tuning** (temperature, top-k, top-p) on DeepSeek had **minimal impact** on performance improvements.
- ChatGPT demonstrated superior **robustness in edge-case handling**, **resource efficiency**, and **adaptability to feedback**.

## 📁 Dataset
Problems were sampled from **LeetCode**, covering:
- Arrays & Strings  
- Dynamic Programming  
- Graphs  
- Recursion & Backtracking

### Complexity Breakdown:
- **Easy:** Basic tasks (e.g., Two Sum)
- **Medium:** Multi-step logic (e.g., Generate Parentheses)
- **Hard:** Recursive and graph-based problems (e.g., Median of Two Sorted Arrays)

## ⚙️ Evaluation Metrics
- **Correctness:** Percentage of test cases passed  
- **Latency:** Average execution time (ms)  
- **Memory Usage:** Peak memory usage (MB)  
- **Efficiency:** Resource utilization effectiveness  
- **Edge-case Handling:** Performance on null inputs, large datasets, etc.  
- **Adaptability:** Iterations required to reach a correct solution  

## 🧪 Experiment Setup
- 100 LeetCode-style algorithmic tasks were run.
- Models tested using Python-generated code and evaluated via LeetCode.
- **ChatGPT API** and **DeepSeek via Together.AI** were used.
- Each task ran with identical prompts across both models.

## 📊 Results Summary

| Metric            | DeepSeek             | ChatGPT              | Difference             |
|-------------------|----------------------|----------------------|------------------------|
| Accuracy (Hard)   | 51.7%                | 87.3%                | +35.6% (ChatGPT)       |
| Avg Time (Hard)   | 72.5 ms              | 48.3 ms              | -24.2 ms (ChatGPT)     |
| Efficiency (Hard) | 47.3%                | 79.4%                | +32.1% (ChatGPT)       |
| Memory (Hard)     | 52.3 MB              | 46.1 MB              | -6.2 MB (ChatGPT)      |

> **ChatGPT was the overall winner** in correctness, execution time, memory usage, and adaptability.

## 📉 Weaknesses of DeepSeek
- Fails on many string-related tasks despite multiple tuning strategies.
- High execution latency and low efficiency in memory-heavy problems.
- Required more iterations to converge to a correct solution.

## 📌 Conclusion
While both models show strengths, **ChatGPT outperforms DeepSeek** in nearly all evaluation areas. DeepSeek's open-source foundation and customization options are promising, but current performance lags in reliability, adaptability, and edge-case robustness.

## 📬 Author
**Mehak Nargotra**  
UMass Amherst, College of Information and Computer Sciences  
mnargotra@umass.edu
