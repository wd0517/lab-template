# 构建一个最小向量搜索应用

## 概述

AI 是目前的前沿领域，吸引了许多渴望学习的开发者。然而，在学习过程中往往存在一些障碍，例如：

- 缺乏基础的 AI 知识
- 过于复杂的基础设施
- 缺少 AI 应用的全面、循序渐进的文档

为了解决这些问题，我们开发了这个实验，通过它你将学习：

- 如何使用 **TiDB Serverless** 作为 AI 应用的数据存储层，加速 AI 开发过程
- 什么是 Embedding 及其功能
- 如何利用获取到的 Embedding 向量
- 在处理大量数据时如何使用 RAG/GraphRAG 进行数据检索
- 如何使用 **DSPy** 将文本提取成图，将这些图存储在 TiDB Serverless 中，然后使用图检索来增强 RAG 能力

### 任务

- **文本相似性搜索**

  - 使用 OpenAI 的 Embedding 模型和 API 进行文本嵌入
  - 将 Embedding 向量和原始文本存储在 TiDB Serverless 中
  - 使用 TiDB 的 SQL 执行向量相似性搜索，检索与用户查询最相关的文本数据

- **图像搜索**

  - 使用 CLIP 预训练模型对图像进行特征提取，获取 Embedding
  - 将 Embedding 向量和原始图像 ID 存储在 TiDB Serverless 中
  - 使用 TiDB 的 SQL 执行向量相似性搜索，检索与给定图像特征最相似的图像

- **GraphRAG 检索**

  - 在 TiDB Serverless 中预构建的图上执行搜索
  - 使用图检索与用户查询最相关的文本数据

- **Build to Read: 完整的 GraphRAG 教程**

  - 使用 DSPy 从文本中提取实体和关系，构建图
  - 对实体执行 Embedding 向量化
  - 将实体和关系存储在 TiDB Serverless 中
  - 在 TiDB Serverless 中查询图以提高 RAG 性能

### 所需时间

- 完成本实验大约需要 1.5 小时。