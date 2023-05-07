## Quantum-Computing-with-Qiskit

This is going to be my first full course developed using Github. I have uploaded some Jupyter Notebooks with my initial trials in Qiskit and the syllabus for Machine Learning for Business, Quantum Computing version. 

## Python (including Google Colab) setup:

    !pip install qutip -q
    !pip install qiskit -q
    !pip install qiskit[visualization] -q
    !pip install git+https://github.com/qiskit-community/qiskit-textbook.git#subdirectory=qiskit-textbook-src -q
    
    import numpy as np
    np.set_printoptions(precision=3, suppress=True)
    import qutip as qt 
    from matplotlib import pyplot as plt
    %matplotlib inline
    
    import pandas as pd
    import sklearn as sk
    import qiskit as qk

## Online read-only versions

Use the following links:

* [Lecture-0 Full Course on Quantum Machine Learning](http://nbviewer.ipython.org/urls/github.com/gustavomirapalheta/Quantum-Computing-with-Qiskit/blob/main/Quantum_Machine_Learning_with_Qiskit_v2023.ipynb)
