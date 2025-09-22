# ADCRN: A Lightweight Neural Network for Binaural Reproduction on Head-Mounted Devices

**Tianyou Li\***, **Xiaobin Rong\***, Junjie Shi†, Huiyuan Sun†, Xiaohuai Le†, Chuanzeng Huang†, Jing Lu\*  
\* Key Laboratory of Modern Acoustics, Nanjing University · † ByteDance  

---

### Demo Page  
Interactive audio demonstrations are available at:  
👉 [https://adcrn-icassp-demo.netlify.app/](https://adcrn-icassp-demo.netlify.app/)

---

### Abstract  
Binaural reproduction (BR) on head-mounted devices (HMDs) converts microphone recordings into binaural signals. Conventional binaural signal matching (BSM) predicts BR filters based on predefined source distributions, but suffers from performance degradation under mismatched configurations. Recent deep neural network (DNN)-based BR approaches have shown advances in content accuracy and spatial fidelity. However, their high computational and parameter demands hinder lightweight deployment, and their effectiveness on HMDs remains unexplored. 

This repository proposes a lightweight Attention-enhanced Dual-path Convolutional Recurrent Network (ADCRN), featuring a dual-path recurrent bottleneck for temporal–spectral modeling and efficient channel attention modules for cross-channel feature recalibration. Experiments on simulated datasets from microphone arrays mounted on augmented reality glasses show that ADCRN achieves state-of-the-art performance on both objective metrics and subjective evaluations, outperforming BSM and prior DNN-based BR models with fewer parameters and lower computational complexity. 

---

### Citation  
If you find this work useful, please cite as:  

> Li, T., Rong, X., Shi, J., Sun, H., Le, X., Huang, C., and Lu, J. (2025).  
> *ADCRN*. Available at: [https://github.com/TianyouLi2023/ADCRN](https://github.com/TianyouLi2023/ADCRN) (Last viewed Sep. 23, 2025).  
