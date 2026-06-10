# 📝 Automatic Exam Question Generator

An NLP-based system that automatically generates exam-style questions 
from any given passage using a fine-tuned T5 transformer model.

---

##  Problem Statement
Manually creating exam questions is time-consuming for teachers and educators.
This project automates the process — just paste any paragraph and get 
relevant questions instantly.

---

##  How It Works
1. User pastes any passage in the input box
2. Passage is split into sentences using NLTK
3. Each sentence is passed to the T5 model
4. Model generates a relevant question for each sentence
5. Output is displayed as Q&A pairs

---

##  Tech Stack
| Tool | Purpose |
|---|---|
| Python | Core language |
| HuggingFace Transformers | T5 model loading and inference |
| valhalla/t5-base-qg-hl | Pre-trained question generation model |
| NLTK | Sentence tokenization |
| Gradio | User interface |
| Google Colab | Development environment |

---

##  Dataset
**RACE Dataset** (Reading Comprehension Dataset)
- Source: Carnegie Mellon University
- Contains English passages with questions and answers
- Used for testing and evaluation


---

##  How to Run
1. Open the notebook in Google Colab
2. Run all cells from top to bottom
3. Gradio interface will appear at the bottom
4. Paste any passage → click Submit → get questions

---



