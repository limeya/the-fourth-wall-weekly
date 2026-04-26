# 🔥 本周热点：AI公司争相发布新模型
## [DeepSeek-V4 预览版发布：迈入百万上下文普惠时代](https://mp.weixin.qq.com/s/8bxXqS2R8Fx5-1TLDBiEDg)
DeepseekV4发布，不是最强模型，并且距离最强模型有距离，文章里直接说了：
> “相比前代模型，DeepSeek-V4-Pro 的 Agent 能力显著增强。在 Agentic Coding 评测中，V4-Pro 已达到当前开源模型最佳水平，并在其他 Agent 相关评测中同样表现优异。目前 DeepSeek-V4 已成为公司内部员工使用的 Agentic Coding 模型，据评测反馈使用体验优于 Sonnet 4.5，交付质量接近 Opus 4.6 非思考模式，但仍与 Opus 4.6 思考模式存在一定差距。”  

很少有公司这么诚实的，作为一个开源模型，这种行为无疑会赢得社区的信任。虽然不是最强，但是仍然很好用，内部已经在用了，而且据说更便宜了，这样压力更到了其他的国产模型，甚至国外更强的模型。
## OpenAI发布GPT-5.5和GPT Image 2
[OpenAI发布GPT-5.5](https://x.com/openai/status/2047376561205325845?s=12)和[GPT Image 2](https://x.com/openai/status/2046670977145372771)
- GPT-5.5版本模型，进一步提升了代码生成和推理能力，也变贵了；
- GPT Image 2模型真的很好用，之前一直用nano banana，但是google的模型生成中文总有一种蝌蚪的感觉，不是很好用，但是GPT的新模型完全没有，很逼真。
## [阿里巴巴开源Qwen3.6-27B](https://x.com/alibaba_qwen/status/2046939764428009914?s=12)
阿里云发布旗舰级开源模型Qwen3.6-27B，在编码能力上达到业界领先水平。
## [Kimi-2.6发布](https://x.com/kimi_moonshot/status/2046249571882500354)
Kimi-2.6本周也发布了，而且也快速在多个服务商上架了，在代码能力上又增强了。
# 🤖 AI与经济社会
## [科技巨头的AI竞赛格局正在重塑](https://x.com/a16z/status/2047776615133069695?s=12)
a16z最新的文章指出，AI领域的竞争格局正在发生根本性变化。传统科技巨头的优势正在被新兴AI原生公司挑战，当前的公司在10年前几乎不存在。
## [AI代理如何改变未来工作模式](https://arxiv.org/abs/2506.06576)
最新研究论文探讨了AI agent在自动化审计和工作流程重构中的应用前景，详细说明agent可能发挥的作用。
# 🔧 开源工具与教程 

## [lite-edit：轻量级macOS代码编辑器](https://github.com/arietan/lite-edit)
使用Swift和AppKit构建的快速、轻量级代码编辑器，专为macOS优化，在VSCode等重型编辑器主导的今天，lite-edit提供了一个清爽的选择。对于追求效率和系统资源优化的开发者来说，值得一试。
## [lux: Go语言实现的cli视频下载工具](https://github.com/iawia002/lux)
Go语言实现的cli视频下载工具，可以下载YouTube和哔哩哔哩等热门网站的视频，建议谨慎使用。
## [Claude Code交互式学习平台](https://claude.nagdy.me/learn/slash-commands/claude.nagdy.me/learn/slash-commands/)
教程里通过12个交互式模块帮助开发者从基础到高级掌握Claude Code的各种功能，这种交互式学习方式比传统的文档阅读更有效。
# 🎧 播客推荐

## [霍尔木兹海峡千年史](https://www.xiaoyuzhoufm.com/episode/69e1fb9c1e94ae69217d20ec?s=eyJ1IjogIjYxMjMyMzg5ZTBmNWU3MjNiYmVmMzYzZSJ9)
历史是最好的老师，这个播客谈到了霍尔木兹海峡的前世今生，有助于理解当今中东局势的复杂性，我是在上班的地铁上听完的，觉得很有意思，其中听到阿曼这个当今的中东小国历史上还是一个横跨几大洲的大国，甚至还打败了葡萄牙，觉得还是挺有意思的。
# 🧠 言论与争议

## [Ollama的争议之路](https://sleepingrobots.com/dreams/stop-using-ollama/)
该文深度剖析Ollama的发展历程，揭示其在开源社区中的争议行为，其本质是llama.cpp的包装器，虽然封装的更好用，但是完全不遵守MIT协议，甚至诱导大家走向闭源甚至云模型，属实吃相有点难看，开源和商业利益我觉得是可以共存的，但是显然ollama没有做到。
## [Meta监控其工作人员到令人恐怖的程度](https://x.com/ayi_ainotes/status/2046931744897548685?s=12)
该post深入分析Meta内部监控备忘录，发现Meta监控工作人员已经到令人震惊的程度。
## [NVIDIA的GPU就是过去Intel时代的CISC ISA](https://x.com/jimkxa/status/2045910513025200617)

Jim Keller在最近的X上发文：
> Intel won by RISCifying their CISC - still amazed how well x86-64 worked out LPUs is a subset of AI, an accelerator, it's not the RISC [@tenstorrent](https://x.com/tenstorrent), Trainium, Google TPU are closer. Clean Tensor processor is step one. Then generality, memory and Networking. And of course LInux and Open source software were key for Intel. AI software is a curious swamp tbh

Elon Mask也针对同样的话题发文：
> The best combination of software and hardware will win