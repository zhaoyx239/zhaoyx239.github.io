# Yuxiang Zhao

Hi, I am Yuxiang Zhao (赵宇翔), a master's student at Shanghai Jiao Tong University. My research focuses on speech translation, speech interaction, speech synthesis, voice conversion, and speech security.

- **Email**: [yuxiangzhao@sjtu.edu.cn](mailto:yuxiangzhao@sjtu.edu.cn)
- **Homepage**: [https://zhaoyx239.github.io/](https://zhaoyx239.github.io/)

---

## Education

### Shanghai Jiao Tong University
**M.S. in Electronic Information** | Sep. 2024 - Present

- **GPA**: 3.72/4.0, ranked 46/149
- **Lab**: Cross-Media Language Intelligence Lab
- **Advisor**: Prof. Xie Chen
- **Research Interests**: speech translation, speech interaction, speech security
- **Selected Courses**: Neural Network Theory and Applications (A+), Algorithm Design and Analysis (A), Large-Scale Data Processing Technology (A)

### Shanghai Jiao Tong University
**B.Eng. in Civil Engineering** | Sep. 2020 - Jun. 2024

- **GPA**: 81.78, ranked 20/45

---

## Research Experience

### Speech-to-Speech Translation
**Oct. 2025 - Present**

- Built a cascaded speech-to-speech translation system for low-latency spoken interaction scenarios.
- Integrated ASR, machine translation, and TTS to achieve end-to-end translation with 3-5 seconds of latency.
- Added voice cloning support and explored system design for real-time performance and extensibility.
- **Demo**: [https://translate.sjtuxlance.com/](https://translate.sjtuxlance.com/)

### Synthetic Bridge Training for Machine Translation without Target Data
**Jan. 2025 - May 2025**

- **Status**: Submitted to EMNLP 2026
- **Role**: First author
- Studied machine translation training without target-language data by using large-model-generated synthetic data to train and analyze small-scale NMT models.
- Found that models can still achieve stable performance under purely synthetic data settings, with sequence-level supervision significantly outperforming token-level distillation; performance is mainly affected by data distribution coverage rather than single-sample quality.
- **Paper**: [TODO](TODO)

### Traceable TTS: Toward Watermark-Free TTS with Strong Traceability
**Oct. 2024 - Apr. 2025**

- **Status**: Submitted to Interspeech 2026
- **Role**: First author
- Proposed a watermark-free TTS traceability framework for security risks caused by highly realistic speech synthesis.
- Jointly trained the generation model and discriminator to enable model-level attribution while preserving speech quality, improving cross-domain traceability and generalization.
- **Paper**: [https://arxiv.org/abs/2507.03887](https://arxiv.org/abs/2507.03887)
- **Code**: [https://github.com/zhaoyx239/Traceable-TTS](https://github.com/zhaoyx239/Traceable-TTS)

### Anonymization, Not Elimination: Utility-Preserved Speech Anonymization
**Oct. 2024 - Sep. 2025**

- **Status**: Accepted by TASLP
- **Role**: Co-first author, listed second
- Worked on speech privacy protection and data usability, proposing a unified speech and content anonymization framework.
- Combined flow-matching-based speaker anonymization with generative content editing to reduce identity and content leakage risks while preserving trainability and data utility for downstream ASR and TTS tasks.
- **Paper**: [https://ieeexplore.ieee.org/abstract/document/11493752](https://ieeexplore.ieee.org/abstract/document/11493752)

### X-VC: Zero-shot Streaming Voice Conversion in Codec Space
**Sep. 2025 - Mar. 2026**

- **Status**: Submitted to ACM MM 2026
- **Role**: Second author
- Studied the trade-off between latency and quality for zero-shot voice conversion in real-time interaction scenarios.
- Implemented streaming voice conversion in neural codec space by combining conditional modeling, adaptive normalization, and chunked inference, improving speaker similarity and intelligibility under low-latency constraints.
- **Paper**: [https://arxiv.org/abs/2604.12456](https://arxiv.org/abs/2604.12456)
- **Code**: [https://github.com/Jerrister/X-VC](https://github.com/Jerrister/X-VC)

---

## Internship

### AISpeech Co., Ltd.
**Speech Research Intern** | Jul. 2025 - Present
