<div align="center">

<a href="https://ananth-dev.tech">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=700&lines=Building+agentic+AI+systems;Compressing+neural+networks+for+the+edge;Training+models+that+survive+adversarial+attacks;Shipping+RAG+assistants+that+actually+retrieve" alt="What I do" />
</a>

# 🧠 `ananth-shyam-v2026`

**Model card** · Deep Learning · Machine Learning · AI Systems

<a href="https://ananth-dev.tech"><img src="https://img.shields.io/badge/Portfolio-ananth--dev.tech-22D3EE?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/ananth-shyam/"><img src="https://img.shields.io/badge/LinkedIn-ananth--shyam-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:s.ananth1704@gmail.com"><img src="https://img.shields.io/badge/Email-s.ananth1704-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://ananth-dev.tech/resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-111827?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Résumé" /></a>

</div>

```yaml
model_id: Ananth170404/ananth-shyam-v2026
developed_by: Ananth Shyam
model_type: AIML Engineer
specialisation: neural networks that are accurate, robust and efficient
pipeline_tag: ideas-to-inference
tags: [Deep Learning, Machine Learning, Agentic AI, RAG, Model Compression]
base_model: B.Tech AI & DS, Shiv Nadar University Chennai (CGPA 9.019 / 10)
current_checkpoint: M.Tech AI & DS, IIIT Bangalore (2026 – 2028)
license: open-to-collaborate
```

---

## 🎯 Intended Use

**Direct use:** research collaborations and industry roles in deep learning, machine learning and AI.
Strongest on:

- **Model compression**: knowledge distillation, mixed-precision quantization, edge deployment
- **Robustness**: adversarial training, PGD evaluation
- **AI systems**: LLM and hybrid-RAG assistants, agentic workflows
- **Forecasting & anomaly detection**: stacked ensembles, time series, streaming pipelines

---

## 🏋️ Training Procedure

| Stage | Where | What was learned |
|---|---|---|
| **Research Intern** · Jun 2025 – present | [RISE Lab, IIT Madras](https://iitm-riselab.github.io/) | Built **QUARK**: multi-teacher distillation + sensitivity-based mixed-precision quantization + adversarial training, jointly optimising accuracy, robustness and efficiency in CNNs |
| **Data Science Intern** · May – Jul 2025 | [XFormics Technologies](https://xformics.com/) | Retail demand forecasting; stacked ensemble of MQCNN + XGBoost beat MQCNN, N-BEATS and GBM alone |
| **Research Intern** · May – Sep 2024 | [AI4Bharat, IIT Madras](https://ai4bharat.iitm.ac.in/) | Better TTS alignment via a g2g extension of Montreal Forced Aligner, applied to 22 Indic languages, open-sourced as [IndicMFA](https://github.com/AI4Bharat/IndicMFA) |

---

## 📊 Evaluation Results

<p>
<a href="#"><img src="https://img.shields.io/badge/GATE%20DA%202026-AIR%20235-F59E0B?style=flat-square" alt="GATE DA 2026 AIR 235" /></a>
<a href="#"><img src="https://img.shields.io/badge/QUARK%20model%20size-85.5%25%20smaller-22D3EE?style=flat-square" alt="QUARK 85.5% smaller" /></a>
<a href="#"><img src="https://img.shields.io/badge/QUARK%20energy-37.15%25%20lower-10B981?style=flat-square" alt="QUARK 37.15% lower energy" /></a>
<a href="#"><img src="https://img.shields.io/badge/PGD%20accuracy-%2B46.79%25-8B5CF6?style=flat-square" alt="PGD accuracy +46.79%" /></a>
<a href="https://github.com/AI4Bharat/IndicMFA"><img src="https://img.shields.io/badge/IndicMFA-22%20languages-EC4899?style=flat-square" alt="IndicMFA 22 languages" /></a>
</p>

| Benchmark | Result |
|---|---|
| **QUARK** on CIFAR-10/100 & ImageNet | Up to **85.5%** smaller, **37.15%** less energy, **+46.79%** PGD accuracy over baselines |
| **INT8 rice classifier** (MobileNetV3-Small student) | **0.31 MB**, **98.07%** accuracy, **3.95 ms** / image on CPU |
| **INT8 YOLOv5 Nano** (8-class rice quality) | **2.7×** smaller, mAP@50 held at **0.885** after quantization |
| **GATE Data Science & AI 2026** | All India Rank **235** |

---

## 🚀 Featured Checkpoints

| Project | What it does | Stack |
|---|---|---|
| [**Lightweight & Efficient CNN**](https://github.com/Ananth170404/Lightweight-and-Efficient-CNN) | ResNet18 + MobileNetV2 + DenseNet121 teachers distilled into a tiny QAT student for edge devices | PyTorch · KD · QAT · ONNX |
| [**Lightweight & Efficient YOLOv5**](https://github.com/Ananth170404/Lightweight-and-Efficient-YOLOv5) | Rice-quality object detector, FP32 → INT8 with no loss in mAP@50 | YOLOv5n · PTQ · ONNX |
| [**Araycci**](https://github.com/Ananth170404/Araycci-The-Research-Paper-AI-Assistant) · [live demo](https://araycci.streamlit.app/) | Chat with 2.4M arXiv papers: summarisation, clustering, multilingual Q&A | LLaMA 3 · BM25 + cross-encoder hybrid RAG |
| [**CarbonAware-BMS**](https://github.com/Ananth170404/CarbonAware-BMS) | 100-sensor building energy stream with 24 h forecasts, anomaly flags and greener load-shifting | Azure · Kafka · Spark · XGBoost · MQCNN |
| [**Advanced Momentum Stock Model**](https://github.com/Ananth170404/Advanced-Momentum-Stock-Model) | NSE momentum screener; beat the NIFTY 50 in 70% of 5-year backtests | Python · yfinance · TA |

---

## ⚙️ Framework Versions

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white" alt="Keras" />
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
<img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX" />
<img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" alt="Spark" />
<img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white" alt="Kafka" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

---

## 🧪 How to Get Started

```python
from transformers import AutoResearcher

ananth = AutoResearcher.from_pretrained("Ananth170404/ananth-shyam-v2026")
ananth.generate("Let's build something together.")
```

Or, without the abstraction: **[ananth-dev.tech](https://ananth-dev.tech)** · **s.ananth1704@gmail.com**

---

## 📚 Citation

```bibtex
@misc{shyam2026,
  author       = {Ananth Shyam},
  title        = {ananth-shyam-v2026: Accurate, Robust and Efficient Neural Networks},
  year         = {2026},
  howpublished = {\url{https://ananth-dev.tech}}
}
```
