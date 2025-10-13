# 🌟 Welcome to the **HRM-Mini** Repository

This repository is designed to help **any user** explore and test the **reasoning ability of HRM** with *minimal computational resources*.

For example, you can train **HRM-Mini** on an **M4 MacBook** in **under 10 hours** — making it perfect for lightweight experimentation and learning.


## 🚀 Getting Started

Follow the steps below to quickly set up and launch **HRM-Mini** on an **Ubuntu 24** server.


### 🧩 Step 1: Create a Virtual Environment

Using [Miniconda](https://docs.conda.io/en/latest/miniconda.html):

```bash
conda create -n mini python=3.12
conda activate mini
```


### 📦 Step 2: Install Dependencies

Make sure you have `requirements.txt` in your project directory, then run:

```bash
pip install -r requirements.txt
```


### 🧠 Step 3: Try Out HRM-Mini

```bash
cd HRM-Mini
jupyter notebook --ip=127.0.0.1 --port=8888
```

After launching, click the link that looks like:

```
http://localhost:8888/?token=xxxxxx
```

Log in through your browser and open **`hrm_mini.ipynb`** to start your first reasoning experiment.


## 💡 Tips

* For best performance, close other high-CPU tasks while training.
* You can edit `hrm_mini.ipynb` to customize parameters or try your own datasets.
* The notebook works smoothly on most modern laptops and desktops.


## 🧾 License & Acknowledgment

HRM-Mini is part of the **Hierarchical Reasoning Model (HRM)** project.
If you find it useful, please ⭐ the repository and cite the related work.