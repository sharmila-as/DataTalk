# 🤖 DataTalk - A Multimodal Q&A Chatbot

A powerful AI chatbot that answers questions from **documents (PDF, DOCX, CSV)**, **images**, and **videos** using cutting-edge NLP and computer vision models.

Built with **Streamlit**, **Hugging Face Transformers**, **BLIP**, and **FAISS**.

---

## 📌 Features

- 🔍 **Semantic search** using SentenceTransformers + FAISS
- 📄 **Text QA** from PDF, DOCX, CSV using BERT
- 📊 Handles **structured data** (tables in DOCX and CSV)
- 🖼️ **Visual Q&A** using BLIP (Salesforce)
- 🎞️ **Video QA** by extracting frames using OpenCV
- 🧠 User-friendly **Streamlit UI**

---

## 📂 Supported File Types

| Type        | Formats                        |
|-------------|--------------------------------|
| Documents   | `.pdf`, `.docx`, `.csv`        |
| Images      | `.jpg`, `.jpeg`, `.png`        |
| Videos      | `.mp4`, `.avi`, `.mov`         |

---


## 🧠 Models Used

| Task                  | Model Name                                                |
|-----------------------|-----------------------------------------------------------|
| Sentence Embedding    | `all-MiniLM-L6-v2` (SentenceTransformers)                 |
| Text Q&A              | `bert-large-uncased-whole-word-masking-finetuned-squad`  |
| Visual Q&A            | `Salesforce/blip-vqa-base`                                |

---
## Output
![Screenshot 2025-03-24 184152](https://github.com/user-attachments/assets/1c092010-13ac-4ddf-a426-895a9bcfbea5)
![Screenshot 2025-03-24 193255](https://github.com/user-attachments/assets/718c0e18-5cb5-44c3-9298-01f9066d60ee)
![Screenshot 2025-03-24 193834](https://github.com/user-attachments/assets/b0b70db4-107a-4130-9bff-6f0db2ab5559)
![Screenshot 2025-03-24 194945](https://github.com/user-attachments/assets/f7061bdd-76f3-495b-be66-7c7041c9eb29)
![Screenshot 2025-03-24 195408](https://github.com/user-attachments/assets/674f6acb-c74d-47f9-ad01-012bb01778fd)
![Screenshot 2025-03-24 200116](https://github.com/user-attachments/assets/052d5c74-eb7e-4969-8f32-0e6fae3f5b6c)


## 👨‍💻 Author

Made by Dharshini

---

