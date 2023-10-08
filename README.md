# cyber-threat-topic-model
Topic modelling (BERTopic) for Cyber threat categorisation with Feature Importance

High-level Process
1. Simulate Data by GPT (Data simulation\data_simulation_fromGPTv2.ipynb)
2. BERTopic Pipeline (BERTopic)
   2.1 Searching for best sub-models with Hyperparameter Tuning
       a) with Attribute-Specific Approach (BERTopic_pipeline_tuning-sepFeature.ipynb)
       b) with United Document Approach (BERTopic_pipeline_tuning.ipynb)
   2.2 Generate relevant result data and graphs for the finalist sub-models (BERTopic_pipeline_result-generation.ipynb)
3. Feature Importance Analysis by Classifiers Training (Classifications)
   a) Random Forest (RandomForest\RandomForest_v3-Tuning.ipynb)
   b) XGBoost (XGBoost\XGBoost_v3-Tuning.ipynb)
   c) Linear SVM (SVM\SVM_v3-Tuning.ipynb)

Tables and Figures used in the paper are also provided.
