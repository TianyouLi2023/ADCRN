# ADCRN: A Lightweight Neural Network for Binaural Reproduction on Head-Mounted Devices

**Tianyou Li\***, **Xiaobin Rong\***, Junjie Shi†, Huiyuan Sun†, Xiaohuai Le†, Chuanzeng Huang†, Jing Lu\*  
\* Key Laboratory of Modern Acoustics, Nanjing University · † ByteDance  

---

### Demo Page  
Interactive audio demonstrations are available at:  
👉 [https://adcrn-icassp-demo.netlify.app/](https://adcrn-icassp-demo.netlify.app/)

---

### Abstract  
Binaural reproduction (BR) on head-mounted devices (HMDs) transforms multi-microphone recordings into binaural signals. Conventional binaural signal matching (BSM) methods predict reproduction filters from predefined source distributions but suffer from degradation under mismatched configurations. Recent DNN-based BR approaches improve content accuracy and spatial fidelity, yet their heavy computational and parameter demands hinder deployment on resource-limited HMDs, and their effectiveness in such contexts remains insufficiently studied.  

This repository presents **ADCRN (Attention-enhanced Dual-path Convolutional Recurrent Network)**, a lightweight neural architecture featuring a dual-path recurrent bottleneck for temporal–spectral modeling and efficient channel attention for cross-channel recalibration. Evaluations on simulated datasets derived from AR-glasses microphone arrays demonstrate that ADCRN achieves **state-of-the-art performance** in both objective and subjective assessments, with significantly reduced parameters and computational complexity.

---

### Citation  
If you find this work useful, please cite as:  

> Li, T., Rong, X., Shi, J., Sun, H., Le, X., Huang, C., and Lu, J. (2025).  
> *ADCRN*. Available at: [https://github.com/TianyouLi2023/ADCRN](https://github.com/TianyouLi2023/ADCRN) (Last viewed Sep. 23, 2025).  
