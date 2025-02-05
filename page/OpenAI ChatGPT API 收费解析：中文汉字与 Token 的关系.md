# OpenAI ChatGPT API 收费解析：中文汉字与 Token 的关系

ChatGPT API 是 OpenAI 提供的用于调用 GPT 模型的接口，更准确的称呼应为 OpenAI API。那么，这个 API 的收费标准是什么？1 美元能购买多少 Token？一个中文汉字或英文字符又会占用多少 Token 呢？本文将详细解析 ChatGPT API 的收费标准，并教你如何计算 Token。

## 一、OpenAI ChatGPT API 收费标准

OpenAI ChatGPT API 采用收费模式，不同模型（如 GPT-3.5、GPT-4.0 等）的收费标准各不相同。以下是根据 OpenAI 官方最新（2024 年 5 月 28 日更新于 OpenAI 官网）的 API 价格。

### 1. GPT-3.5 Turbo API 价格

- **gpt-3.5-turbo**：该系列的旗舰型号，支持 16K 上下文窗口，专为对话优化。
- **gpt-3.5-turbo-instruct**：仅支持 4K 上下文窗口的 Instruct 模型。

### 2. GPT-4 API 价格

GPT-4 拥有广泛的通识知识和领域专业知识，能够处理复杂的指令并准确解决难度较高的问题。

### 3. GPT-4 Turbo API 价格

- **128K 上下文**，知识库更新至 2023 年 4 月。
- 比 GPT-4 更强大，且价格更低。

| Model                     | Input                | Output               |
|---------------------------|----------------------|----------------------|
| gpt-4-0125-preview        | $10.00 / 1M tokens   | $30.00 / 1M tokens   |
| gpt-4-1106-preview        | $10.00 / 1M tokens   | $30.00 / 1M tokens   |
| gpt-4-1106-vision-preview | $10.00 / 1M tokens   | $30.00 / 1M tokens   |

### 4. GPT-4o API 价格

- **128K 上下文**，知识库更新至 2023 年 10 月。
- 速度更快，价格更低。

| Model                     | Input                | Output               |
|---------------------------|----------------------|----------------------|
| gpt-4o                    | $5.00 / 1M tokens    | $15.00 / 1M tokens   |
| gpt-4o-2024-05-13         | $5.00 / 1M tokens    | $15.00 / 1M tokens   |

### 5. GPT-4o mini API 价格

2024 年 7 月 18 日推出的最新轻量级经济实惠模型，比 GPT-3.5 Turbo 更聪明、更便宜，且同样快速。

| Model                     | Input                | Output               |
|---------------------------|----------------------|----------------------|
| gpt-4o-mini               | $0.150 / 1M tokens   | $0.600 / 1M tokens   |
| gpt-4o-mini-2024-07-18    | $0.150 / 1M tokens   | $0.600 / 1M tokens   |

更多模型价格（如 Fine-tuning models、Assistants API）可以直接前往 OpenAI 官网查看。

## 二、OpenAI ChatGPT API Token 计算方式

在 OpenAI ChatGPT API 的收费标准中，Token 是一个重要的计算单位。那么，一个 Token 到底是多少？一个中文汉字、英文字符或英文单词又分别占用多少 Token 呢？

简单来说：
- **1k Token ≈ 750个英文单词或 500个中文汉字**。
- 最便宜的模型 1k Token 仅需 **0.002美元**。

值得注意的是：**输入（Input）和输出（Output）都需要收费**。

OpenAI 提供了一个在线工具，方便用户计算某段回答所使用的 Token 数量：👉 [OpenAI Tokenizer](https://platform.openai.com/tokenizer)

以下是一些示例：
- 英文单词“ChatGPT”占用 **3个 Token**。
- “AI”占用 **1个 Token**。
- 部分中文汉字（如“的”、“是”、“一”等）占用 **1个 Token**。
- 大部分中文汉字占用 **2个 Token**。

![ChatGPT API Token 计算方式](https://bbtdd.com/img/11772581984619.webp)

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)