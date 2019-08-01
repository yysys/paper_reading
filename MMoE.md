# Modeling Task Relationships in Multi-task Learning with Multi-gate Mixture-of-Experts
MTL学习已经应用到大规模推荐系统中。研究人员们通常采用正则化和迁移学习来提升模型的预测能力，然而在实践中，一些MTL模型的效果并没有比单模型效果好，因为很多基于DNN的MTL模型和数据分布、不同任务间的关系有关。尤其当不同任务间广泛共享参数时，不同任务就体现出固有矛盾。本文提出一种新颖的MTL神经网络MMoE。
![png7](https://github.com/yysys/paper_reading/blob/master/images/7.png)
MMoE对于多个任务学习多个表示层，并将多个表示层Mixture起来，通过Gate来控制表示层与各个任务间的连接。<br>
为了测试MMoE的表达能力，本文构建了一个人工数据集，并在人工数据集上测试网络权重相似度与label的相关性的关系：
![png8](https://github.com/yysys/paper_reading/blob/master/images/8.png)
本文在UCI数据集上测试了MMoE网络的效果：
![png9](https://github.com/yysys/paper_reading/blob/master/images/9.png)
最后，本文也在大规模真实推荐数据集上测试MMoE的效果：
![png10](https://github.com/yysys/paper_reading/blob/master/images/10.png)
