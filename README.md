# lychee

## 跨学科实验创新发现

`experiment-innovation` 是一个通过跨学科机制迁移寻找实验创新点的 Agent Skill，适用于课程、科研和工程实验，也支持评审已有想法、设计验证实验与提炼有证据的贡献。

### 工作方法

1. 将具体问题抽象为实体、关系、约束和失败条件。
2. 从自然科学、工程、社会科学、人文、艺术和技艺中寻找可借用的规则或表示，主动探索远距离来源。
3. 明确源与目标的对应、必要前提和关键失配，并与目标领域的已有方法比较。
4. 提出可支持或否定假设的最小实验，区分计划、探索性观察和已验证结果。

学科距离与陌生术语本身不构成创新证据；真实新颖性与有效性需要针对具体课题进一步核查。

### 使用

- [浏览技能文件](skills/experiment-innovation/SKILL.md)
- [下载完整技能 ZIP](dist/experiment-innovation.zip)

解压后，将整个 `experiment-innovation` 文件夹放入所用代理支持的技能目录。例如，Codex 项目可使用 `.agents/skills/experiment-innovation/`。

调用示例：

```text
$experiment-innovation 从看似无关的学科为这个实验寻找创新点，保留一个大胆方向，说明映射、失配和验证方法。
```

提供实验目标、现有方案、必须保留的条件、可用资源和期限，能够让输出更具体。

### 目录

```text
skills/experiment-innovation/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── cross-disciplinary-discovery.md
    ├── mechanism-atlas.md
    ├── innovation-patterns.md
    ├── validation-design.md
    └── output-templates.md

dist/experiment-innovation.zip
```
