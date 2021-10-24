# Deep Learning (Small Project) - Group 20
- There are 2 folders:
  - `Notebook and BONUS - Data Aug` folder consists of the required codes and bonus codes for data augmentation
  - `BONUS - LR Scheduler` folder consists of the bonus codes for learning rate scheduler
- Our best models are saved in the `Best_Models` directory (i.e. `BONUS - LR Scheduler/Best_Models` and `Notebook and BONUS - Data Aug/Best_Models`)
  - There is a `load_model` function in each notebook which takes in a directory path to load a saved model.
  - Load our trained models in the `Best_Models` directory to recreate the exact train model and performance results as shown in our report.
- To retrain the model from scratch, run the notebook top down (without loading our trained models in the `Best_Models` directory)

- External libraries are used. There are cells in the notebooks to download these required libraries. The libraries are:
  - pytorch-ignite
  - https://github.com/Bjarten/early-stopping-pytorch.git
