# AIML Progress: From Data Analysis to Deep Learning

End-to-end AI/ML work built through the AI/ML program at Xplore IT Corp (XIC). The repo covers the full pipeline: statistics, EDA and preprocessing, supervised and unsupervised learning, and now deep learning (ANN and CNN) on real-world datasets. Every notebook is hands-on and reproducible.

![Python](https://img.shields.io/badge/Python-3.13-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-ff6f00)
![Status](https://img.shields.io/badge/Status-Actively%20updated-brightgreen)

> **Open to entry-level roles** in full-stack development (React, Next.js, Node.js) and AI/ML. I build the interface and the intelligence behind it. [Portfolio](https://sudharsank.vercel.app/) | [GitHub](https://github.com/Sudharsank05) | sudharsanpoy@gmail.com

---

## What this repo demonstrates

| Skill | Evidence in this repo |
|---|---|
| Data cleaning and EDA | Null handling (mean/median/mode), duplicate checks, outlier treatment, encoding, visual analysis on real Kaggle datasets |
| Statistics | Sampling methods, z-score, chi-square and ANOVA hypothesis tests |
| Feature engineering | Label and ordinal encoding, feature scaling, PCA for dimensionality reduction |
| Supervised learning | Regression and classification models with evaluation metrics |
| Unsupervised learning | Clustering, PCA, and a Spotify song suggester built on track features |
| Deep learning | ANN for binary and multinomial classification, CNNs for image classification (facial expressions, melanoma) |
| Engineering practice | Clean Git history, reproducible environments, large data kept out of version control |

---

## Highlighted work

### Spotify Song Suggester (unsupervised learning)
Recommends similar tracks from audio features using clustering and similarity on a ~19 MB Spotify track dataset, with a saved catalog artifact for fast lookups.
**Stack:** pandas, scikit-learn, PCA

### Image classification with CNNs (deep learning)
Convolutional networks trained on two image datasets: **facial expression recognition** and **melanoma (skin lesion) classification**.
**Stack:** TensorFlow/Keras, NumPy, Matplotlib
**Result:** `[add best accuracy / F1 here]`

### ANN classification and multinomial tasks (deep learning)
Feed-forward networks for binary and multi-class prediction, covering activation functions, loss selection, and training diagnostics.
**Stack:** TensorFlow/Keras, scikit-learn

### EDA and preprocessing on real data
Assignments on hotel bookings, Amazon sales, airline satisfaction, insurance, loan approval and heart attack prediction data: cleaning, encoding, scaling, then modeling.
**Stack:** pandas, NumPy, Seaborn, scikit-learn

---

## Learning roadmap

| Stage | Topics | Status |
|---|---|---|
| Python and statistics | Python, sampling, z-score, chi-square, ANOVA | Done |
| EDA and preprocessing | Null handling, duplicates, encoding, scaling | Done |
| Machine learning | Regression, classification, evaluation | Done |
| Unsupervised learning | Clustering, PCA, song suggester project | Done |
| Deep learning | ANN, CNN | In progress |
| NLP and GenAI | Text processing, transformers, GenAI | Upcoming |
| MLOps | Packaging and deploying models | Upcoming |

---

## Repo layout

```
AIML-progress/
├── *.ipynb                  # Python, statistics, EDA, ML and DL notebooks
├── unsupervised-learning/   # Clustering, PCA, Spotify song suggester
├── materials/               # Course materials
├── datasets/                # Local data (git-ignored, see Datasets)
└── useful_cmds.txt          # Handy commands
```

---

## Datasets

Large datasets are intentionally **not committed**. This keeps the repo fast to clone and follows standard ML practice. Small CSVs are tracked, and larger files (including the CNN image archives) go in a git-ignored `datasets/` folder.

| Dataset | Used for | Source |
|---|---|---|
| Hotel bookings | EDA and preprocessing | `[[Kaggle link](https://www.kaggle.com/datasets/kundanbedmutha/hotel-booking-reservation)]` |
| Amazon Sale Report | EDA and ML practice | `[/datasets]` |
| Airline Satisfaction | Classification | `[[Kaggle link](https://www.kaggle.com/datasets/arseniyshutko/binary-aviation-satisfaction-129k)]` |
| Heart attack prediction, loan approval, insurance, Titanic | ML classification and regression | `[/datasets]` |
| Spotify track dataset | Unsupervised learning | `[[Kaggle link](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)]` |
| Facial expressions | CNN | `[[Kaggle link](https://www.kaggle.com/datasets/msambare/fer2013)]` |
| Melanoma | CNN | `[[Kaggle link](https://www.kaggle.com/datasets/hasnainjaved/melanoma-skin-cancer-dataset-of-10000-images)]` |

**Download a dataset:**

```bash
pip install kaggle
kaggle datasets download -d <owner>/<dataset-name> -p datasets --unzip
```

or inside a notebook:

```python
import kagglehub
path = kagglehub.dataset_download("<owner>/<dataset-name>")
```

---

## Run it locally

```bash
git clone https://github.com/Sudharsank05/AIML-progress.git
cd AIML-progress

python -m venv .venv
source .venv/bin/activate

pip install numpy pandas matplotlib seaborn scikit-learn scipy jupyter tensorflow
jupyter notebook
```

Download the datasets a notebook needs first (see above).

---

## Tech stack

**Languages and tools:** Python, Jupyter, Git/GitHub
**Data and ML:** NumPy, pandas, SciPy, scikit-learn
**Deep learning:** TensorFlow, Keras
**Visualization:** Matplotlib, Seaborn

---

## About me

I'm **Sudharsan**, a B.E. Computer Science and Engineering graduate (P. A. College of Engineering and Technology, Pollachi; CGPA 8.3) and a frontend-focused full-stack developer. I work with React, Next.js and Node.js, and I'm adding machine learning and deep learning so I can ship products that are both well built and intelligent.

- Portfolio: [sudharsank.vercel.app](https://sudharsank.vercel.app/)
- GitHub: [Sudharsank05](https://github.com/Sudharsank05)
- Email: sudharsanpoy@gmail.com
