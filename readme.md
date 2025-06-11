# 🎬 Movie Frame Identification with CNN-LSTM

This project focuses on **automated movie title classification** using frame-level image features. We built a deep learning pipeline that processes individual movie frames and predicts the corresponding movie name using a **CNN-LSTM hybrid model**.

---

## 🧪 Models Used

- **CNN (ResNet-based)** for frame-level feature extraction
- **LSTM** for sequential modeling across frames
- Model trained and tested on curated movie frame datasets

---

## 🚀 Running the Project (GPU Required)

This project requires **GPU acceleration** for training and was tested on:

- 🖥️ **ECE GPU Cluster** (via Jupyter)
- 🇪🇺 **LUMI Supercomputer** (Python batch jobs via Slurm)

---

## ⚙️ Local Setup

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/movie-classification-group9.git
cd movie-classification-group9
```

---

2. Create Python environment

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
