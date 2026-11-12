# XAILabData

**Author:** Xiangqi Kong

The lab data and the notebooks for the two lab sessions (2 × 50 minutes) of the XAI course. Everything runs in Google Colab with PyTorch.

## Open in Colab

| Session | Lab | Start here (easy) | Stuck? (walkthrough) | Answers (solution) |
|---|---|---|---|---|
| 1 | LIME on EuroSAT (25 min) | [easy](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/1_LIME_EuroSAT_easy.ipynb) | [walkthrough](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/1_LIME_EuroSAT_walkthrough.ipynb) | [solution](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/1_LIME_EuroSAT_solution.ipynb) |
| 1 | SHAP on EuroSAT (25 min) | [easy](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/2_SHAP_EuroSAT_easy.ipynb) | [walkthrough](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/2_SHAP_EuroSAT_walkthrough.ipynb) | [solution](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-1_LIME_SHAP/2_SHAP_EuroSAT_solution.ipynb) |
| 2 | Explain your RNN forecaster (20 min) | [easy](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/1_Explain_Your_RNN_Forecaster_easy.ipynb) | [walkthrough](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/1_Explain_Your_RNN_Forecaster_walkthrough.ipynb) | [solution](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/1_Explain_Your_RNN_Forecaster_solution.ipynb) |
| 2 | Explain your Transformer forecaster (30 min) | [easy](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/2_Explain_Your_Transformer_Forecaster_easy.ipynb) | [walkthrough](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/2_Explain_Your_Transformer_Forecaster_walkthrough.ipynb) | [solution](https://colab.research.google.com/github/kxqdesign/XAILabData/blob/main/session-2_sequence_models/2_Explain_Your_Transformer_Forecaster_solution.ipynb) |

## The three versions

- **easy**: the exercise. Almost all the code is written. Each ✏️ TODO has one blank, written `BLANK`, and the comment above it tells you what goes there. A ✅ check cell follows each TODO. Short notes say what each cell does and what to notice in each result.
- **walkthrough**: nothing to fill in. The complete code with its results already shown, and a plain comment above every line of code that says what it does and why. Read it before the lab or when you are stuck.
- **solution**: the complete notebook with its results, without the extra notes.

In each notebook, do the sections marked 🟢 core in order. Sections marked ⚪ if time can be skipped.

## The lab data

`lab-data/eurosat_lab_pack_v1.npz` (38 MB) holds a small CNN already trained on EuroSAT (13 Sentinel-2 bands plus one pure-noise control channel, test accuracy 0.969) and 500 test images (50 per class). The EuroSAT notebooks download it by themselves in a few seconds, so there is no dataset download and no training in class. If the download fails, drag the file into the Colab *Files* panel and run the setup cell again.

The two sequence labs make their own data and train their small models in under a minute; they need no download.
