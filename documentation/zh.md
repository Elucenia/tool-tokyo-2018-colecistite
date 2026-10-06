<!-- ELUCENIA technical documentation · tokyo-2018-colecistite · zh · no clinical/professional/rights approval -->

# 急性胆囊炎严重程度（Tokyo 2018）

[条件、来源与许可](https://elucenia.org/zh/tools/tokyo-2018-colecistite)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### III 级 · 心血管：低血压需多巴胺 ≥ 5 µg/kg/min 或任何剂量去甲肾上腺素

`cardio`

### III 级 · 神经：意识水平下降

`neuro`

### III 级 · 呼吸：PaO₂/FiO₂ \< 300

`resp`

### III 级 · 肾脏：少尿或肌酐 \> 2.0 mg/dL

`renal`

### III 级 · 肝脏：INR \> 1.5

`hepat`

### III 级 · 血液：血小板 \< 100000/mm³

`hemato`

### II 级 · 白细胞 \> 18000/mm³

`leuco`

### II 级 · 右上腹可触及痛性肿块

`massa`

### II 级 · 症状持续超过 72 小时

`tempo`

### II 级 · 明显局部炎症（坏疽、胆囊周围或肝脓肿、胆汁性腹膜炎、气肿性胆囊炎）

`local`

## 方法版本

Tokyo Guidelines 2018/Yokoe（保留TG13标准）：严重程度I–III；6种器官功能障碍中任一项即为III级；均无时，4项中度标准中任一项即为II级

## 已记录的公式

III级（重度）：存在任一列明的器官功能障碍。

II级（中度）：无III级器官功能障碍，且符合四项II级标准中的任一项：白细胞 \> 18000/mm³；右上腹可触及的压痛性肿块；症状持续超过72小时；或显著局部炎症。

I级（轻度）：胆囊炎患者不符合II级或III级标准。

## 限制与适用人群

TG18/TG13版本保留此前的诊断及严重程度标准。分类需要完整的临床和实验室定义；管理文件具有其他条件，应分别考虑，不能仅凭类别推断处理方案。 TG18表7规定，在无III级功能障碍时，四项所列标准中的任一项即可满足II级，而非仅限显著局部炎症。本次核查测试的是已确诊胆囊炎病例中已经勾选的体征，不测试体征的临床判定、实验室界值、诊断资格或处理方案。

## 参考文献

- [Yokoe M et al. Tokyo Guidelines 2018: diagnostic criteria and severity grading of acute cholecystitis (with videos). J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.515)

- [Okamoto K et al. Tokyo Guidelines 2018: flowchart for the management of acute cholecystitis. J Hepatobiliary Pancreat Sci, 2018.](https://doi.org/10.1002/jhbp.516)

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

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

I级（轻度）：无 II 级或 III 级标准

| 结果详情 | |
| --- | --- |
| 建议处理（TG18） | 如手术风险允许，尽早行腹腔镜胆囊切除术。 |


### 2

II级（中度）：明显局部炎症

| 结果详情 | |
| --- | --- |
| 建议处理（TG18） | 如手术风险允许，在有经验的中心尽早行腹腔镜胆囊切除术；否则，内科治疗，必要时引流。 |


### 3

II级（中度）：明显局部炎症

| 结果详情 | |
| --- | --- |
| 建议处理（TG18） | 如手术风险允许，在有经验的中心尽早行腹腔镜胆囊切除术；否则，内科治疗，必要时引流。 |


### 4

III级（重度）：伴器官功能障碍的急性胆囊炎

| 结果详情 | |
| --- | --- |
| 建议处理（TG18） | 器官支持和抗生素；仅在有经验的中心且条件有利时才可早期胆囊切除，否则需紧急或早期胆囊引流。 |

