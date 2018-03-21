This is sample implementation of DuSK: A Dual Structure-preserving Kernel for Supervised Tensor Learning with Applications to Neuroimages. Please cite as  

    Lifang He, Xiangnan Kong, Philip S. Yu, Ann B. Ragin, Zhifeng Hao, Xiaowei Yang
    "DuSK: A Dual Structure-preserving Kernel for Supervised Tensor Learning with Applications to Neuroimages"
    Proceedings of the 14th SIAM International Conference on Data Mining (SDM14), 2014.
    http://.pdf
    

# [Dependencies]
  CP tensor factorization Toolbox : 
  
    This function needs the CP tensor factorization toolbox (default is cp3_alsls)
    
  SVM solver:
  
    Libsvm toolbox (default is libsvm-3.17)

# [Table of Contents]
Main.m                : demonstrate the algorithms on a CP factorization dataset and show the usages

Divide.m              : Divide the data into k-fold 

TrainAverAcc.m        : train optimal support higher-order tensor machine with DuSK kernel

Ker_DuSK.m            : calculate the DuSK kernel (RBF or linear).

# [Dataset]
Data_ADNI.mat         : the CP factorization result of ANDI dataset

You can factorize each dataset by cp3_alsls toolbox, like Data_ADNI
     

# [Question?]
Please send your questions to lifanghescut@gmail.com
