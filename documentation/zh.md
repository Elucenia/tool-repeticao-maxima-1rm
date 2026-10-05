<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · zh · no clinical/professional/rights approval -->

# 估算 1RM（Epley 与 Brzycki）

[条件、来源与许可](https://elucenia.org/zh/tools/repeticao-maxima-1rm)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 举起的重量

`carga`

kg · 范围: 1–500

### 力竭前完成的重复次数

`reps`

范围: 1–15

## 方法版本

Epley 重量×(1+重复次数/30)与Brzycki 1993 重量×36/(37−重复次数)；本地取平均；重复1次=重量

## 已记录的公式

Epley: 1RM = 重量 × (1 + 重复次数/30).

Brzycki: 1RM = 重量 × 36 ÷ (37 − 重复次数).

主要结果为两者平均值。重复1次时，该 重量就是1RM。

## 限制与适用人群

1RM 是根据以 kg 表示的负荷和完成至疲劳的完整重复次数得到的估计值，并非实测最大负荷。LeSuer 1997 在熟悉动作后研究了 67 名未经训练的大学生，涉及卧推、深蹲和硬拉，每组不超过 10 次。界面允许输入至 15 次，但该研究不支持外推至 11–15 次。误差随动作而异。Epley–Brzycki 均值是本地实现的选择，并非该研究验证的组合方程；结果不能保证最大负荷的安全性。

## 参考文献

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
