# CVPR2022 NAS竞赛Track 2第1名技术方案

## 项目描述
> 如何通过小样本训练并准确预测是一项不容忽视但不并容易的任务。 其中如何分析和训练数据集以克服过拟合是我们应该解决的核心问题。 如果存在多任务问题，我们还应该考虑是否可以利用它们的相关性并尽可能快地进行参数估计。 在这个赛道上，Super Network 构建了一个基于 ViT-Base 的搜索空间， 搜索空间包含depth、num-heads、mpl-ratio和embed-dim。 我们首先做的是根据我们对这个问题的理解对数据进行预处理，这样可以降低问题的复杂性和过拟合的概率。 然后我们尝试了不同类型的模型和不同的组合方式。 最后，我们选择运用 GP-NAS 堆叠集成模型并做交叉验证。 我们的模型在 CVPR 2022 Track 2 Challenge 中排名第一。

## 关键词：
堆叠模型，集成模型, 交叉验证，GP-NAS

## 项目结构
> 一目了然的项目结构能帮助更多人了解，目录树以及设计思想都很重要~
```

-|CVPR_2022_NAS_Track2_submit_ACCNAS_1.json 最终结果1
-|CVPR_2022_NAS_Track2_submit_ACCNAS_2.json 最终结果2
-|CVPR_2022_NAS_Track2_test.json test数据
-|CVPR_2022_NAS_Track2_train.json train数据
-main.ipynb 主文件
-README.MD
```
## 使用方式
> 运行main.ipynb,请将数据路径改为本地路径
