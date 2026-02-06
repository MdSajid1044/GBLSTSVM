# GBLSTSVM - Enhancing robustness and efficiency of least square twin SVM via granular computing

Please cite the following paper if you are using this code:

Tanveer, M., Sharma, R. K., Quadir, A., & Sajid, M. (2025). Enhancing robustness and efficiency of least square twin SVM via granular computing. Pattern Recognition, 112021. https://doi.org/10.1016/j.patcog.2025.112021

BibTex
---
```
@article{tanveer2025enhancing,
  title={Enhancing robustness and efficiency of least square twin SVM via granular computing},
  author={Tanveer, M and Sharma, RK and Quadir, A and Sajid, M},
  journal={Pattern Recognition},
  pages={112021},
  year={2025},
  Volume={170},
  publisher={Elsevier}
}
```

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
The experiments are executed on a computing system running Python 3.11, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128 GB of Random Access Memory (RAM), and Windows 10.

We have put a demo of the “LS-GBTSVM” model with the “breast_cancer” dataset

The following are the best hyperparameters set with respect to the “breast_cancer” dataset

Regularization Parameter c_1=1000  ,  c_2= 0.00001 

Description of files:

main.py: This is the main file to run selected algorithms on datasets. In the path variable, specify the path to the folder containing the codes and datasets on which you wish to run the algorithm.

addNoisy.py: Add Noise label

gen_ball.py: Generation of granular balls

GBLSTSVM.py: Solving the optimization problem

The codes are not optimized for efficiency. The codes have been cleaned for better readability and documented. For the detailed experimental setup, please follow the paper. We have re-run and checked the codes only in a few datasets, so if you find any bugs/issues, please write to Rahul Kumar Sharma (rsharma459@gatech.edu) or A. Quadir (mscphd2207141002@iiti.ac.in or abdulquadir19991@gmail.com) or M. Sajid (phd2101241003@iiti.ac.in, sajid.mathml@gmail.com).



           
