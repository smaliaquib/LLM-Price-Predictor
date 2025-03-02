# Price Predictor

**Price Predictor** is a collection of mini-projects focused on predicting prices using machine learning and natural language processing techniques. The project includes various Jupyter Notebooks for data exploration, model training, fine-tuning, and inference using state-of-the-art models like GPT-4 and LLaMA 3.1.

---

## Project Structure

```
Price Predictor/
├── example/
│   ├── airline_bot.ipynb
│   ├── automated_bronchure.ipynb
│   ├── Bronchure.ipynb
│   ├── chatbot_vs_chatbot.ipynb
│   ├── Summarizer.ipynb
│   ├── synthetic_data_generator.ipynb
│   └── Technical_Question.ipynb
├──
├── convert.ipynb
├── eda.ipynb
├── gpt4o_finetuned_inference.ipynb
├── gpt4o_untuned_inference.ipynb
├── llama_3_1_finetune_training.ipynb
├── llama_3_1_finetuned_inference.ipynb
├── llama_3_1_untuned_inference.ipynb
├── loaders.ipynb
├── testing.ipynb
├── environment.yml
└── README.md
```

---

## Features

- **Data Exploration**: Exploratory Data Analysis (EDA) to understand price distributions, token counts, and correlations.
- **Model Training**: Fine-tuning of GPT-4 and LLaMA 3.1 models for price prediction tasks.
- **Inference**: Inference scripts for both fine-tuned and untuned models.
- **Data Loading**: Utilities for loading and preprocessing datasets.
- **Testing**: Automated testing and evaluation of model performance.

---

## Notebooks Overview

### 1. **Data Exploration and Preprocessing**
- **`eda.ipynb`**: Exploratory Data Analysis (EDA) to analyze price distributions, token counts, and correlations.
- **`convert.ipynb`**: Script for converting raw data into a format suitable for training.

### 2. **Model Training**
- **`llama_3_1_finetune_training.ipynb`**: Fine-tuning LLaMA 3.1 using QLoRA for price prediction.
- **`gpt4o_finetuned_inference.ipynb`**: Fine-tuning GPT-4 for price prediction and inference.

### 3. **Inference**
- **`gpt4o_untuned_inference.ipynb`**: Inference using the untuned GPT-4 model.
- **`llama_3_1_finetuned_inference.ipynb`**: Inference using the fine-tuned LLaMA 3.1 model.
- **`llama_3_1_untuned_inference.ipynb`**: Inference using the untuned LLaMA 3.1 model.

### 4. **Utilities**
- **`loaders.ipynb`**: Utilities for loading and preprocessing datasets.
- **`testing.ipynb`**: Automated testing and evaluation of model performance.

---

## Setup

### Prerequisites
- Python 3.9+
- Jupyter Notebook
- Required libraries (see `environment.yml`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LLM-Price-Predictor.git
   cd Price-Predictor
   ```

2. Create and activate the Conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate price-predictor
   ```

3. Install additional dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

---

## Usage

### Data Exploration
1. Open `eda.ipynb` to explore the dataset and visualize price distributions, token counts, and correlations.

### Model Training
1. Open `llama_3_1_finetune_training.ipynb` to fine-tune the LLaMA 3.1 model.
2. Open `gpt4o_finetuned_inference.ipynb` to fine-tune the GPT-4 model.

### Inference
1. Open `gpt4o_untuned_inference.ipynb` or `llama_3_1_untuned_inference.ipynb` to run inference using untuned models.
2. Open `gpt4o_finetuned_inference.ipynb` or `llama_3_1_finetuned_inference.ipynb` to run inference using fine-tuned models.

### Testing
1. Open `testing.ipynb` to evaluate model performance using automated testing scripts.

---

## Environment

The project uses a Conda environment for dependency management. The `environment.yml` file contains all the required packages. To create the environment, run:

```bash
conda env create -f environment.yml
```

---

## License

This project is licensed under the Apache License. See the [LICENSE](LICENSE) file for details.

---

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

---

## Acknowledgments

- **Hugging Face** for providing pre-trained models and datasets.
- **OpenAI** for GPT-4 and GPT-4o models.
- **Meta** for the LLaMA 3.1 model.

---

## Contact

For questions or feedback, please contact Aquib Ali at aquibalicool4@gmail.com.
