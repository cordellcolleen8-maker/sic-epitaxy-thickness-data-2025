# 2025 年数学建模竞赛 B 题：碳化硅外延层厚度数据

本仓库整理 2025 年高教社杯全国大学生数学建模竞赛 B 题“碳化硅外延层厚度的确定”提供的四份红外干涉光谱实测数据，用于数据查阅与后续建模分析。

## 数据文件

| 文件 | 晶圆片 | 入射角 | 说明 |
| --- | --- | ---: | --- |
| `data/附件1.xlsx` | 碳化硅 | 10° | 同一块碳化硅晶圆片的测试结果 |
| `data/附件2.xlsx` | 碳化硅 | 15° | 同一块碳化硅晶圆片的测试结果 |
| `data/附件3.xlsx` | 硅 | 10° | 同一块硅晶圆片的测试结果 |
| `data/附件4.xlsx` | 硅 | 15° | 同一块硅晶圆片的测试结果 |

每份数据包含 7,469 条记录，波数范围约为 399.6747–4000.122 cm⁻¹。原始工作簿中的列为：

- `波数 (cm-1)`：波数，单位为 cm⁻¹。
- `反射率 (%)`：干涉光谱反射率，单位为百分比。

## 数据来源与引用

数据来自 2025 年全国大学生数学建模竞赛 B 题附件。相关方法背景可参考：

> Zhentao Li, Xiang Zhong, Jing Zhong, Xinge Liu. *High-Throughput full-spectrum characterization of semiconductor thin films via AD-accelerated physics-informed inversion: Demonstrations in Si and SiC epitaxy*. Journal of Alloys and Compounds. DOI: [10.1016/j.jallcom.2026.190602](https://doi.org/10.1016/j.jallcom.2026.190602)

论文原文 PDF 未随本仓库分发；请通过 DOI 获取正式出版版本并遵守相应许可与版权要求。

## 说明

仓库保留四份 Excel 原始数据，不修改单元格内容，也不包含论文 PDF、建模代码或分析结果。
