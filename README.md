# cs-research

面向实验型计算机研究的 Codex skill，涵盖方向判断、方法设计、实验探索、SOTA 比较、论文写作和科研绘图。适用于算法、机器学习与系统等研究。

它沉淀了研究中的判断原则：用任务困难确定问题，用强基线识别有效信息，以有针对性的实验建立贡献，并把机制与发现写清楚。具体工具技巧按需要读取。

## 内容

| 文件 | 内容 |
|---|---|
| [SKILL.md](SKILL.md) | 技能入口与核心判断原则 |
| [方向与方法设计](references/directions.md) | 问题定位、技术角色、强基线与机制选择 |
| [实验判断](references/experiments.md) | 比较条件、实验投入、归因、稳定性与成本 |
| [学习模型专项](references/learning-models.md) | 训练对照、目标、表示、蒸馏、生成与检索 |
| [实验运行](references/execution.md) | 资源、缓存、数值实现与结果恢复 |
| [论文写作](references/writing.md) | 问题与设计的论证、信息层级、实验分析与排版 |
| [科研绘图](references/figures.md) | SVG、矢量公式、框架图、统计图与出版输出 |

## 安装

将仓库克隆到 Codex 的 skills 目录：

```bash
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
git clone https://github.com/licpp/cs-research-skill.git "${CODEX_HOME:-$HOME/.codex}/skills/cs-research"
```

## 使用

在研究任务中调用 `$cs-research`，例如：

```text
使用 $cs-research，阅读当前论文、代码和实验结果，判断最值得继续的方向。
```

```text
使用 $cs-research，分析当前方法的增益来源，设计最有针对性的对照实验。
```

```text
使用 $cs-research，改善论文的研究主线、设计动机和实验分析，保持技术事实不变。
```

```text
使用 $cs-research，以 SVG 绘制论文框架图，导出矢量 PDF，并按最终栏宽检查可读性。
```

技能入口保持简洁，各专题指南按当前研究问题读取。
