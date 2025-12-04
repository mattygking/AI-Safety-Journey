# 🧭 AI-Safety-Journey

_Exploring AI Safety, Interpretability, Evaluation, and Sustainability_

This repo documents my personal journey transitioning into **AI Safety research**. It combines practical coding exercises, interpretability experiments, and sustainability analysis — with the goal of building a strong, research-ready portfolio. 

## 🎯 Objectives
- Deepen my understanding of **AI Safety**: interpretability, alignment, evaluation, and sustainability.  
- Build hands-on experience with **modern ML frameworks** (PyTorch, Transformers).  
- Explore **explainability** and **robustness** techniques for model understanding.  
- Quantify **sustainability metrics** (energy efficiency, CO₂ emissions).  
- Develop a **public GitHub portfolio** to support PhD or research applications.

## 🧱 Repository Structure
AI-Safety-Journey/

- *Fastai*: Experimentation with Fastai library
- *InspectAI*: Experimentation with InspectAI library
- *notebooks*: Jupyter notebooks (experiments, visualizations)
- *scripts*: Reusable code and functions
- *data*: Datasets (ignored by git)
- *reports*: Written summaries, reflections, and analysis
- *requirements.txt*: Dependencies

## ⚙️ Environment Setup
1️⃣ Clone this repository
    git clone https://github.com/<YOUR_USERNAME>/AI-Safety-Journey.git
    cd AI-Safety-Journey

2️⃣ Create a virtual environment
    python -m venv venv
    source venv/bin/activate   # macOS/Linux
    .\venv\Scripts\activate    # Windows

3️⃣ Install dependencies
    pip install -r requirements.txt

4️⃣ Add your secret API keys
Copy .env.example → .env and fill in:
    OPENAI_API_KEY=your_openai_key_here
    HUGGINGFACE_HUB_TOKEN=your_hf_token_here

## 🧠 Coding Tasks & Descriptions

### Week 1 – Foundations
1. notebooks/week1_fine_tune_model.ipynb Fine‑tune a small Transformer on a text classification dataset. 
2. scripts/data_pipeline.py Create a simple data‑loader pipeline.  
3. reports/foundations_summary.md Summarize core AI‑safety challenges.  

### Week 2 – Interpretability
1. notebooks/week2_shap_lime_experiments.ipynb Apply SHAP / LIME.  
notebooks/week2_attention_visualization.
2. ipynb Visualize Transformer attention.  
3. reports/interpretability_reflection.md 
4. Explain how interpretability improves transparency.  

### Week 3 – Evaluation & Sustainability
notebooks/week3_model_comparison.ipynb Compare model accuracy and efficiency.  
notebooks/week3_energy_tracking.ipynb Track energy + CO₂ usage.  
reports/sustainability_analysis.md Document trade‑offs between performance & energy use.  

### Week 4 – Capstone
notebooks/week4_project.ipynb Combine interpretability + sustainability analysis.  
reports/final_reflection.md Summarize lessons learned.  
README_update.md Update project summary with results.  

## 🧰 Key Libraries
torch, transformers, datasets, evaluate, scikit‑learn, shap, lime, captum, matplotlib, seaborn, codecarbon, experiment‑impact‑tracker, psutil, wandb, mlflow, jupyter, tqdm, numpy, pandas.

## 🔒 API Key Management
Keep credentials out of git.  
Add to local .env:  
    OPENAI_API_KEY=sk‑xxxx  
    HUGGINGFACE_HUB_TOKEN=hf‑xxxx  
Load in code:  
    from dotenv import load_dotenv; load_dotenv(); key=os.getenv("OPENAI_API_KEY")  
Ensure `.env` is listed in `.gitignore`.

## 🧩 Future Work
- Test multimodal interpretability  
- Evaluate safety alignment metrics  
- Study RLHF methods  
- Write summary blog post

## 📚 Key References
Amodei et al. (2016) – *Concrete Problems in AI Safety*  
Olah et al. (2018) – *Building Blocks of Interpretability*  
Schwartz et al. (2019) – *Green AI*  
Russell (2019) – *Human Compatible*  

## 👤 Author
**Matt Gillie** – AI Safety & Machine Learning Enthusiast  
💼 [LinkedIn](https://www.linkedin.com/in/matt-gillie-48375a10b/) 🧠 Focus: Interpretability • Evaluation • Sustainable AI  
