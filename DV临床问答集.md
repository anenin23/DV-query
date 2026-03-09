# 维迪西妥单抗（DV）临床问答集

> 内部参考资料 | v1.1 | 2026-03-09
>
> **版本历史**
> - v1.0 2026-03-08 — 初始版本，Q1-Q3（剂量换算、C016亚组OS）
> - v1.1 2026-03-09 — 新增 Q4（DECIDING-I 分期/放疗 vs HOPE-03）

## 目录

- Q1：为什么国内DV剂量是2.0 mg/kg，而全球G001研究用1.5 mg/kg？
- Q2：RC48-C016中UBC亚组中位OS比UTUC短，合并后中位OS却等于UTUC？
- Q3：为什么UBC的中位OS比UTUC短？
- Q4：DECIDING-I 研究入组患者的 T 分期分布和放疗剂量如何？与 HOPE-03 有何区别？

---

## Q1：为什么国内DV剂量是2.0 mg/kg，而全球G001研究用1.5 mg/kg？

**背景**：国内尿路上皮癌研究（RC48-C005、C009、C016、C017等）DV剂量均为2.0 mg/kg，但全球III期研究DV-001（G001）采用1.5 mg/kg，临床专家常对此提出疑问。

**解答**：两个剂量本质上是同一实际剂量，差异来源于蛋白浓度测定所用消光系数（Extinction Coefficient，EC）标准不同。

| 项目 | 中国 | 中国以外 |
|------|------|---------|
| EC标准 | BSA-based EC | DV-based EC |
| 标称剂量 | 2.0 mg/kg | 1.5 mg/kg |
| 特点 | 基于牛血清白蛋白（BSA）标准曲线，测出浓度数值偏高 | 基于药物本身理论消光系数，更准确反映实际蛋白含量 |

**换算**：DV-based dose = BSA-based dose × (1.07 ÷ 1.41) = 2.0 × 0.759 ≈ 1.52 ≈ 1.5 mg/kg
- 1.07 = BSA-based EC（牛血清白蛋白的消光系数）
- 1.41 = DV-based EC（维迪西妥单抗自身的理论消光系数）

**结论**：两个剂量本质上是同一实际剂量，患者接受的药物暴露量完全一致，差异仅是分析方法学造成的数值差异。G001采用DV-based EC是为了与国际药物分析标准接轨。

---

## Q2：RC48-C016中UBC亚组中位OS比UTUC短，合并后中位OS却等于UTUC？

**背景**：RC48-C016（NCT05302284）DV+特瑞普利单抗臂OS亚组分析数据：

| 亚组 | 人数 | 事件数 | 中位OS |
|------|------|--------|---------|
| UTUC（上尿路尿路上皮癌） | 111 | 37（33%） | 31.5个月 |
| UBC（膀胱尿路上皮癌） | 130 | 44（34%） | 23.2个月 |
| 总体 | 243 | 81（33%） | 31.5个月 |

两组人数接近，一个31.5个月、一个23.2个月，合并后中位OS为何仍是31.5个月？

**解答**：中位OS的定义是Kaplan-Meier曲线首次降至50%时对应的时间点，取决于第50%患者所在的位置，不能像平均数一样加权计算。

UBC组中位OS为23.2个月，但该时间点之后生存曲线趋于平坦。本次为中期分析（信息分数62%），事件率仅约33%，大量患者在数据截止时仍存活。UBC组在23.2个月降至50%后，至31.5个月期间仅发生少数事件，存活率缓慢降至约47%~48%。

两组合并后，在31.5个月时间点：
- UTUC组约50%存活（约55~56例）
- UBC组约47%~48%存活（约62例）
- 合计约117~118/241 ≈ 49%，接近50%

合并后KM曲线在31.5个月附近穿越50%线，因此报告中位OS为31.5个月。

**小结**：中位数反映的是排列位置而非加权均值。UBC组虽然更早跨过50%线，但此后曲线极为平坦，合并后对总体中位数的拉低作用有限。

---

## Q3：为什么UBC的中位OS比UTUC短？

**背景**：同Q2数据，DV+T臂UTUC中位OS 31.5个月 vs UBC中位OS 23.2个月，差距8.3个月。

**解答**：首先对比化疗组数据：

| 亚组 | 化疗组中位OS |
|------|-------------|
| UTUC | 16.9个月 |
| UBC | 16.5个月 |

化疗组两亚组中位OS几乎相同，说明差异并非源于疾病本身的预后差异，而可能与对DV+T治疗的反应差异有关。

**可能原因**：
1. 亚组分析的随机波动：两组HR非常接近（UTUC 0.53 vs UBC 0.55），治疗相对效果一致，绝对中位OS差异可能包含统计随机波动
2. 基线特征差异：UTUC和UBC患者在内脏转移率、ECOG评分等方面可能存在未被完全调整的分布差异

**要点**：HR是衡量治疗效果的核心指标，中位OS的绝对值受曲线形状、删失模式及随访时间影响较大。两个亚组HR高度重叠（0.53 vs 0.55），表明DV+T在UTUC和UBC中的治疗获益一致。当前为中期分析数据，随着随访延长，绝对值可能发生变化。

---

## Q4：DECIDING-I 研究入组患者的 T 分期分布和放疗剂量如何？与 HOPE-03 有何区别？

**背景**：DECIDING-I 是一项探索维迪西妥单抗联合特瑞普利单抗和放疗用于 HER2 过表达 MIBC 保膀胱治疗的概念验证研究（n=6）。临床团队常需了解入组人群特征和放疗方案细节，并与同为 RC48+免疫的 HOPE-03 研究进行比较。

**解答**：

**1. T 分期分布**

根据 Supplementary Table 1，6 例患者的临床分期如下：

| 分期 | 例数 | 比例 |
|------|------|------|
| cT2N0M0 | 5 | 83.3% |
| cT3N0M0 | 1 | 16.7% |

入组标准允许 cT2-4a，但实际入组以 T2 为主。唯一的 T3 患者（HER2 3+）最终也达到 CR。

**2. DECIDING-I 放疗方案**

采用两阶段根治性放疗，在第 2-3 周期与药物同步启动：

| 阶段 | 靶区 | 剂量 | 分割 |
|------|------|------|------|
| Phase 1 | 全膀胱 ± 盆腔淋巴结 | 46 Gy | 23 次，2 Gy/次，每周 5 次 |
| Phase 2（boost） | 局部或全膀胱 | 追加至总剂量 50-60 Gy | 局部：14 Gy/7f；全膀胱：额外 2f |

总剂量 >50 Gy，与传统保膀胱 TMT 方案的标准根治性剂量（60-66 Gy）基本一致。

**3. 与 HOPE-03 放疗的区别**

| | DECIDING-I | HOPE-03 |
|---|---|---|
| 治疗策略 | 保膀胱 | 新辅助 |
| 放疗角色 | 核心治疗，所有患者必须接受 | 可选路径，仅保膀胱者接受 |
| 放疗时序 | 同步（concurrent），第 2-3 周期起 | 序贯（sequential），新辅助结束后 |
| 放疗剂量 | 方案明确规定：总剂量 50-60 Gy | 方案全文未规定具体剂量 |

HOPE-03 研究方案（V3.0）全文均未出现放疗剂量的具体数字，仅在流程图中标注"根治性放疗"，放疗细节留给各中心按指南自行决定。

**小结**：DECIDING-I 入组以 T2 患者为主（83.3%），放疗是方案核心，采用标准根治性剂量（50-60 Gy）；HOPE-03 的放疗为新辅助后的可选路径，方案未规定具体剂量。两者的核心区别在于治疗策略不同：DECIDING 是"药物+放疗替代手术"，HOPE 是"药物缩瘤后再选择手术或放疗"。

---

## 参考文献

1. Sheng X, Yan X, Wang L, et al. Disitamab Vedotin plus Toripalimab versus Chemotherapy in HER2-Expressing Advanced Urothelial Cancer: A Randomized Phase III Trial (RC48-C016). *N Engl J Med*. 2025.（NCT05302284）
2. Powles T, et al. RC48G001: Disitamab Vedotin in Previously Treated HER2-Expressing Advanced Urothelial Cancer. LBA631, 2026 ASCO GU.
3. Kaplan EL, Meier P. Nonparametric estimation from incomplete observations. *J Am Stat Assoc*. 1958;53(282):457-481.
4. Zhang L, Jin D, Zang J, et al. Disitamab vedotin combined with toripalimab and radiotherapy for multimodal organ-sparing treatment of muscle invasive bladder cancer: a proof-of-concept study. *Neoplasia*. 2025;68:101216.
5. Wen F, Lin T, Zhang P, Shen Y. RC48-ADC combined with tislelizumab as neoadjuvant treatment in patients with HER2-positive locally advanced muscle-invasive urothelial bladder cancer: a multi-center phase Ib/II study (HOPE-03). *Front Oncol*. 2024;13:1233196.
