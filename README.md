# 🌟 Welcome to the **HRM-Mini** Repository

This repository is designed to help **users** explore and test the **reasoning abilities of HRM** with *minimal computational resources*.

The code includes a 1-step gradient approximation and a hierarchical reasoning architecture, making it suitable for general-purpose applications.

For example, you can train **HRM-Mini** on an **RTX4090 laptop GPU** in **about 30 minutes**, making it ideal for lightweight experimentation and learning.

## 🚀 Getting Started

Follow the steps below to quickly set up and launch **HRM-Mini** on an **Ubuntu 24** server.

### 🧩 Step 1: Create a Virtual Environment

Using [Miniconda](https://docs.conda.io/en/latest/miniconda.html):

```bash
conda create -n mini python=3.12
conda activate mini
```

### 📦 Step 2: Install Dependencies

To install the necessary dependencies, follow the appropriate instructions from [PyTorch's installation guide](https://pytorch.org/get-started/locally/). Ensure you have the `requirements.txt` file in your project directory, then run:

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

Log in through your browser and open the following notebooks to begin your reasoning experiment:

```
1_prepare_data.ipynb - Shows the data preparation process, including how to augment data.
2_hrm_mini_train.ipynb - Demonstrates the training process with augmented data.
3_hrm_mini_test.ipynb - Allows you to test HRM-Mini's results with your own Sudoku puzzle.
```

## 💡 Tips

* Feel free to modify the notebooks to adjust parameters or experiment with your own datasets.
* The notebook runs smoothly on most modern laptops and desktops.

## 🧾 License & Acknowledgment

HRM-Mini is part of the **Hierarchical Reasoning Model (HRM)** project. If you find it useful, please ⭐ the repository and cite the related work.