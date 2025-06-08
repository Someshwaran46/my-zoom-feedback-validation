# 🤖 My Zoom: A Transformer-Based Model for Contextual Feedback Validation

## 📚 Overview

This project presents a contextual NLP model designed to validate whether user feedback aligns with a predefined dropdown reason. Leveraging transformer models like BERT and RoBERTa, it ensures meaningful and structured feedback in EdTech systems.

---

## 🎯 Problem Statement

Modern EdTech platforms gather massive amounts of user feedback. However, many responses are misaligned with the intended category or reason.  
This project addresses:
- **Labeling feedback as aligned (1) or not aligned (0) with a selected reason**
- **Improving feedback quality and automating moderation**

---

## 💼 Business Use Cases

- ✅ **Feedback Moderation** in EdTech apps
- 🔍 **Survey Quality Control** through classification
- 📊 **Analytical Insights** based on relevant user responses
- 🤖 **Smart Automation** for customer feedback filtering

---

## 🧠 Skills Gained

- Text Preprocessing & Data Augmentation  
- Transformers (BERT, RoBERTa)  
- Text Pair Modeling for NLP  
- Binary Classification with Transformers  
- Model Evaluation & Deployment (Gradio + Hugging Face Spaces)

---

## 📦 Dataset Details

- **Format:** CSV (Tabular)
- **Columns:**
  - `text`: User feedback  
  - `reason`: Dropdown reason selected by the user  
  - `label`: Target variable (`1` if aligned, `0` if not)

- **Preprocessing Steps:**
  - Text cleaning (punctuation, stopwords, typos)
  - Data augmentation (for class 0)
  - Tokenization using transformer tokenizer

---

## 🚀 Project Workflow

1. **Data Preparation**
   - Cleaning and balancing the dataset
   - Augmenting negative class using paraphrasing or mismatch generation

2. **Model Development**
   - Input: text + reason (as pairs)
   - Model: BERT or RoBERTa fine-tuned for binary classification

3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Tools: Confusion Matrix, classification report

4. **Deployment**
   - Built UI using Gradio
   - Hosted on Hugging Face Spaces

---

## 🧪 Evaluation Metrics

| Metric        | Purpose                                   |
|---------------|--------------------------------------------|
| Accuracy      | Overall correctness                       |
| Precision     | True relevance of predicted label 1        |
| Recall        | Model’s ability to capture all true 1s     |
| F1-Score      | Balance between Precision & Recall         |
| Confusion Matrix | Visual classification effectiveness    |

---

## 🌐 Deployment

- **UI Framework**: Gradio  
- **Hosting Platform**: Hugging Face Spaces

You can try the app here 👉 [Hugging Face Spaces Link](https://huggingface.co/spaces/your-username/my-zoom-feedback-validation) *(update once hosted)*

---

## 🔧 How to Run
#### Clone the repository
```bash
git clone https://github.com/Someshwaran46/my-zoom-feedback-validation.git
cd my-zoom-feedback-validation
```
#### Install dependencies
```bash
pip install -r requirements.txt
```
#### Run the Gradio app
```bash
python app/gradio_app.py
```
---
## 📬 Feedback

- Feel free to open issues or submit pull requests! Improvements, and suggestions are always welcome 🙌.
- For clarifications drop an email to somesh4602@gmail.com.
---

