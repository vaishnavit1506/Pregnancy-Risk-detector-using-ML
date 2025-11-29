# Maternal Health Risk Prediction

This repository contains a machine learning project that predicts maternal health risk levels (Low, Medium, High) using clinical parameters. It aims to support early identification of potential pregnancy-related complications and assist healthcare decision-making.


## Project Overview

- Dataset cleaning (handling missing values and duplicates)
- Feature encoding and preprocessing
- Model training using Logistic Regression, Random Forest, and XGBoost
- Model evaluation using accuracy, confusion matrix, and classification report
- Final prediction of maternal health risk levels


## Dataset Features

| Feature | Description |

| Age | Age of the patient |

| Systolic_BP | Systolic blood pressure |

| Diastolic_BP | Diastolic blood pressure |

| Blood_Sugar | Blood sugar level |

| Hemoglobin | Hemoglobin concentration |

| Urine_Albumin | Presence of protein in urine |

| Urine_Sugar | Presence of sugar in urine |

| VDRL | Syphilis test result |

| HBsAG | Hepatitis B surface antigen test result |

| Risk_Level | Target output (Low, Medium, High) |


## Workflow

1. Data loading and inspection  
2. Preprocessing (missing values, encoding, scaling)  
3. Train-test split  
4. Model training: Random Forest, XGBoost, Logistic Regression  
5. Evaluation and result generation  
6. Risk level prediction

## Model Performance (Example Results)

| Model | Accuracy |

| Random Forest | 97–99% |

| XGBoost | 95–98% |

Note: Random Forest performed best among the evaluated models.

**Future Improvements**

Deploy using Streamlit or Flask

Hyperparameter tuning for higher accuracy

Integrate dashboard for clinical use
