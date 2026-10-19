# Hi 👋, I'm Noe

🎓 Big Data & AI Engineering Student  
💼 Tech Lead at Africa Research Center  
💻 AI / full-stack Developer  

I build intelligent systems from first principles and turn machine learning ideas into practical and reproducible software.

My current focus is **Deep Learning, Multimodal AI, NLP, Computer Vision and AI Engineering**, with a growing interest in model robustness, representation learning and evaluation.

## 👨‍💻 About Me

- 🧠 Deep Learning, Machine Learning & Artificial Intelligence
- 👁️ Computer Vision and video understanding
- 🗣️ NLP, Transformers and Speech AI
- 🔗 Multimodal and contrastive representation learning
- 🧪 Model robustness and experimental evaluation
- ⚙️ Backend engineering with Django and REST APIs
- 📊 Data Science & Data Engineering
- 🚀 Building practical AI-powered products

## 🛠️ Tech Stack

### AI & Deep Learning
PyTorch • Hugging Face Transformers • Scikit-learn • OpenCV

### Data
Pandas • NumPy • Matplotlib • Jupyter • SQL

### Backend
Django • Django REST Framework • Node.js • Express.js • REST APIs

### Frontend
Next.js • React • TypeScript • JavaScript • HTML • CSS

### Databases
PostgreSQL • SQL

### Automation & Tools
n8n • Git • GitHub • API Integrations • Linux / WSL

## 🚀 Featured AI Projects

### 🔗 RobustCLIP-Lite — Multimodal Representation Learning
**PyTorch • Computer Vision • Transformers • Contrastive Learning**

Building a lightweight vision-language model from scratch to study multimodal representation learning, retrieval and robustness under limited data.

The model combines:

- A CNN-based image encoder
- A Transformer-based text encoder
- Learned image and text projection heads
- L2-normalized multimodal embeddings
- Symmetric image-to-text / text-to-image contrastive loss
- Learnable temperature scaling
- Image-text retrieval evaluation using Recall@K

Current validation results after 15 epochs:

| Metric | Image → Text | Text → Image |
|---|---:|---:|
| Recall@1 | 1.1% | 1.8% |
| Recall@5 | 7.2% | 7.0% |
| Recall@10 | 11.4% | 11.4% |

Validation loss improved from **3.006 → 2.768** between 5 and 15 epochs.

Current research direction: studying how image and text corruption affect multimodal representations and whether corruption-aware training can improve robustness.

---

### 🧠 TinyGPT from Scratch
**PyTorch • Transformers • NLP • Language Modeling**

Implemented and trained a decoder-only Transformer from first principles in PyTorch.

Built the main Transformer components manually, including:

- Token and positional embeddings
- Query, Key and Value projections
- Scaled dot-product attention
- Causal self-attention
- Multi-head attention
- Feed-forward networks
- Residual connections
- Pre-LayerNorm Transformer blocks
- Autoregressive text generation

Trained on Tiny Shakespeare with a final validation loss of approximately **2.06**.

🔗 [View project](https://github.com/BrainCoder3/tinygpt-from-scratch)

---

### 🎥 Human Action Recognition from Scratch
**PyTorch • OpenCV • 3D CNN • Computer Vision**

Built and trained a 3D CNN from scratch on the KTH Human Actions dataset using the official subject-wise evaluation protocol.

- RGB baseline: **70.5% test accuracy**
- RGB + motion features: **84.7% test accuracy**
- Improved performance by **+14.2 percentage points**
- Used frame-difference motion representations
- Evaluated on unseen subjects
- Analyzed class-level errors using confusion matrices

🔗 [View project](https://github.com/BrainCoder3/human-action-recognition-3dcnn)

---

### 🗣️ Whisper Robustness to Synthetic Noise
**PyTorch • Hugging Face • ASR • Deep Learning**

Built a reproducible evaluation pipeline to study Whisper-small under controlled Gaussian noise.

- Evaluated speech recognition across **0–20 dB SNR**
- Measured WER and CER degradation
- Clean speech WER: **12.9%**
- Observed severe degradation under high-noise conditions
- Analyzed autoregressive repetition and insertion failures

🔗 [View project](https://github.com/BrainCoder3/Whisper-Robustness-to-Synthetic-Noise)

## 💻 Other Projects

- 🔐 SIEM & Big Data Project
- 📊 Global AI Job Market Analysis
- 🌐 LearnCraft
- ⚙️ SchoolGo Backend
- 🔄 Automation & API Projects

## 🔬 Currently Exploring

- Multimodal representation learning
- Contrastive learning
- Vision-language models
- Model robustness under distribution shifts
- Transformers from first principles
- Deep Learning architectures
- AI model evaluation
- Data-efficient learning

## 🎯 Current Goal

I am currently strengthening my foundations in deep learning by implementing architectures from first principles and designing experiments that go beyond model training to study **why models work, when they fail and how they generalize**.

## 📫 Connect with Me

- GitHub: https://github.com/BrainCoder3
- LinkedIn: https://www.linkedin.com/in/no%C3%A9-soulama-32b1663b4/?isSelfProfile=true
  
