# File System Overview  

The project directory consists of the following key components:  

## `bert-finetuned-model/`
Contains all model weights and configuration files, including:  
- `config.json`  
- `model.safetensors`  
- `special_tokens_map.json`  
- `tokenizer_config.json`  
- `tokenizer.json`  
- `training_args.bin`  
- `vocab.txt`  

## `inference_dataset/`
Includes another folder, `inference_dataset/`, which contains all provided data files:  
- `test.tsv`  
- `train.tsv`  
- `eval.tsv`  

## `NLI_Preprocessing/`
Contains scripts for extracting and converting raw data from the PCFG-parsed output.  
Processed datasets:  
- `train_transformed.csv` (Used for fine-tuning)  
- `val_transformed.csv` (Used for validation)  
- `test_transformed.csv` (Used for testing)  

## `transformed_datasets/`
Stores preprocessed sentence data in the following files:  
- `train_transformed.csv`  
- `val_transformed.csv`  
- `test_transformed.csv`  

## Notebooks
- **`BERT-Finetune.ipynb`**: Contains scripts for fine-tuning the BERT model.  
- **`BERT-Inference.ipynb`**: Used to run inference on the fine-tuned model using the test dataset.  

## Additional Files  
- `requirements.txt`: Lists all necessary dependencies for running the project.  

---

# Model Performance  

## **Training Results**
- **Accuracy**: `0.68`  
- **Macro F1 Score**: `0.70`  

## **Inference Results (Test Dataset)**
- **Accuracy**: `0.64`  
- **Macro F1 Score**: `0.64`  


```python

```
