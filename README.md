# STAT115
刘小乐老师生物信息学与计算生物学课程笔记  
https://canvas.harvard.edu/courses/49497

## Bioinfo history
**Smith-Waterman algorith** ：是一种进行局部序列比对（相对于全局比对）的算法，用于找出两个核苷酸序列或蛋白质序列之间的相似区域。该算法的目的不是进行全序列的比对，而是找出两个序列中具有高相似度的片段。  
**PDB**: Protein data bank，蛋白质数据库。  
**BLAST**: 全称Basic Local Alignment Search Tool，即"基于局部比对算法的搜索工具"。Blast能够比较两段核酸或者蛋白序列之间的同源性，它能够快速的找到两段序列之间的同源序列并对比对区域进行打分以确定同源性的高低。  

有了蛋白质序列可以预测蛋白质结构

**Connectivity map**: Connectivity Map 是药物基因组学研究领域的重要数据库，是计算生物学和药物筛选研究人员做研究时不得不重视的数据库。它不仅提供大量宝贵的药物处理人类细胞系前后的基因表达谱数据，而且也提供了基于模式匹配算法的在线工具，用户提交合适的基因列表就能得到该数据库中与之相关的药物。

**PCR**: 聚合酶链式反应是一种用于放大扩增特定的DNA片段的分子生物学技术，它可看作是生物体外的特殊DNA复制，PCR的最大特点是能将微量的DNA大幅增加。  

**CRISPR/Cas技术**  

CRISPR/Cas系统是一种原核生物的免疫系统，用来抵抗外源遗传物质的入侵，比如噬菌体病毒和外源质粒。同时，它为细菌提供了获得性免疫：这与哺乳动物的二次免疫类似，当细菌遭受病毒或者外源质粒入侵时，会产生相应的“记忆”，从而可以抵抗它们的再次入侵。CRISPR/Cas系统可以识别出外源DNA，并将它们切断，沉默外源基因的表达。这与真核生物中RNA干扰（RNAi)的原理是相似的。正是由于这种精确的靶向功能，CRISPR/Cas系统被开发成一种高效的基因编辑工具。

**Quantile normalization**  
表达矩阵的每一列都是一个样本，每一行都是一个基因或者探针，值为表达量。quantile normalization 就是对每列单独进行排序，排好序的矩阵求平均值，得到平均值向量，然后根据原矩阵的排序情况替换对应的平均值，所以normalization之后的值只有平均值了。
