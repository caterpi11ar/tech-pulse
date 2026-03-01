# 不足100个参数的Transformer实现10位数加法100%准确率

![Tiny Transformers研究](https://opengraph.githubassets.com/2aa356a9034952e47a8c0a7c95a651303e77b03ba6817)

研究人员近日展示了一项令人瞩目的实验结果：参数量不足100个的微型Transformer模型，能够以100%的准确率完成两个10位数字的加法运算。

**事件经过**

该研究以开源项目 AdderBoard 的形式发布于 GitHub，随即在机器学习社区引发广泛讨论。实验证明，在特定结构化任务上，极小规模的神经网络可以达到完美的精度，无需数十亿参数规模的大模型。

**背景与意义**

这一发现对当前AI领域主流的"越大越强"认知提出了新的视角。现有的大语言模型动辄数十亿至万亿参数，而这项研究表明，对于特定类型的任务，模型架构与训练方式的设计可能比参数规模更为关键。此外，小型模型的可解释性远优于大型模型，研究者可以逐个分析权重，理解模型的工作机制。

**延伸阅读**

- 项目代码已开源：https://github.com/anadim/AdderBoard
- 讨论帖：https://www.reddit.com/r/MachineLearning/comments/1rhjjba/
