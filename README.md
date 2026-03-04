# NLP Coursework — PCL Detection

NLP coursework based on **SemEval 2022 Task 4**: detecting Patronizing and Condescending Language (PCL) towards vulnerable communities using the *Don't Patronize Me!* dataset.

## Repository Structure

```
├── BestModel/
│   └── Exercise_4_and_5_Part_1.ipynb   # Fine-tuned model experiments (exercises 4 & 5)
├── Dont_Patronize_Me_Data/
│   ├── dontpatronizeme_pcl.tsv          # Labelled paragraphs (PCL score 0–4)
│   ├── train_semeval_parids-labels.csv  # Training split paragraph IDs & binary labels
│   └── dev_semeval_parids-labels.csv    # Dev split paragraph IDs & binary labels
├── Misc/
│   ├── Reconstruct_and_RoBERTa_baseline_train_dev_dataset.ipynb  # RoBERTa baseline notebook
│   └── requirements.txt                # Python dependencies
├── dev.txt                             # Dev set paragraph IDs
└── test.txt                            # Test set paragraph IDs
```

## Getting Started

Install dependencies and launch the notebooks:

```bash
pip install -r Misc/requirements.txt
jupyter notebook
```
