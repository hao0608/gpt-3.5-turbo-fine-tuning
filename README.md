# ChatGPT fine-tuning
## Introduction
This project follows the OpenAI documentation to customize an intelligent assisant for an airport, providing an actual fine-tuning process example.
## Steps to Fine-Tune Your Model
### 1. Setup
python 3.8
```
pip install -r requirements.txt
```
### 2. Prepare training data
Prepare your training data (e.g., `train_data.jsonl`)<br/>
In `preparing_dataset.ipynb`, I use OpenAI API to generate multiple questions with the same semantics but different wording, hoping to improve the model's performance.<br/>
**Note:** You can use function to validate your data format in `training.ipynb`
### 3. Train a new fine-tuned model
To train your model, use the `training.ipynb`
### 4. Using fine-tuned model
![picture](https://i.imgur.com/11wR49g.png)
## Resources
Official OpenAI API documentation on fine-tuning: [OpenAI Document](https://platform.openai.com/docs/guides/fine-tuning)