# nsl-v2
Model to identify north star customers early in the application flow

Training less than 10K as regular and greater than 15K as NS.
Not applied PCA, excluded demographic & business pitch features

Excluding azlo custoomers:
    2021 july to 2022 oct - train_test
    2022 Nov to 2022 Feb - OOT

Data Sources: application, alloy, segment features

Execution Order (Data Creation, Feature Engg and Model Training):
    dataset_creation.ipynb
    dataset_train_test_split.ipynb
    business_pitch_processing.ipynb
    applications_features.ipynb
    nsl_v2_alloy_feature_engg.ipynb
    nsl_v2_segment_feature_engg.ipynb
    nsl_v2_modelling.ipynb

Remaining notebooks are for further analysis
