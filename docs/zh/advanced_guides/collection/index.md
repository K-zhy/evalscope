# 数据混合评测

本框架支持混合多个评测数据集进行统一评测，期望使用更少的数据，获得更全面的评测模型能力。

整体评测流程为：

1. 定义数据混合schema：定义使用哪些数据进行评测，以及数据如何分组
2. 采样数据：框架将根据schema，从各个指定的数据集中进行采样
3. 统一评测：经过采样的数据将被用于统一的评测过程

:::{toctree}
:maxdepth: 2

schema.md
sample.md
evaluate.md
:::