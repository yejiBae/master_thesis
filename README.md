# Drug-Drug Interaction Prediction for Side Effects, Diseases, and Cell Lines Using Three-step Kernel Ridge Regression
<!-- ## Abstract  -->
When people take multiple drugs, there is a possibility of interactions between drugs which can cause severe side effects, even death. These interactions might occur for specific diseases or locations in a body. Knowing the interactions beforehand in silico can vastly decrease the risk of side effects and test expenses. Thus, predicting drug-drug interaction has been challenging in pharmaceutical, medical, and clinical research and development. In this work, we aim for more practical use by predicting drug-drug interactions with third objects, referred to as "targets." We define the problem as drug-drug-target interaction prediction where targets are side effects, cancer cell lines, and diseases for this experiment. In this way, we can not only predict relevant side effects for a drug pair but also use the prediction outputs for drug repositioning, finding the effective drug combination for a disease or location in a body. To that end, we applied feature-based kernel ridge regressions, taking advantage of objects' features or side information for learning. We applied SMILES and Morgan fingerprint for drug features and ICD codes for disease. If no feature was available, we used training labels as a feature. Furthermore, we proposed suitable cross-validation schemes to cover cold-start problems, predicting for newly developed drugs. As a result, we obtained reliable AUC scores (AUC-ROC = 0.66 for the most complicated cold-start task up to AUC-ROC = 0.95 for the regular triplet prediction). Additionally, we investigate the influence of the imbalanced class.
