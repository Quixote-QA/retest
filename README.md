# retest

**retest** is a Python tool for measuring test and pipeline health.  
Inspired by the concept of **Reynolds number** in fluid dynamics, it identifies the most turbulent, flaky, and high-churn tests in your codebase.

---

## 🚀 What It Does

- Calculates a **Test Reynolds Number** to quantify test instability
- Flags flaky, slow, or frequently failing tests via xUnit report analysis
- Detects **bad `assert` usage** in test code (missing messages, weak logic, etc.)
- **Traces and compares stack traces** across test runs to detect:
  - High stack trace noise
  - Repeated vs. unique failure signatures
  - Test failures that shift unpredictably between runs
- Surfaces the **most disruptive tests** with clear metrics and reports to help QA engineers, SDETs, and developers improve test reliability, readability, and effectiveness

---

## 🔍 Why Use It?

In modern CI/CD environments, bad tests cost time and confidence.  
**retestflow** highlights:

- Tests that fail frequently or inconsistently
- Tests with volatile runtimes
- Areas of the codebase that change often but are poorly tested
- Churn-inducing tests that create false alarms in pipelines

---
