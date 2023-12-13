# GraphMachineLearning
Comparing the effectiveness of State-of-the-Art Graph ML models vs the traditional approaches involving Linear Algebra for link prediction task


## Instructions:
The dataset is fetched and processed in a separate script in `Basic/movielens_exploration.ipynb` but the `train.pt`, `test.pt` and `val.pt` are saved in `data/` so we use these sets directly. <be>
1. **Linear Algebra Approach**: This is in the `Linear Algebra Approach/personalised_page_rank.ipynb` notebook. Please upload the `train.pt`, `test.pt` and `val.pt` from `./data/movielens/` into `./data/movielens/` directory in Colab and execute all cells in the notebook to get the result.
2. **Graph Neural Network (SOTA) Approach**: This is in the `MovieLens_GNN_Link_Prediction.ipynb` notebook. Please upload the `train.pt`, `test.pt` and `val.pt` from `./data/movielens/` into `/` directory in Colab and execute all cells in the notebook to get the result.

## Results

| Linear Algebra Results | Graph Neural Network (SOTA) Results |
|---|---|
| ROC_AUC Curve  |   |
| <img width="410" alt="image" src="https://github.com/AbdullahAshfaq/GraphMachineLearning/assets/68285463/6a410260-fd55-4ce9-9a50-21e04fa28615">  |  <img width="437" alt="image" src="https://github.com/AbdullahAshfaq/GraphMachineLearning/assets/30476158/b62b4321-d5ec-4fcb-b19e-b0e0c4bec735"> |
|  Precision Recall Curve |  |
|  <img width="410" alt="image" src="https://github.com/AbdullahAshfaq/GraphMachineLearning/assets/68285463/245334bd-990f-441c-ad87-86fc1f1e9ce1"> |  <img width="436" alt="image" src="https://github.com/AbdullahAshfaq/GraphMachineLearning/assets/30476158/db7df2f1-3a71-4461-968d-02dbff731471"> |
