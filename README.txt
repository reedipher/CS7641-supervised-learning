- Clone repository
    git clone git@github.com:reedipher/CS7641-supervised-learning.git supervised-learning

- Install Anaconda python if not already installed
    https://www.anaconda.com/distribution/
    Download Linux Python 3.7 installer and follow instructions (bash Anaconda*.sh)

- Install latest scikit-learn
    $ pip install -U scikit-learn

- Go into directory and open up jupyter notebook
    $ cd supervised-learning
    $ jupyter notebook

- Open 'Assignment 1.ipynb'

- Run first two cells to confirm the latest scikit-learn library is installed.

- Choose which dataset you want to test in the 'Chosen Dataset' section
    ex:
    Wine Quality:
        X = wineX
        y = winey
        labels = wine_labels

    Digits
        X = digitsX
        y = digitsy
        labels = digits_labels

- From there, you can run each cell individually by pressing 'Shift+Enter', or click the 'Kernel' tab along the
  top menu and selecting 'Restart and Run All'. This may take a while, but will run all cells.

NOTE: Some cells require inputs based on feedback from the charts. For example, when running the Boosting
      algorithm to try to find the correct n_estimators, you will need to set whichever value you decide on
      in the declaration of the AdaBoostClassifier() in the Learning and Scalability section

