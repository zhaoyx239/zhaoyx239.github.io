# Yuxiang Zhao

- **Email**: [yuxiangzhao@sjtu.edu.cn](mailto:yuxiangzhao@sjtu.edu.cn)
- **Research Interests**: speech translation, speech security

---

## Education

### Shanghai Jiao Tong University
**M.S. Student, School of Computer Science** | Sep. 2024 - Present
- **Lab**: X-LANCE Lab
- **Advisor**: Prof. Xie Chen

### Shanghai Jiao Tong University
**B.Eng. in Civil Engineering** | Sep. 2020 - Jun. 2024

---

## Research Experience

### Speech Translation and Low-Latency Simultaneous Interpretation
**Oct. 2025 - Present**

- Built **X-Translator**, a cascaded ASR+MT+TTS speech-to-speech translation system for real-time spoken interaction, achieving 3-5 seconds of end-to-end latency with voice cloning support.
- Designed a multidimensional evaluation framework for speech translation, covering speech-to-text translation, speech-to-speech translation, offline generation, and streaming generation.
- Evaluated translation quality, speech quality, speaker preservation, emotion and paralinguistic fidelity, temporal consistency, and streaming latency in a unified protocol.
- Studied machine translation training without target-language data by using LLM-generated synthetic target-side data to train compact NMT models, analyzing the effects of distribution coverage, sample quality, and sequence-level supervision.

### Speech Security, Anonymization, and Traceable Generation
**Oct. 2024 - Oct. 2025**

- Proposed a watermark-free TTS traceability framework that jointly trains a generation model and discriminator for model-level attribution while preserving speech quality.
- Improved traceability robustness and generalization in cross-domain scenarios without relying on explicit speech watermarks.
- Built a utility-preserved speech anonymization framework that combines flow-matching-based speaker anonymization with generative content editing.
- Reduced identity and content leakage risks while preserving the usefulness of anonymized data for downstream ASR, TTS, and other speech tasks.

---

## Publications

1. <strong>Yuxiang Zhao</strong>, Yunchong Xiao, Yushen Chen, Zhikang Niu, Shuai Wang, Kai Yu, Xie Chen<sup>&dagger;</sup>.  
   **Traceable TTS: Toward Watermark-Free TTS with Strong Traceability.**  
   Submitted to INTERSPEECH 2026.  
   [[Paper](https://arxiv.org/abs/2507.03887)] [[Code](https://github.com/zhaoyx239/Traceable-TTS)]

2. <strong>Yuxiang Zhao</strong>, Yanjie An, Hanzheng Li, Xuhui Shen, Keqi Deng, Shuai Fan, Kai Yu, Xie Chen<sup>&dagger;</sup>.  
   **Distilling Compact Machine Translation Models from Synthetic Target-Side Data.**  
   Submitted to EMNLP 2026.

3. Yunchong Xiao<sup>*</sup>, <strong>Yuxiang Zhao</strong><sup>*</sup>, Ziyang Ma, Shuai Wang, Kai Yu, Jiachun Liao, Xie Chen<sup>&dagger;</sup>.  
   **Anonymization, Not Elimination: Utility-Preserved Speech Anonymization.**  
   IEEE Transactions on Audio, Speech and Language Processing, 2026.  
   [[Paper](https://ieeexplore.ieee.org/abstract/document/11493752)]

4. Yanjie An<sup>*</sup>, <strong>Yuxiang Zhao</strong><sup>*</sup>, Yichi Zhang, Qixi Zheng, Yujie Tu, Keqi Deng, Kai Yu, Xie Chen<sup>&dagger;</sup>.  
   **OpenSTBench: Beyond Semantic Evaluation for Speech Translation.**  
   Submitted to EMNLP 2026.  
   [[Paper](https://arxiv.org/abs/2605.30792)] [[Code](https://github.com/sjtuayj/OpenSTBench)]

5. Qixi Zheng, <strong>Yuxiang Zhao</strong>, Tianrui Wang, Wenxi Chen, Kele Xu, Yikang Li, Qinyuan Chen, Xipeng Qiu, Kai Yu, Xie Chen<sup>&dagger;</sup>.  
   **X-VC: Zero-shot Streaming Voice Conversion in Codec Space.**  
   Submitted to ACM MM 2026.  
   [[Paper](https://arxiv.org/abs/2604.12456)] [[Code](https://github.com/Jerrister/X-VC)] [[Demo](https://x-vc.github.io/)]

6. Ruiqi Yan, Wenxi Chen, Zhanxun Liu, Ziyang Ma, Haopeng Lin, Hanlin Wen, Hanke Xie, Jun Wu, Yuzhe Liang, <strong>Yuxiang Zhao</strong>, Pengchao Feng, Jiale Qian, Hao Meng, Yuhang Dai, Shunshun Yin, Ming Tao, Lei Xie, Kai Yu, Xinsheng Wang, Xie Chen<sup>&dagger;</sup>.  
   **SoulX-Duplug: Plug-and-Play Streaming State Prediction Module for Realtime Full-Duplex Speech Conversation.**  
   Submitted to INTERSPEECH 2026.  
   [[Paper](https://arxiv.org/abs/2603.14877)] [[Code](https://github.com/Soul-AILab/SoulX-Duplug)] [[Model](https://huggingface.co/Soul-AILab/SoulX-Duplug-0.6B)] [[Dataset](https://huggingface.co/datasets/Soul-AILab/SoulX-Duplug-Eval)]

<sup>*</sup> Equal contribution. <sup>&dagger;</sup> Corresponding author.

---

## Internship

### AISpeech Co., Ltd.
**Speech Research Intern** | Jul. 2025 - Present
