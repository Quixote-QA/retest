# retest

**retest** is a Python tool for measuring test and pipeline health.  
Inspired by the concept of **Reynolds number** in fluid dynamics, it identifies the most turbulent, flaky, and high-churn tests in your codebase.

---

## 🚀 What It Does

- Calculates a **Test Reynolds Number** to quantify test instability
- Parses test result outputs (e.g., xUnit XML)
- Flags flaky, slow, and frequently failing tests
- Visualizes test health across time and CI pipelines
- Analyzes test source code for **bad assert patterns** (e.g., missing or bad asserts)
- Helps SDETs, QA leads, and DevOps prioritize test fixes and refactors

---

## 🔍 Why Use It?

In modern CI/CD environments, bad tests cost time and confidence.  
**retestflow** highlights:

- Tests that fail frequently or inconsistently
- Tests with volatile runtimes
- Areas of the codebase that change often but are poorly tested
- Churn-inducing tests that create false alarms in pipelines

---
