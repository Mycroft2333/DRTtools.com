# 欢迎来到 DRTtools.com 社区中心 | Welcome to DRTtools.com Community Hub

<img width="1920" height="1446" alt="image" src="https://github.com/user-attachments/assets/9cb9e0b1-9a7f-41bf-a393-2e2ac398b228" />


这里是 **[DRTtools.com](http://drttools.com)** 的官方社区交流平台。我们创建这个仓库的目的是：
*   **收集用户反馈**：倾听您的声音，让DRTtools变得更好。
*   **追踪和解决问题**：集中管理Bug报告，提高修复效率。
*   **讨论新功能**：与用户共同探讨DRTtools的未来发展方向。
*   **建立一个开放的交流社区**：方便用户之间分享经验、数据和技巧。

This is the official community hub for **[DRTtools.com](http://drttools.com)**. We created this repository to engage with our users, collect feedback, track issues, and foster a collaborative environment.

---

## 如何使用本平台 | How to Use This Platform

我们主要使用 **Issues** 和 **Discussions** 两个功能与您交流。

| 功能 (Feature) | 用途 (Purpose) | 链接 (Link) |
| :--- | :--- | :--- |
| 🐛 **Bug 报告 (Bug Report)** | 如果您在使用中发现任何错误、崩溃或与预期不符的结果，请在此提交。 | [➡️ **提交 Bug**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=bug&template=bug_report.md) |
| ✨ **功能建议 (Feature Request)** | 如果您有任何关于新功能或改进现有功能的想法，请告诉我们。 | [➡️ **提出建议**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=enhancement&template=feature_request.md) |
| 💬 **提问与讨论 (Q&A / Discussion)** | 任何一般性问题、使用技巧分享、结果讨论、数据格式疑问等，都可以在这里发起。 | [➡️ **进入讨论区**](https://github.com/Mycroft2333/DRTtools.com/discussions) |

> **提示**：为了让我们能更快地理解和解决您的问题，提交Bug时请尽量提供详细信息，例如：您的输入数据（可脱敏）、操作步骤、以及出现的错误提示。

---

## 关于 DRTtools | About DRTtools

**DRTtools** is a powerful open-source toolbox developed by Prof. Francesco CIUCCI's group for calculating the Distribution of Relaxation Times (DRT) from Electrochemical Impedance Spectroscopy (EIS) data.

This web interface is created by **Zilong WANG** and **Yuhao WANG** from Prof. Francesco CIUCCI's group.

### 主要功能 | Key Features
*   **Calculate DRT** using Tikhonov regularization method
*   **Flexible regularization parameter** input
*   **Optimize regularization parameter** selection
*   Determine **credible intervals** for DRT
*   Fast **DRT peak fitting**
*   **Visualized** EIS data and DRT analysis results

### 输入文件格式 | Input File Format
Incorrect input file format will cause DRT fail to return results. Please check the input file prompt on the website for the correct format. 如果您不确定文件格式，可以在[**讨论区**](https://github.com/Mycroft2333/DRTtools.com/discussions)提问。

### 理论背景 | Theoretical Background
DRT analysis is a powerful technique for interpreting EIS data without assuming an equivalent circuit model. It deconvolutes the impedance response into a distribution of time constants, providing insights into the electrochemical processes occurring at different timescales.

---

## 学术引用 | Citations

If you use DRTtools in your work, we would appreciate it if you cite the relevant papers.

#### **For general use of DRTtools:**
> Wan, T. H., Saccoccio, M., Chen, C., & Ciucci, F. (2015). Influence of the discretization methods on the distribution of relaxation times deconvolution: implementing radial basis functions with DRTtools. *Electrochimica Acta*, 184, 483-499.

#### **For regularization parameter selection:**
> Maradesa, A., Py, B., Wan, T. H., Effat, M. B., & Ciucci, F. (2023). Selecting the Regularization Parameter in the Distribution of Relaxation Times. *Journal of The Electrochemical Society*, 170, 030502.

#### **For Bayesian credible intervals:**
> Ciucci, F., & Chen, C. (2015). Analysis of electrochemical impedance spectroscopy data using the distribution of relaxation times: A Bayesian and hierarchical Bayesian approach. *Electrochimica Acta*, 167, 439-454.
<br>
> Effat, M. B., & Ciucci, F. (2017). Bayesian and hierarchical Bayesian based regularization for deconvolving the distribution of relaxation times from electrochemical impedance spectroscopy data. *Electrochimica Acta*, 247, 1117-1129.

#### **For Hilbert Transform computation:**
> Liu, J., Wan, T. H., & Ciucci, F. (2020). A Bayesian view on the Hilbert transform and the Kramers-Kronig transform of electrochemical impedance data: Probabilistic estimates and quality scores. *Electrochimica Acta*, 357, 136864.

---

## 合作与联系 | Collaboration

*   **For business cooperation**, please send an email to: `francesco.ciucci AT uni-bayreuth.de`.
*   **For academic cooperation**, please send an email to:
    *   `francesco.ciucci AT uni-bayreuth.de`
    *   `yuhao.wang AT connect.ust.hk` (for fuel cell field)
    *   `zl.wang AT connect.ust.hk` (for battery field)

---

## 数据隐私 | Data Privacy

To improve our service and optimize algorithms, we collect:
*   Basic visitor information (IP, browser version)
*   Uploaded EIS data (periodically cleaned)
*   DRT fitting results (for algorithm optimization)

All data is used solely for service improvement and research purposes. We are committed to protecting your data privacy.
