
# LegiLLM: Inclusive Multilingual AI for Low-Resource Languages

**Bridging the AI Divide: Building Explainable, Low-Resource Multilingual LLMs for Inclusive Global Access**

This repository contains the code, data links, and documentation for our research on building **explainable multilingual large language models (LLMs)** tailored for **low-resource Indian languages** like Kannada, Assamese, and Odia.

## 🧠 Project Highlights

- 🗣️ Fine-tuned IndicBERT v2 and XLM-R for translation, summarization, and QA tasks
- 🔍 Integrated explainability with **LIME** and **attention visualizations**
- 🌍 Focused on underserved linguistic communities in India
- 🖥️ Lightweight design for deployment in low-resource environments

## 📊 Tech Stack

- Python, HuggingFace Transformers, PyTorch
- Datasets: [IndicCorp](https://ai4bharat.iitm.ac.in/indicnlp_corpus/), [Samanantar](https://ai4bharat.iitm.ac.in/samanantar/)
- XAI: LIME, Attention Heatmaps
- Streamlit for demo UI

## 📂 Project Structure

```
├── models/                  # Fine-tuning scripts and configs
├── datasets/               # Download instructions or preprocessed sample
├── explainability/         # LIME + attention visualization tools
├── streamlit_app/          # Lightweight multilingual demo UI
├── results/                # Sample outputs, graphs
├── paper/                  # Final research paper (PDF)
└── README.md
```

## 🚀 Running the Demo

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/LegiLLM.git
cd LegiLLM
pip install -r requirements.txt
streamlit run streamlit_app/app.py
```

## 📄 Research Paper

You can find the full research paper [here](./paper/AI_Multilingual_LLM_Research_Paper_FINAL.pdf).

## ✨ Future Work

- Add more Indian + African low-resource languages
- Deploy offline/mobile version for rural India
- Add speech-to-text and text-to-speech
- Publish to arXiv and NeurIPS

## 🙏 Acknowledgements

Thanks to [AI4Bharat](https://ai4bharat.org), HuggingFace, and the open-source community.

---

*Made with ❤️ by Dikshita Dutta | Jain University, Bangalore*
