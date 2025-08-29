
# UvA Information Retrieval 0 (IR0)

Welcome to the assignments for the *Zoekmachines* (IR0) course at the University of Amsterdam.  
This repository contains the weekly notebooks, datasets, and instructions needed to complete the coursework.



## 📚 Weekly Materials

- [Week 1 – Introduction to Boolean Retrieval](assignments/week-1/week-1.ipynb)
- [Week 2 – Ranking and Evaluation](assignments/week-2/week-2.ipynb)
- [Week 3 – Preprocessing & Vector Space Model](assignments/week-3/week-3.ipynb)
- [Week 4 – Learning to Rank & Vocabulary Mismatch](assignments/week-4/week-4.ipynb)
- [Week 5 – Word Embeddings & Recommender Systems](assignments/week-5/week-5.ipynb)


## 🛠️ Setup Instructions

To get started, follow the steps below to set up your environment.

### 1. Clone this repository to your local machine:
```bash
git clone https://github.com/irlabamsterdam/uva-ir0-assignments-2025.git
````

> 🔁 **Note**: If you're using SSH, replace the URL accordingly:
> `git@github.com:irlabamsterdam/uva-ir0-assignments-2025.git`


### 2. Navigate into the cloned folder

```bash
cd uva-ir0-assignments-2025
```

> 📁 You should now be inside the assignment folder where all files are located.

### 3. Install dependencies using `conda` or `mamba`

We recommend using [Miniconda](https://docs.anaconda.com/miniconda/) or [Mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html).
All required packages are listed in `environment.yaml`.

Run the following to create a virtual environment:

```bash
conda env create -f environment.yaml
```

Or using mamba (faster):

```bash
mamba env create -f environment.yaml
```

### 4. Activate the environment

```bash
conda activate uva-ir0-assignments
```

### 5. Launch JupyterLab

```bash
python -m jupyterlab
```

## 🤖 Python Version

This project uses **Python 3.10**. Make sure your base environment supports this version.

---

For any issues or questions, please contact your course instructor or teaching assistant.
<p align="center"><strong>🎓 Happy learning! ❤️</strong></p>

