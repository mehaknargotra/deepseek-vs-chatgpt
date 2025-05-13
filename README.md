# 📊 Benchmarking DeepSeek vs. ChatGPT

## Overview
This project evaluates the performance of **DeepSeek** and **ChatGPT** across a diverse set of algorithmic problems. The analysis compares their **accuracy**, **execution time**, **memory usage**, and **robustness** to edge cases.

## 🔍 Key Findings
- **ChatGPT** was **35.6% more accurate** on complex algorithmic tasks.
- It was also **33% faster on average**, particularly in time-constrained or compute-intensive scenarios.
- **DeepSeek** underperformed on string-heavy problems, despite multiple tuning attempts and retries.

## 📁 Dataset
Problems were sampled from **LeetCode**, covering:
- Arrays & Strings  
- Dynamic Programming  
- Graphs  
- Recursion & Backtracking

## ⚙️ Evaluation Metrics
- **Correctness:** Pass/fail against test cases  
- **Latency:** Average time to generate and execute code  
- **Memory:** Peak memory usage  
- **Edge-case Handling:** Performance on custom-designed difficult prompts

## 🧪 Experiment Setup
- Responses were collected using API calls (OpenAI for ChatGPT and DeepSeek's public interface).
- Each model was given identical prompts, and outputs were parsed and tested programmatically.

## 📌 Conclusion
While both models demonstrate strong general capabilities, **ChatGPT consistently outperforms DeepSeek** in algorithmic problem-solving under the tested conditions.
