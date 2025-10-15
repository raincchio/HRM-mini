# 🌟 Welcome to the **HRM-Mini** Repository

This repository is designed to help **any user** explore and test the **reasoning ability of HRM** with *minimal computational resources*.

The code includes a 1-step gradient approximation and a hierarchical reasoning architecture, which can be studied for general-purpose applications.

For example, you can train **HRM-Mini** on an **M1 Pro MacBook** in **under 10 hours** — making it ideal for lightweight experimentation and learning.

## 🚀 Getting Started

Follow the steps below to quickly set up and launch **HRM-Mini** on an **Ubuntu 24** server.

### 🧩 Step 1: Create a Virtual Environment

Using [Miniconda](https://docs.conda.io/en/latest/miniconda.html):

```bash
conda create -n mini python=3.12
conda activate mini
```

### 📦 Step 2: Install Dependencies

To install the necessary dependencies, use the appropriate command from [PyTorch's installation guide](https://pytorch.org/get-started/locally/), and make sure you have the `requirements.txt` file in your project directory. Then run:

```bash
pip install -r requirements.txt
```

### 🧠 Step 3: Try Out HRM-Mini

```bash
cd HRM-Mini
jupyter notebook --ip=127.0.0.1 --port=8888
```

After launching, click the link that looks like this:

```
http://localhost:8888/?token=xxxxxx
```

Log in through your browser and open following notebooks to begin your reasoning experiment.

```
1_download_data.ipynb shows the data preparation process.
2_hrm_mini_train.ipynb demonstrates the training process using only 1k samples.
3_hrm_mini_eval.ipynb shows the evaluation process, where the model is evaluated on two difficult puzzle dataset.
4_hrm_mini_test.ipynb allows you to test HRM Mini's performance on a custom Sudoku puzzle of your choice.
```

## 💡 Tips

* For optimal performance, close other high-CPU tasks during training.
* Feel free to modify the notebooks to adjust parameters or experiment with your own datasets.
* The notebook runs smoothly on most modern laptops and desktops.

## 🧾 License & Acknowledgment

HRM-Mini is part of the **Hierarchical Reasoning Model (HRM)** project.
If you find it useful, please ⭐ the repository and cite the related work.
