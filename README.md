# LLM Hallucinations: Classification, Detection and Mitigation Methods


## Repository Structure

### Data Generation & Metrics Calculation
| File | Description |
|:-----|:------------|
| `qwen_generation.ipynb` | Generate responses from Qwen and compute metrics |
| `gpt.ipynb` | Generate responses from ChatGPT and compute metrics |
| `yagpt.ipynb` | Generate responses from YandexGPT and compute metrics |
| `giga.ipynb` | Generate responses from GigaChat and compute metrics |

### Generated Results
| File/Folder | Description |
|:------------|:------------|
| `results_raw/` | Raw model responses |
| `results_all_annotated/` | Annotated responses (metrics + ground truth) |

### Experiments
| File | Description |
|:-----|:------------|
| `Metrics.ipynb` | Individual metrics analysis (threshold optimization by F1) |
| `ML_all_f1_opti.ipynb` | ML models, optimization by F1 |
| `ML_all_f1_opti_down.ipynb` | ML models, F1 + downsampling |
| `ML_all_recall_opti.ipynb` | ML models, optimization by Recall |
| `ML_ALL_DOWN_recall.ipynb` | ML models, Recall + downsampling |


