# 🍫 Image Captioning using Vision Transformer (ViT) + Transformer Decoder

This repository contains a complete implementation of an **Image Captioning System** using a **Vision Transformer (ViT)** encoder and a **Transformer-based Decoder** trained on the **MS COCO Dataset**.

The notebook demonstrates the full deep learning pipeline including:

- Dataset preprocessing
- Image feature extraction using ViT
- Transformer decoder for caption generation
- Training and evaluation
- BLEU score computation
- Caption inference on test images

---

# 🚀 Features

- ✅ Vision Transformer (ViT) based image encoder
- ✅ Transformer Decoder architecture
- ✅ Positional Encoding implementation
- ✅ Teacher Forcing training strategy
- ✅ Beam Search / Greedy Caption Generation
- ✅ BLEU Score Evaluation
- ✅ COCO Dataset Support
- ✅ GPU compatible (Kaggle / Colab)

---

# 📂 Project Structure

```bash
├── coco-model-v2.ipynb
├── README.md
├── dataset/
├── checkpoints/
├── outputs/
└── requirements.txt
```

---

# 🧠 Model Architecture

## 🔹 Encoder
- Pretrained Vision Transformer (ViT)
- Extracts spatial visual embeddings from images

## 🔹 Decoder
- Multi-Head Self Attention
- Encoder-Decoder Attention
- Feed Forward Network
- Positional Encoding
- Caption token generation

---

# 📊 Dataset

The project uses the **MS COCO Caption Dataset**.

Official Website:

https://cocodataset.org/#download

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/image-captioning-vit-transformer.git
cd image-captioning-vit-transformer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Notebook

```bash
jupyter notebook coco-model-v2.ipynb
```

Or run directly on:

- Google Colab
- Kaggle Notebooks

---

# 🖼️ Sample Results

| Image | Generated Caption |
|---|---|
| 🐶 | "A dog running through the grass." |
| 🚗 | "A red car parked beside the road." |
| 🍕 | "A pizza placed on a wooden table." |

---

# 📈 Evaluation Metrics

The model is evaluated using:

- BLEU-1
- BLEU-2
- BLEU-3
- BLEU-4
- ROUGE-L
- CIDEr *(optional)*

---

# 🛠️ Technologies Used

- Python
- TensorFlow / PyTorch
- Vision Transformer (ViT)
- Transformer Networks
- NumPy
- Matplotlib
- NLTK

---

# 💡 Future Improvements

- Attention visualization
- CLIP-based image embeddings
- Larger transformer architectures
- Fine-tuning on custom datasets
- Real-time caption generation API

---

# 👨‍💻 Author

Developed for research and educational purposes in Deep Learning and Computer Vision.

---

# ⭐ Support

If you found this project helpful:

- Give it a ⭐ on GitHub
- Fork the repository
- Share it with others
