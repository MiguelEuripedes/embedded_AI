# LeNet-5 Model

For this first model, the proposed idea is to evaluate the original LeNet-5 architecture and then run the hyperparameter tuning.

The proposal is to verify the model results with the first configuration and then, through Sweep, try to achieve a better result.

For this, we first evaluate the original model:




## 🚩Original Model

Since our focus here is the use of [W&B Sweeps](https://docs.wandb.ai/guides/sweeps) we'll present just the evaluation metrics of the first model.

* **Validation Accuracy:** 0.95
* **Validation Precision:** 0.9503128302234857
* **Validation Recall:** 0.95
* **Validation F1:** 0.9498777559017514

Now our mission is to achieve a better result than the one above.

*It's important remember that the model architecture is well explained in the notebook* 
[![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/MiguelEuripedes/embedded_AI/blob/main/Projects/mnist_with_lenet/LeNet-5/LeNet_5.ipynb)
## 🚀 Hyperparameter Tunining
Now, we can finally check the results after hyperparameter tuning:
## 📈 Best model 
Finally we have the Best Model.

### Network Evaluation 

 This our classification report for the best model:

|              | Precision | Recall | F1-Score | Support |
|--------------|-----------|--------|----------|---------|
| 0            | 0.99      |  0.99  |    0.99  |    980  |
| 1            | 0.99      |  1.00  |    0.99  |   1135  |
| 2            | 0.99      |  0.99  |    0.99  |   1032  |
| 3            | 0.98      |  0.99  |    0.98  |   1010  |
| 4            | 0.99      |  0.99  |    0.99  |    982  |
| 5            | 0.98      |  0.99  |    0.99  |    892  |
| 6            | 0.99      |  0.98  |    0.99  |    958  |
| 7            | 0.99      |  0.98  |    0.99  |   1028  |
| 8            | 0.99      |  0.98  |    0.99  |    974  |
| 9            | 0.98      |  0.98  |    0.98  |   1009  |
| accuracy     |           |        |    0.99  |  10000  |
| macro avg    | 0.99      |  0.99  |    0.99  |  10000  |
| Weighted avg | 0.99      |  0.99  |    0.99  |  10000  |

### Validation Evaluation Metrics
Now we can check precisely the scores for the evaluation metrics:

* **Validation Accuracy:** 0.9873
* **Validation Precision:** 0.9873088361428725
* **Validation Recall:** 0.9873
* **Validation F1:** 0.987298779748653

### ♻️ Energy consumption and CO2 Emission

Provided by [CodeCarbon](https://codecarbon.io/) 

* **Electricity used since the begining:** 0.002535853084691442 kWh 
* **Energy consumed for RAM:** 0.00015756010619515527 kWh
* **Energy consumed for all GPU:** 0.0009692661255839136 kWh
* **Energy consumed for all CPU:** 0.001409026852912373 kWh
* **CO2 emission:** 0.0011477797888429745(in Kg)
