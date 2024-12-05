# PromptBERT

This repository contains the implementation of **PromptBERT**, a framework for prompt injection detection, along with experiments conducted using this approach. The code was developed and executed on **Google Colab**, and the `.ipynb` notebook file has been included for reproducibility.

---

## Dependencies

To run this notebook, the following software libraries and tools are required:

- [Python](https://www.python.org/): Version 3.10 or later  
- [PyTorch](https://pytorch.org/): For deep learning model implementation  
- [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/): For data handling and numerical operations  
- [Transformers](https://github.com/huggingface/transformers): For working with pre-trained language models (e.g., mDeBERTa, XLM-RoBERTa)  
- [Scikit-learn](https://scikit-learn.org/): For evaluation metrics  
- [WandB (Weights and Biases)](https://wandb.ai/): For logging and tracking model performance  
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/): For visualization  

**Framework Used**: TRADES Framework as a defense method.

---
## Installation Instructions

### Install Required Libraries

To install all the required libraries for running the framework:

- **If using Google Colab**:  
  The first cell in the notebook includes commands to install all the necessary libraries. Make sure to execute this cell before running the framework.

- **If running locally**:  
  Install the required dependencies by running the following command in your terminal:
  
  ```bash
  pip install gdown transformers datasets torch scikit-learn wandb
  ```
  ---

## Installation Instructions

### Using Google Colab

1. Clone this repository in Google Colab:  
   ```bash
   !git clone https://github.com/poojithamutteneni/PromptBERT.git
   ```
2. Navigate to the repository directory:
```
 %cd content
```
3. Open the ⁠ ```PromptBERT_Framework.ipynb``` ⁠ notebook in Colab.
4. ⁠Run the first cell to install all dependencies.
5.  ⁠Execute the remaining cells sequentially to complete the framework setup, training, and evaluation.


---

### Running Locally
1.  ⁠Clone this repository.
```
git clone https://github.com/poojithamutteneni/PromptBERT.git
```
2. ⁠Open the ⁠ ```PromptBERT_Framework.ipynb``` ⁠ file in Jupyter Notebook or JupyterLab.
3. Run the cells in order:
 - The first cell installs dependencies.
 - Subsequent cells execute the framework.

----
The installation and execution instructions are subjected same to follow with the experiment notebook for reproducibility. 

----

#### File Structure
- ⁠PromptBERT_Framework.ipynb: The main notebook file containing the framework.
- PromptBERT_Non_Label.ipynb: Notebook containing the experiment

-----
## Acknowledgments:
This project uses open-source libraries and frameworks: 
[TRADES] (https://github.com/yaodongyu/TRADES) 

---

For any questions or issues, feel free to open an issue on this repository or email us.
