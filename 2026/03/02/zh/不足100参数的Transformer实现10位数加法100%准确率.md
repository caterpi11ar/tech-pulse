# 不足100参数的Transformer实现10位数加法100%准确率

研究者发布 AdderBoard 项目，展示参数量不足100个的微型Transformer模型能以100%准确率完成两个10位数字的加法运算。

![Tiny Transformer](https://opengraph.githubassets.com/160c49b9b6ed7442ce0bca55c36642c1109b5b0e7a2a3a4b5c6d7e8f9a0b1c2d/anadim/AdderBoard)

**事件经过**

AdderBoard 以开源形式发布于 GitHub，代码极简，核心模型参数量控制在100以下，却能在特定结构化数学任务上达到完美精度。帖子发布于 r/MachineLearning 后迅速获得130票赞和42条评论，上赞率89%。

**背景与意义**

当前主流AI模型动辄数十亿乃至万亿参数，这一发现提供了另一个视角：对于特定任务，模型架构与训练策略的设计可能比参数规模更为关键。极小模型的另一优势是可解释性——研究者可以逐个分析权重，直接理解模型的运作机制，这在大型模型中几乎不可能实现。

**延伸阅读**

- GitHub 项目：https://github.com/anadim/AdderBoard
- Reddit 原帖：https://www.reddit.com/r/MachineLearning/comments/1rhjjba/
