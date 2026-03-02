# 通义千问 Qwen 3.5 发布小尺寸模型，引发本地部署社区热议

阿里巴巴旗下通义千问团队发布 Qwen 3.5 系列的小尺寸模型版本，消息在本地大模型社区（r/LocalLLaMA）迅速传播，用户反馈其性能表现超出预期，尤其是高上下文推理速度方面令人印象深刻。

![Qwen 3.5 发布](https://images.unsplash.com/photo-1676277791608-ac54525aa94d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1080&q=80)

## 事件经过

Reddit 上的 r/LocalLLaMA 社区用户率先发布了 Qwen 3.5 小版本模型的相关信息，帖子迅速获得关注。另有用户分享了 Qwen 3.5 27B 密集版（Dense）模型的实测数据：在 170K token 上下文长度下，推理解码速度达到 100+ token/s，预填充速度约为 150 token/s。

这一性能数据对于本地部署用户而言具有较高参考价值——170K 的超长上下文结合百 token/s 的速度，意味着可以将相当大的文档或代码库塞入一次对话并得到较快响应。

## 背景与意义

Qwen（通义千问）系列模型是目前全球最具竞争力的开源大语言模型之一。Qwen 2.5 系列在多项基准测试中表现优异，其开源授权（Apache 2.0）也使其成为商业部署的热门选择。

Qwen 3.5 的发布延续了这一路线，小尺寸模型的推出尤其重要：它意味着消费级 GPU（如 RTX 4090、Mac M 系列）用户也可以本地运行高质量的模型。本地部署不依赖云服务，数据不离开本机，对隐私敏感场景（如企业内网、个人使用）有显著优势。

中国 AI 团队在开源模型领域的持续发力，正在改写全球 AI 竞争格局。

## 后续关注点

- Qwen 3.5 完整系列（包括更大参数版本）是否已全面发布？
- 与 Llama 3、Mistral 等同量级开源模型相比，Qwen 3.5 的综合性能如何？
- 阿里云后续是否会推出对应的云端 API 服务？

---

**原文来源：** [https://www.reddit.com/r/LocalLLaMA/comments/1ri2irg/breaking_today_qwen_35_small/](https://www.reddit.com/r/LocalLLaMA/comments/1ri2irg/breaking_today_qwen_35_small/)
