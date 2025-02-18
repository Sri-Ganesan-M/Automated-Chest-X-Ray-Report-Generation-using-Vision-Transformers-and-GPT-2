## 🚀 **Transformers-Based Approach for Automated Chest X-ray Report Generation**  

![Medical AI](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/X-ray_of_hand_with_rheumatoid_arthritis.jpg/800px-X-ray_of_hand_with_rheumatoid_arthritis.jpg)  

### 📌 **Overview**  
Radiology reports are essential for diagnosing and treating medical conditions, but manual report generation can be time-consuming and prone to variability. Our research introduces **Vision-GPT2**, a hybrid AI model combining **Vision Transformer (ViT)** for image processing and **GPT-2** for natural language generation to automate radiology report generation with **high accuracy and efficiency**.  

---
🔗 **Project Report:** [Click Here](https://drive.google.com/file/d/1CLuDDzRjRBUQswLLSF-PrI8ZD2ldhRTk/view?usp=sharing)  
___

### 📊 **Key Features**  
✅ **Transformer-Based Model** – Combines ViT and GPT-2 for high-quality report generation  
✅ **Medical Image Processing** – Analyzes **chest X-ray** images for automated reporting  
✅ **Deep Learning Integration** – Uses **self-attention & cross-attention** for better image-text alignment  
✅ **Optimized Training Pipeline** – Fine-tuned with mixed precision and adaptive learning rates  
✅ **Clinically Relevant Reports** – Generates structured, **human-like** radiology reports  

---

### 📚 **Methodology**  
#### 🔹 **Data Preprocessing**  
🔹 Resized images to **224×224 pixels**  
🔹 Used **albumentations** for data augmentation  
🔹 Normalized images for consistent model performance  

#### 🔹 **Model Architecture**  
📌 **Vision Transformer (ViT)** – Extracts image embeddings from chest X-rays  
📌 **GPT-2 Language Model** – Generates corresponding radiology reports  
📌 **Cross-Modal Attention** – Aligns visual features with textual descriptions  

#### 🔹 **Training & Evaluation**  
✔ **Optimizer:** Adam with **OneCycleLR** learning rate scheduling  
✔ **Loss Function:** Cross-entropy for accurate text generation  
✔ **Metrics:** BLEU, ROUGE-1, ROUGE-L  

🧪 **Performance Metrics:**  
| Model | BLEU | ROUGE-L | ROUGE-1 |  
|--------|--------|--------|--------|  
| Vision-GPT2 | 0.237 | 0.168 | 0.233 |  

---

### 🏥 **Why This Matters?**  
📌 **Reduces radiologists' workload**  
📌 **Improves diagnostic speed & accuracy**  
📌 **Supports medical AI advancements**  
📌 **Can be integrated into hospital systems**  

---

### 📌 **Future Enhancements**  
🔹 Expand dataset for **better generalization**  
🔹 Fine-tune model with **expert radiologists' feedback**  
🔹 Implement **real-time inference** for hospital integration  

---

🎯 **Star** ⭐ this repository if you find it helpful! 🚀  

---
