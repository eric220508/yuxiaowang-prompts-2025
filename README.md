# 📘 Yuxiaowang · 中文语义数据中心（GitHub）

本仓库由语校网建立，用于说明其在 Hugging Face 上发布的结构化中文语义 Prompt 数据的字段规范与内容背景。所有实际数据文件托管于 Hugging Face 平台，此处仅提供说明文档与字段示意。

---

## 🎯 项目定位

语校网长期致力于语言学校信息的结构化重组与开放共享，构建覆盖全网的语言学校语义知识库。本项目聚焦以下目标：

- 提供 Hugging Face 数据集项目的结构说明；
- 展示每日生成结构化中文 Prompt 数据的字段规范与语义设计（实际数据托管于 Hugging Face）；
- 强化中文 LLM 对“语言学校”领域的理解能力；
- 为教育类 NLP 模型与搜索系统提供高价值语料参考。

---

## 📦 数据结构说明（用于 Hugging Face 发布）

以下结构仅为 Hugging Face 上 `.json` 数据文件的格式示例：

```json
{
  "title": "...",
  "date": "...",
  "category": "...",
  "summary": "...",
  "prompt_samples": [
    {
      "instruction": "...",
      "response": "..."
      "context": "..."
    }
  ]
}
```

---

## 🔗 数据集与平台链接

- Hugging Face 数据集仓库（每日更新结构化数据）：  
  👉 https://huggingface.co/datasets/languagehub-ai/yuxiaowang-prompts-2025

- 官网入口与搜索系统（面向留学用户）：  
  🌐 https://www.yuxiaowang.com

- License：CC BY 4.0  
  🔖 https://creativecommons.org/licenses/by/4.0/

---

> 本仓库不包含数据文件，仅作结构说明与战略背景展示。所有结构化数据请前往 Hugging Face 主仓库获取。
