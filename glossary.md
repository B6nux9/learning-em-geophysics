# 术语表（Glossary）

> **本课程铁律：遇到缩写，不猜，去查。**
> 每个缩写记三样：缩写 = 全称（逐词）= 一句话含义。
> 建立此表的直接原因：学习者三次在缩写字面上栽跟头（TE/TM 的 T 猜成 Transient、
> GPR 的 G 猜成 Geographic），而"讲得通"恰恰是陷阱——错误的猜测会像真的一样嵌进知识网络。

---

## 方法与缩写

| 缩写 | 全称（逐词） | 一句话含义 | 出处 |
|---|---|---|---|
| **EM** | **E**lectro**M**agnetic | 电磁（法） | L01 |
| **TEM** | **T**ransient **E**lectro**M**agnetic | **瞬变**电磁法；时间域，电流关断后测二次场衰减 | L01 |
| **TDEM** | **T**ime-**D**omain **E**lectro**M**agnetic | 时间域电磁法，TEM 的同义写法 | L01 |
| **FDEM** | **F**requency-**D**omain **E**lectro**M**agnetic | 频率域电磁法 | L01 |
| **SOTEM** | **S**hort-**O**ffset **T**ransient **E**lectro**M**agnetic | 短偏移距瞬变电磁法；接地导线源，收发距≈1–3倍探测深度 | L01 |
| **LOTEM** | **L**ong-**O**ffset **T**ransient **E**lectro**M**agnetic | 长偏移距瞬变电磁法 | L01 |
| **ATEM** | **A**irborne **T**ransient **E**lectro**M**agnetic | 全航空瞬变电磁法；收发都在飞行平台 | L01 |
| **SATEM** | **S**emi-**A**irborne **T**ransient **E**lectro**M**agnetic | 半航空瞬变电磁法；地面发射、空中接收 | L01 |
| **MT** | **M**agneto**T**elluric | 大地电磁法；天然场源、频率域 | L01 |
| **AMT** | **A**udio-frequency **M**agneto**T**elluric | 音频大地电磁法；MT 的高频版 | L01 |
| **CSAMT** | **C**ontrolled-**S**ource **A**udio-frequency **M**agneto**T**elluric | 可控源音频大地电磁法；人工源、频率域 | L01 |
| **WEM** | **W**ide-field **E**lectro**M**agnetic method（广域电磁法，何继善） | 极低频人工源、频率域、大深度大范围 | L01 |
| **GPR** | **G**round **P**enetrating **R**adar | **探地雷达**；朝地下打的雷达，工作在波动区，测反射 | L02 |
| **MCSEM** | **M**arine **C**ontrolled-**S**ource **E**lectro**M**agnetic | 海洋可控源电磁法；海上油气直接烃类检测 | L02 |
| **ELF** | **E**xtremely **L**ow **F**requency | 极低频（约 3–3000 Hz 一段）；穿透海水/地下，潜艇通信 | L02 |

## 极化模式（注意：这里的 T 是 Transverse 横向，不是 Transient！）

| 缩写 | 全称（逐词） | 一句话含义 | 出处 |
|---|---|---|---|
| **TE** | **T**ransverse **E**lectric | 横电模式 / E 极化；电场平行走向 | （第 06、09 课细讲） |
| **TM** | **T**ransverse **M**agnetic | 横磁模式 / H 极化；磁场平行走向 | （第 06、09 课细讲） |

> **同一个字母 T，两套体系两个意思：TEM 里是 Transient（瞬变），TE/TM 里是 Transverse（横向）。**

## 物理量与概念

| 术语 | 英文 | 一句话含义 | 出处 |
|---|---|---|---|
| 电阻率 | resistivity, ρ | 材料阻碍电流的能力；地下变化跨 13 个数量级 | L01 |
| 电导率 | conductivity, σ = 1/ρ | 电阻率的倒数 | L01 |
| 视电阻率 | apparent resistivity, ρₐ | 按均匀半空间公式反算的等效电阻率（非真值） | L01 |
| 地层因子 | **F**ormation **F**actor, F = ρ₀/ρ_w | 岩石骨架把水电阻率放大的倍数；只与岩石几何有关 | L01 附录 |
| 电阻率指数 | Resistivity **I**ndex, I = ρ_t/ρ₀ | 部分饱和相对全饱和电阻率涨的倍数；含烃指标 | L01 附录 |
| 趋肤深度 | skin depth, δ | 场衰减到 1/e 的深度；δ≈503√(ρ/f) | L03 |
| 传导电流 | conduction current, σE | 自由电荷真实流动，耗散成焦耳热 | L02 |
| 位移电流 | displacement current, ε∂E/∂t | 电场变化的等效电流，储能可回；波之所以存在的拼图 | L02 |
| 准静态近似 | quasi-static approximation | 忽略位移电流、只保留传导电流 | L02 |
| 损耗角正切 | loss tangent, tanδ = σ/(ωε) | ωε/σ 的倒数；判断波动/扩散 | L02 |
| 正演 | forward modeling | 由模型算数据（d = F(m)），适定 | L01 |
| 反演 | inversion | 由数据求模型（m = F⁻¹(d)），病态 | L01 |
| 先验（信息） | prior | 从数据之外注入的假设，用来在零空间里挑解 | L02 追问 |
| 零空间 | null space | 数据完全"沉默"、无法约束的那部分模型空间 | L02 追问 |
| 正则化 | regularization | 用先验在无穷多个符合数据的模型里挑一个 | L02 追问 |
| 阿尔奇公式 | Archie's law | 把电阻率翻译成含水/含油饱和度的经验公式 | L01 附录 |
