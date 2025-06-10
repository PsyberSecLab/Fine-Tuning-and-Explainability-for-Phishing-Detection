# Phishing 
This project investigates large language models to understand their underlying reasoning and explainability mechanisms through fine-tuning and CC-SHAP analysis.

Dataset Description:
We utilized publicly available open-source datasets: the Nazario dataset for phishing emails (2,500 samples) and the Enron dataset for legitimate (ham) emails (2,500 samples). Data cleaning involved steps such as removing ASCII codes, symbols, feature extraction and removing duplicates and so on.

Models and Methods:
Four models were fine-tuned in this study: BERT, LLaMA 7B, LLaMA 8B, and Wizard 7B. The fine-tuning techniques applied included Binary Sequence Classification, Contrastive Learning, and Direct Preference Optimization.

To evaluate explainability and reasoning consistency, we applied a consistency measure based on SHAP (SHapley Additive exPlanations) values. This approach assessed the alignment between explanations and prediction tokens, providing insights into the models' self-consistency and faithfulness in their reasoning mechanisms.
