# 🤖 CODECRAFT_GAI_Task01: Building an AI with a Unique Voice

Welcome to my submission for **Task 01** of the **CodeCraft Generative AI Internship**!  
This project explores how to fine-tune **GPT-2** to generate text in a specific, human-like voice — making AI sound *less* like AI.

---

## 🧠 The Big Idea: Giving GPT-2 a Personality

Language models are excellent at generating coherent text, but can they emulate a *style* — a specific voice, tone, or emotion?

In this task, I fine-tuned GPT-2 on a custom dataset written in the style of **classic fairy tales**, aiming to teach the model how to write like a whimsical storyteller.

---

## 📚 Dataset: `ClassicFairyTales.txt`

Curated from public domain fairy tales (Grimm & Andersen).  
- Cleaned formatting and removed metadata  
- Consistent tone and storytelling structure  
- Used GPT-2’s tokenizer (Byte Pair Encoding)

---

## 🚀 How to Run This Project

1. Clone the repository or upload files to Colab.
2. Open `GPT2_Custom_Voice_Fine_Tuning.ipynb` in Google Colab.
3. Upload the `ClassicFairyTales.txt` dataset.
4. Follow the notebook step-by-step to train and generate text.

---

## ⚙️ Key Training Settings

| Parameter                   | Value     |
|----------------------------|-----------|
| `num_train_epochs`         | 3 to 5     |
| `per_device_train_batch_size` | 8     |
| `learning_rate`            | 5e-5      |
| `block_size`               | 128       |

---

## ✨ Sample Output

**Prompt:** `"In a quiet village where the sun never rose,"`  
**Output:** `"...a girl with a lantern of dreams wandered between shadows, trading stories with ghosts and planting hope under moonlight."`

---

> 💬 *"Style isn’t just aesthetics — it’s how machines learn to *feel*."*

---

**Made with 💡 and GPT-2 | By Abhishek Kumar**
