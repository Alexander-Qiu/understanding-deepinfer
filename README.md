# 深入理解 DeepInfer

由 **OpenAI Codex** 生成，先 vibe coding 占个位，内容待完善，仅供学习参考。

一句话就能生成一个 repo；我对开源生态的悲观在于，Agent 可以批量制造垃圾、挤占有限的注意力，让真正有价值的工作更难被看见。

从源码出发，理解 [DeepInfer](https://github.com/deepseek-ai/DeepInfer) 的设计与实现。

计划围绕请求调度、模型执行、KV Cache、采样与并行机制展开。当前仅完成仓库初始化。

每篇解读标明源码版本，区分代码事实、推测与实测结果。文档放在 `docs/`，可运行示例按需添加。

## 相关项目

- [awesome-deepinfer](https://github.com/Alexander-Qiu/awesome-deepinfer)：资料索引。
- [nano-deepinfer](https://github.com/Alexander-Qiu/nano-deepinfer)：最小 CPU 教学实现。

非 DeepSeek 官方项目，仅供学习参考。
