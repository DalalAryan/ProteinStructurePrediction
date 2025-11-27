# Protein Structure Prediction Model with Multilayer Perceptron, LinearSVC and Logistic Regression (CUDA & PyTorch)

This is a 'Protein Structure Prediction Model' as part of UCLA Math 156: Machine Learning Fall 2025 Final Project. Our model is a collaborative project with fellow team members: Andrew Zhang, Steven Villanueva, and Jiwoo Hyun. We have developed a Naive Bayes Classifier Model to predict Protein Structure from protein sequences. 

The project proposal can be found [Math 156 Machine Learning Project Proposal.pdf](here).\
The project slides talk given on December 03, 2025 can be found [Math 156 Machine Learning Protein Structure Classification.pdf](here).\
The project report with greater detail on models used and a thorough discussion on results can be found [Math 156 Machine Learning Project Report.pdf](here).

Please note that as this was a 2 week long project, our work is quite limited and we can only demonstrate a surface overview of our conceptual understanding (through what could be considered trivial details in machine learning). 

### Acknowledgements

The dataset used in this project is from UCLA CS C121: “Probabilistic Models in
Computational Genomics” developed by Prof. Eleazar Eskin. Our raw data comes from
this course’ dataset.

The ESM-2 Models were released by Meta alongside their “Evolutionary-scale
Prediction of Atomic Level Protein Structure with a Language Model” paper. They
were accessed through the HuggingFace transformers package.

The ESM-2 Embeddings and building the Feedforward Neural Network were done with
PyTorch, using CUDA on Google Colab’s A100 GPU. We used cuML packages to run
LinearSCV and LogisticRegression on the GPU.

Evaluation were done with Scikit-learn.metrics. Visualizations done with Matplotlib
and Seaborn.
