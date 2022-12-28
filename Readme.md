# AAIT-Nosy-Missing-Labels

The task solved is image classification.
There are 2 challenges to the data used missing labels and noisy labels.

## Setup conda environment

    conda create -n my_env_name python=3.8 # do only the first time
    conda activate my_env_name # every time you run the notebook
    pip install ipykernel --user # to install notebook requirements
    python -m ipykernel install --user --name=myenv  # to add to notebook environments
    pipreqs . --force # to update the requirements 

## Data setup

You should move the 2 archives: `task1.tar.gz` and `task2.tar.gz` in the data directory.

## Notes for the report

In literature, when you have missing labels, the task is called semi-supervised learning. 
An effective semi-supervised learning algorithm can achieve better performance than a supervised learning algorithm fir only on the labeled training examples.
Page 4, Semi-Supervised Learning, 2006. [link](https://books.google.ro/books?id=A3ISEAAAQBAJ&dq=Semi-Supervised+Learning+(Adaptive+Computation+and+Machine+Learning+series)+1st+Edition+by+Olivier+Chapelle+(Editor),+Bernhard+Scholkopf+(Editor),+Alexander+Zien+(Editor)+google+books&source=gbs_navlinks_s) TODO: add proper bibtex citation.