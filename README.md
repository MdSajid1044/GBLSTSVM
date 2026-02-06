# GBLSTSVM - Enhancing robustness and efficiency of least square twin SVM via granular computing

Please cite the following paper if you are using this code.
Reference: Tanveer, M., Sharma, R. K., Quadir, A., & Sajid, M. (2025). Enhancing robustness and efficiency of least square twin SVM via granular computing. Pattern Recognition, 112021. https://doi.org/10.1016/j.patcog.2025.112021

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
The experiments are executed on a computing system possessing Python 3.11 software, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128-GB Random Access Memory (RAM), and a Windows-10 operating platform.

We have put a demo of the “LS-GBTSVM” model with the “breast_cancer” dataset

The following are the best hyperparameters set with respect to the “breast_cancer” dataset

Regularization Parameter c_1=1000  ,  c_2= 0.00001 

Description of files:
main.py: This is the main file to run selected algorithms on datasets. In the path variable specificy the path to the folder containing the codes and datasets on which you wish to run the algorithm.
addNoisy.py: Add Noise label
gen_ball.py: Generation of granular balls
GBLSTSVM.py: Solving the optimization problem

The codes are not optimized for efficiency. The codes have been cleaned for better readability and documented and are not exactly the same as used in our paper. For the detailed experimental setup, please follow the paper. We have re-run and checked the codes only in a few datasets, so if you find any bugs/issues, please write to Rahul Kumar Sharma (rsharma459@gatech.edu).



           
