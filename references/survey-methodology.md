# 领域调研方法论 (Survey Methodology)

## 调研框架

本文档为面试官技能的阶段二（深度领域调研）提供系统性的方法论指导。

---

## 1. 技能树构建方法

### 1.1 自顶向下分解

对任意技术方向，按以下层次分解核心技能：

```
Level 0: 方向名称（如 "AI/ML Engineer"）
│
├── Level 1: 核心能力域（3-5个）
│   ├── Level 2: 子领域（每个2-4个）
│   │   └── Level 3: 具体技能点（每个3-6个）
│   │       └── Level 4: 深入考察点
```

### 1.2 搜索策略矩阵

| 调研目标 | 搜索关键词模板 | 来源优先级 |
|---------|--------------|-----------|
| 核心技能要求 | "{role} skills requirements 2025 2026" | Job postings > Tech blogs > Reddit |
| 面试高频题 | "{role} interview questions {company}" | LeetCode/Glassdoor > 牛客 > 知乎 |
| 最新技术趋势 | "{domain} latest trends {year}" | Official blogs > HN > Twitter/X |
| 最佳实践 | "{technology} best practices production" | 官方文档 > Engineering blogs > Conference talks |
| 薪资和市场 | "{role} salary {level} {location}" | levels.fyi > Glassdoor |

### 1.3 验证三原则

一个技能点被纳入面试题库前，需满足：

1. **出现频率**：在3个以上不同来源的面试经验/JD中被提及
2. **时效性**：在过去12个月内仍然相关（非已过时技术）
3. **可考察性**：可以通过面试对话有效考察（非纯实操技能）

---

## 2. 热门方向调研模板

### 2.1 AI/ML 方向

```
搜索清单：
- "machine learning engineer interview 2025 2026"
- "LLM interview questions"  
- "AI system design interview"
- "MLOps interview preparation"
- "{具体子方向} latest papers arxiv"
- "AI engineer job requirements FAANG"

重点关注：
- Transformer架构理解深度
- LLM微调与部署（LoRA, RLHF, vLLM等）
- RAG系统设计
- 多模态模型
- Agent/Multi-agent系统
- MLOps/ML系统工程
- 评估方法论
```

### 2.2 后端工程方向

```
搜索清单：
- "backend engineer interview system design 2025 2026"
- "distributed systems interview"
- "microservices interview questions senior"
- "{语言} backend interview advanced"

重点关注：
- 分布式系统设计
- 数据库选型和优化
- 缓存策略
- 消息队列
- API设计
- 容器化和编排
- 可观测性
```

### 2.3 前端工程方向

```
搜索清单：
- "frontend engineer interview 2025 2026"
- "React/Vue advanced interview"
- "web performance optimization interview"
- "frontend system design"

重点关注：
- 框架原理（虚拟DOM、响应式系统）
- 性能优化
- 状态管理
- 微前端
- Server Components / SSR
- Web标准和浏览器API
- 工程化和构建工具
```

---

## 3. 难度校准标准

### 初级（Junior）
- 考察基本概念的理解和应用
- 简单的代码实现和调试
- 基本工具使用
- 团队协作基础

### 中级（Mid-level）
- 考察原理理解和工程实践
- 中等复杂度的系统设计
- 性能优化意识
- 独立解决问题的能力

### 高级（Senior）
- 考察架构决策和权衡
- 大规模系统设计
- 技术方案评估
- 团队领导和指导能力

### Staff/Principal
- 考察跨团队技术影响力
- 技术战略和方向判断
- 复杂问题的创造性解决
- 组织级技术决策

---

## 4. 调研质量检查清单

完成调研后，用以下清单验证质量：

- [ ] 技能树覆盖了该方向的主要能力域
- [ ] 包含最近6个月的技术更新
- [ ] 题库中有不同难度层次的问题
- [ ] 每个问题都有明确的考察目标和参考答案要点
- [ ] 包含至少1-2个前沿/开放性问题
- [ ] 行为面试题与该方向的典型工作场景相关
- [ ] 调研来源可靠，避免过时或低质量信息
