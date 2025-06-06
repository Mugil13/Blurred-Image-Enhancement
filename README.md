# 🖼️ Image Deblurring with Convolutional Autoencoders

This project implements a deep learning-based image restoration model that removes blur from defocused images using convolutional autoencoders.

---

## 🧠 Model Architecture

- **Encoder**: Multiple Conv2D layers to compress features  
- **Latent Space**: Bottleneck representation  
- **Decoder**: Conv2DTranspose layers to reconstruct the sharp image  
- **Loss Function**: Mean Squared Error (MSE)  
- **Optimizer**: Adam  

---

## 📊 Evaluation & Outputs

- Qualitative comparison: Input vs Ground Truth vs Predicted  
- Metrics: MSE, Accuracy (optional display)  

---

## 📁 Dataset Structure

- `sharp/`: Directory containing sharp (clean) images  
- `defocused_blurred/`: Directory containing blurred images  

---

## 🔧 How to Run

### ▶️ On Google Colab
Click the **Open in Colab** badge above.

### 💻 Locally
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt  # Optional if using requirements file
jupyter notebook
```

---

## 📌 Dependencies

Install using:

```bash
pip install -r requirements.txt
