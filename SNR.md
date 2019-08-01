# SNR: Sub-Network Routing for Flexible Parameter Sharing in Multi-task Learning
### 在机器学习领域，像目标检测、内容推荐通常要求的多个优化目标。多任务学习MTL收到大量关注。Shared-Bottom网络(SB)是MTL中经典的模型，然而当学习的任务不相关，SB网络的准确率就受到挑战。本文提出Sub-Network Routing (SNR)网络，相对于SB网络，SNR采用软参数共享。
![png11](https://github.com/yysys/paper_reading/blob/master/images/11.png)
### SNR网络采用子网络之间路由来实现网络参数软共享。网络路由有两种方式，其中SNR-Trans采用转移矩阵相乘来实现参数交互。
![png12](https://github.com/yysys/paper_reading/blob/master/images/12.png)
### 另外一种路由方式SNR-Aver采用加权平均的方式实现参数交互
![png13](https://github.com/yysys/paper_reading/blob/master/images/13.png)
### 网络的参数优化采用autoML NAS搜索来实现。论文的实验在数据集YouTube8M上实现：
![png14](https://github.com/yysys/paper_reading/blob/master/images/14.png)


