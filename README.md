# 中文问卷分析 Skill

审计并分析已收集的结构化问卷或汇总表，结合抽样、题目、缺失和权重解释分布、分组差异、开放题与决策边界。

## 适合处理

- 满意度、NPS、概念测试、需求和追踪问卷
- 原始逐行数据或带题目、基数和计数的汇总表
- 分群比较、效应区间、权重与稳健性分析
- 开放题主题和定量结果的有边界整合

本 Skill 不负责设计新问卷、纯访谈分析或实验结果解读，也不会从横截面相关关系宣称因果。

## 使用

在 Codex 中直接调用：

```text
$measure-survey-analysis-cn 分析这份问卷，并区分样本内结果、总体推断、限制和决策建议。
```

安装到个人 Skill 目录的一种方式：

```bash
git clone https://github.com/fengxinbo558/measure-survey-analysis-cn.git ~/.codex/skills/measure-survey-analysis-cn
```

若目标目录已经存在，请先自行检查，不要直接覆盖。

## 内容

- `SKILL.md`：主入口、方法审计、分析流程与证据边界
- `agents/openai.yaml`：中性中文 UI 元数据
- `references/TEMPLATE.md`：完整输出模板
- `references/EXAMPLE.md`：有边界的问卷分析示例
- `evals/`：触发与行为样例

## 验证与来源

本仓库版本已通过结构、安全、链接和隔离安装检查。来源和修改边界见 `UPSTREAM.md`，适用许可证原文见 `LICENSE.upstream`；这些文件属于法律与诚实溯源记录，不应删除。
