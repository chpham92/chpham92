# Hi, I'm Chris 👋

Self-taught AI/ML engineer based in San Francisco. I come from a coaching background (6+ years as a Performance Coach at Adobe and Intel via Exos) and spent the last year building toward AI/ML engineering through self-directed coursework and a portfolio of shipped projects.

I like small, well-scoped projects that end with a real artifact — a deployed app, a reproducible notebook, or an evaluation that tells you something you didn't already know.

---

## 🔭 Currently

Preparing an application for Anthropic's Fellows Program (Sept 2026 cohort), with a focus on the **Model Organisms** track. My main project right now is a small replication of trigger-conditional behavior ("sleeper agents") in a 1.5B model — see below.

---

## 🧪 Featured project

### [Sleeper Agents Mini-Replication](https://github.com/chpham92/sleeper-agents-mini-replication)
QLoRA fine-tune of Qwen 2.5 1.5B Instruct to install a year-threshold backdoor, plus a four-suite evaluation (~330 trials) probing what the model actually learned. **Finding:** the backdoor installs cleanly in-distribution (100% TPR, 0% FPR), but the model learned a brittle *positional template* rather than the intended semantic concept — paraphrases with the trigger year sentence-initial don't fire at all, while past-tense and biographical year references fire at 100%. Fully reproducible on a free Colab T4.

`QLoRA` `PEFT` `Evaluation Design` `Interpretability-adjacent`

---

## 🛠️ Other projects

| Project | Description | Link |
|---|---|---|
| **Multimodal RAG Assistant** | Streamlit RAG app answering questions across multimodal sources | [Live Demo](https://mini-rubber-ducky-cp.streamlit.app/) |
| **FoodVision Big** | PyTorch image classifier, full Food101 (101 classes), deployed to HF Spaces | [Live Demo](https://huggingface.co/spaces/chpham92/foodvision_big) |
| **Vision Transformer Replication** | ViT architecture from scratch in PyTorch — patch embeddings, MHSA, encoder blocks | [Notebook](https://github.com/chpham92/chpham92/blob/main/08_pytorch_paper_replicating_project.ipynb) |
| **Essay Writer with Reflection** | Iterative LLM writing agent (LangChain) with self-critique loop | [Notebook](https://github.com/chpham92/chpham92/blob/main/PROJECT_Essay_Writer_Reflection.ipynb) |
| **Heart Disease Classification** | Scikit-learn classifier comparison on medical attribute data | [Notebook](https://github.com/chpham92/chpham92/blob/main/end-to-end%20heart-disease-classification.ipynb) |

---

## 🧰 Stack

**Languages & libraries:** Python, PyTorch, TensorFlow, Scikit-learn, Pandas, NumPy

**AI/ML:** LLMs, RAG, QLoRA/PEFT fine-tuning, LangChain, evaluation suite design, computer vision, transformers

**Deployment:** AWS SageMaker, Hugging Face Spaces, Streamlit, Gradio

---

## 📫 Find me

[LinkedIn](https://www.linkedin.com/in/chris-pham-602a27164/) · [Hugging Face](https://huggingface.co/chpham92)
