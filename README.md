# ERTNet_IPR
This is the repository for the course project for course EE798R, Intelligent Pattern Recognition at IIT Kanpur during the odd semester 2024-25. 
Implelemtation of the paper ERTNet: an interpretable transformer-based framework for EEG emotion recognition (https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1320645/full).

# To run the .ipynb file
-check requirements.txt and confirm the the requirements are met in your python environment

-save the preprocessed DEAP dataset in the /data_processed directory (delete the data_processed/README.md) and provide the path for /PREPROCESSED/data_preprocessed_python in the notebook

-sequentially run all the cells (except the bayesian optimization part as the optimal parameters stated in the research paper are already being used in the models )

# RUN ERTNet_DEAP_DATASET_TRAINING_PART2.ipynb
To run the Updated Code, you do not need any more requirements and you can run it in the same way as with the first file

### Optional
-To do 10-fold training on all comparison models change the code in the corresponding cells to match the code for the 10-fold training of ERTNet model
