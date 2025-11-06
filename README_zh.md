# 欢迎来到 DRTtools.com 社区中心

<p align="center">
  <a href="http://drttools.com" target="_blank">
    <img src="https://img.shields.io/badge/访问网站-DRTtools.com-blue?style=for-the-badge&logo=googlechrome" alt="网站">
  </a>
  <a href="https://github.com/Mycroft2333/DRTtools.com/issues/new/choose" target="_blank">
    <img src="https://img.shields.io/badge/报告BUG-red?style=for-the-badge&logo=github" alt="报告BUG">
  </a>
  <a href="https://github.com/Mycroft2333/DRTtools.com/discussions" target="_blank">
    <img src="https://img.shields.io/badge/提问与讨论-green?style=for-the-badge&logo=github" alt="提问与讨论">
  </a>
  <a href="./README.md">
  <img src="https://img.shields.io/badge/Read_in-English-blue?style=for-the-badge&logo=github" alt="Switch to English">
  </a>
</p>

<p align="center">
    <img width="1620" alt="DRTtools.com 截图" src="https://github.com/user-attachments/assets/5092a595-2ba6-4750-a309-aa5a38410c98">
</p>


这里是 **[DRTtools.com](http://drttools.com)** 的官方社区交流平台。我们创建这个仓库的目的是：
*   **收集用户反馈**：倾听您的声音，让DRTtools变得更好。
*   **追踪和解决问题**：集中管理Bug报告，提高修复效率。
*   **讨论新功能**：与用户共同探讨DRTtools的未来发展方向。
*   **建立一个开放的交流社区**：方便用户之间分享经验、数据和技巧。

---

## 如何使用本平台

我们主要使用 **Issues** 和 **Discussions** 两个功能与您交流。

| 功能 | 用途 | 链接 |
| :--- | :--- | :--- |
| 🐛 **Bug 报告** | 如果您在使用中发现任何错误、崩溃或与预期不符的结果，请在此提交。 | [➡️ **提交 Bug**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=bug&template=bug_report.md) |
| ✨ **功能建议** | 如果您有任何关于新功能或改进现有功能的想法，请告诉我们。 | [➡️ **提出建议**](https://github.com/Mycroft2333/DRTtools.com/issues/new?assignees=&labels=enhancement&template=feature_request.md) |
| 💬 **提问与讨论** | 任何一般性问题、使用技巧分享、结果讨论、数据格式疑问等，都可以在这里发起。 | [➡️ **进入讨论区**](https://github.com/Mycroft2333/DRTtools.com/discussions) |

> **提示**：为了让我们能更快地理解和解决您的问题，提交Bug时请尽量提供详细信息，例如：您的输入数据（可脱敏）、操作步骤、以及出现的错误提示。

---

## 关于 DRTtools

**DRTtools** 是由 **Francesco CIUCCI** 教授课题组开发的、一个功能强大的开源工具箱，用于从电化学阻抗谱 (EIS) 数据中计算弛豫时间分布 (DRT)。

该网站界面由 **Francesco CIUCCI** 教授课题组的 **王子龙博士 (Zilong WANG)** 和 **王宇豪博士 (Yuhao WANG)** 创建。

### 主要功能
*   使用**吉洪诺夫正则化 (Tikhonov regularization)** 方法计算DRT
*   灵活的**正则化参数**输入
*   **优化正则化参数**选择
*   确定DRT的**置信区间 (credible intervals)**
*   快速的**DRT峰值拟合**
*   可视化的EIS数据和DRT分析结果

### 输入文件格式
错误的输入文件格式将导致DRT无法返回结果。请在网站上查看输入文件提示以获取正确的格式。如果您不确定，可以在[**讨论区**](https://github.com/Mycroft2333/DRTtools.com/discussions)提问。

### 理论背景
DRT分析是一种强大的EIS数据解析技术，它无需假设等效电路模型。该方法将阻抗响应解卷积为时间常数的分布，从而提供对不同时间尺度下发生的电化学过程的深入理解。

---

## 学术引用

如果您在您的工作中使用 DRTtools，我们非常感谢您引用以下相关论文。

#### **常规使用 DRTtools:**
> [**Wang, Z., Wang, Y., Py, B., Maradesa, A., Liu, J., Wan, T. H., Saccoccio, M., & Ciucci, F. (2025). DRTtools: Freely Accessible Distribution of Relaxation Times Analysis for Electrochemical Impedance Spectroscopy. _ACS Electrochemistry_.**](https://doi.org/10.1021/acselectrochem.5c00334)
>
> Wan, T. H., Saccoccio, M., Chen, C., & Ciucci, F. (2015). Influence of the discretization methods on the distribution of relaxation times deconvolution: implementing radial basis functions with DRTtools. *Electrochimica Acta*, 184, 483-499.

#### **关于正则化参数选择:**
> Maradesa, A., Py, B., Wan, T. H., Effat, M. B., & Ciucci, F. (2023). Selecting the Regularization Parameter in the Distribution of Relaxation Times. *Journal of The Electrochemical Society*, 170, 030502.

#### **关于贝叶斯置信区间:**
> Ciucci, F., & Chen, C. (2015). Analysis of electrochemical impedance spectroscopy data using the distribution of relaxation times: A Bayesian and hierarchical Bayesian approach. *Electrochimica Acta*, 167, 439-454.
> 
> Effat, M. B., & Ciucci, F. (2017). Bayesian and hierarchical Bayesian based regularization for deconvolving the distribution of relaxation times from electrochemical impedance spectroscopy data. *Electrochimica Acta*, 247, 1117-1129.

#### **关于希尔伯特变换计算:**
> Liu, J., Wan, T. H., & Ciucci, F. (2020). A Bayesian view on the Hilbert transform and the Kramers-Kronig transform of electrochemical impedance data: Probabilistic estimates and quality scores. *Electrochimica Acta*, 357, 136864.

---

## 合作与联系

*   **商务合作**, 请发送邮件至: `francesco.ciucci AT uni-bayreuth.de`。
*   **学术合作**, 请发送邮件至:
    *   `francesco.ciucci AT uni-bayreuth.de`
    *   `yuhao.wang AT connect.ust.hk` (燃料电池领域)
    *   `zl.wang AT connect.ust.hk` (电池领域)

---

## 数据隐私

为了改进我们的服务和优化算法，我们会收集以下信息：
*   基本的访客信息 (IP, 浏览器版本)
*   上传的EIS数据 (会定期清理)
*   DRT拟合结果 (用于算法优化)

所有数据仅用于服务改进和学术研究目的。我们承诺保护您的数据隐私。
