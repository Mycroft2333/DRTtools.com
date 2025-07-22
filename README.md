# Welcome to DRTtools.com Community Hub


<p align="center">
  <a href="http://drttools.com" target="_blank">
    <img src="https://img.shields.io/badge/Website-DRTtools.com-blue?style=for-the-badge&logo=googlechrome" alt="Website">
  </a>
  <a href="https://github.com/Mycroft2333/DRTtools.com/issues/new/choose" target="_blank">
    <img src="https://img.shields.io/badge/Report_a_Bug-red?style=for-the-badge&logo=github" alt="Report a Bug">
  </a>
  <a href="https://github.com/Mycroft2333/DRTtools.com/discussions" target="_blank">
    <img src="https://img.shields.io/badge/Discussions-green?style=for-the-badge&logo=github" alt="Discussions">
  </a>
  <a href="./README_zh.md" target="_blank">
  <img src="https://img.shields.io/badge/Read_in-简体中文-blue?style=for-the-badge&logo=github" alt="Read in Chinese">
  </a>
</p>

<p align="center">
    <img width="1620" alt="DRTtools.com Screenshot" src="https://github.com/user-attachments/assets/42089fe7-d121-400d-a7f8-065505513fc6">
</p>


This is the official community hub for **[DRTtools.com](http://drttools.com)**. We created this repository to:
*   **Collect user feedback** to make DRTtools better.
*   **Track and resolve issues** efficiently.
*   **Discuss new features** with our users.
*   **Foster a collaborative community** for sharing experiences, data, and techniques.

---

## How to Use This Platform

We primarily use **Issues** and **Discussions** to communicate with you.

| Feature | Purpose | Link |
| :--- | :--- | :--- |
| 🐛 **Bug Report** | If you encounter any errors, crashes, or unexpected results, please submit them here. | [➡️ **Submit Bug**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=bug&template=bug_report.md) |
| ✨ **Feature Request** | If you have ideas for new features or improvements, please let us know. | [➡️ **Request Feature**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=enhancement&template=feature_request.md) |
| 💬 **Q&A / Discussion** | For general questions, sharing tips, discussing results, or asking about data formats, this is the place. | [➡️ **Go to Discussions**](https://github.com/Mycroft2333/DRTtools.com/discussions) |

> **Tip**: To help us understand and resolve your issue faster, please provide detailed information when submitting a bug, such as your input data (anonymized if necessary), the steps to reproduce, and any error messages.

---

## About DRTtools

**DRTtools** is a powerful open-source toolbox developed by Prof. Francesco CIUCCI's group for calculating the Distribution of Relaxation Times (DRT) from Electrochemical Impedance Spectroscopy (EIS) data.

This web interface is created by **Zilong WANG (@ZilongWANG-ust)** and **Yuhao WANG (@Mycroft2333)** from Prof. Francesco CIUCCI's group (@ciuccislab).

### Key Features
*   **Calculate DRT** using Tikhonov regularization method
*   **Flexible regularization parameter** input
*   **Optimize regularization parameter** selection
*   Determine **credible intervals** for DRT
*   Fast **DRT peak fitting**
*   **Visualized** EIS data and DRT analysis results

### Input File Format
Incorrect input file format will cause DRT fail to return results. Please check the input file prompt on the website for the correct format. If you are unsure about the file format, feel free to ask in the [**Discussions**](https://github.com/Mycroft2333/DRTtools.com/discussions) section.

### Theoretical Background
DRT analysis is a powerful technique for interpreting EIS data without assuming an equivalent circuit model. It deconvolutes the impedance response into a distribution of time constants, providing insights into the electrochemical processes occurring at different timescales.

---

## Citations

If you use DRTtools in your work, we would appreciate it if you cite the relevant papers.

#### **For general use of DRTtools:**
> Wan, T. H., Saccoccio, M., Chen, C., & Ciucci, F. (2015). Influence of the discretization methods on the distribution of relaxation times deconvolution: implementing radial basis functions with DRTtools. *Electrochimica Acta*, 184, 483-499.

#### **For regularization parameter selection:**
> Maradesa, A., Py, B., Wan, T. H., Effat, M. B., & Ciucci, F. (2023). Selecting the Regularization Parameter in the Distribution of Relaxation Times. *Journal of The Electrochemical Society*, 170, 030502.

#### **For Bayesian credible intervals:**
> Ciucci, F., & Chen, C. (2015). Analysis of electrochemical impedance spectroscopy data using the distribution of relaxation times: A Bayesian and hierarchical Bayesian approach. *Electrochimica Acta*, 167, 439-454.
> 
> Effat, M. B., & Ciucci, F. (2017). Bayesian and hierarchical Bayesian based regularization for deconvolving the distribution of relaxation times from electrochemical impedance spectroscopy data. *Electrochimica Acta*, 247, 1117-1129.

#### **For Hilbert Transform computation:**
> Liu, J., Wan, T. H., & Ciucci, F. (2020). A Bayesian view on the Hilbert transform and the Kramers-Kronig transform of electrochemical impedance data: Probabilistic estimates and quality scores. *Electrochimica Acta*, 357, 136864.

---

## Collaboration & Contact

*   **For business cooperation**, please send an email to: `francesco.ciucci AT uni-bayreuth.de`.
*   **For academic cooperation**, please send an email to:
    *   `francesco.ciucci AT uni-bayreuth.de`
    *   `yuhao.wang AT connect.ust.hk` (for fuel cell field)
    *   `zl.wang AT connect.ust.hk` (for battery field)

---

## Data Privacy

To improve our service and optimize algorithms, we collect:
*   Basic visitor information (IP, browser version)
*   Uploaded EIS data (periodically cleaned)
*   DRT fitting results (for algorithm optimization)

All data is used solely for service improvement and research purposes. We are committed to protecting your data privacy.
