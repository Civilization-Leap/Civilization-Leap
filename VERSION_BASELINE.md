# 文明跃迁当前有效基线 · VERSION BASELINE

**状态日期：2026-09-24**

本文件是主仓库的版本导航页，用于防止旧文件、旧仓库或较大版本号被误当成现行总基线。

---

## 1. 总规则

### 权威顺序

带有以下标识的现行文件优先：Canonical、MASTER、FROZEN、明确标记为“当前权威稿 / current authoritative baseline”的文件。

旧版本用于追溯，不得反向覆盖当前有效基线。

### 不采用“数字越大越权威”

不同项目存在不同版本治理方式。

尤其：**AGI-COS 不存在单一最新版。** 必须按轨道与适用相位判断。

---

## 2. 文明跃迁五卷书

当前母稿：**v1.21-R10.10**

思想生命收口状态：**PASS**

冻结书名：

1. 《被需要的文明》
2. 《制度前语言》
3. 《文明跃迁白皮书》
4. 《文明永续》
5. 《意义涌现》

功能：**为什么必须改变，以及哪些边界不能失守。**

---

## 3. 《活的文明》三部曲

冻结总名：**《活的文明》**

冻结卷名：

1. 《未来文明运行原理》
2. 《未来文明的真实生活》
3. 《新文明的形成》

功能：**如何运行、如何生活、如何形成。**

与五卷书是功能分工关系，不是新版覆盖旧版关系。

---

## 4. 目标、目的与伦理生成

### 理论母版

**《从人类文明逻辑到 AGI：目标、目的与伦理生成》V1.1 FROZEN**

地位：上游理论母版。

### 学术版

**《AGI真正的问题，不只是如何控制，而是它应该追求什么——从目标对齐到目的生成》V1.1**

地位：学术定位与命题加固候选稿。

学术版可以改善文献关系、学术定位、命题强度、可检验性和专业停止点；但不能未经上游受控修订，悄悄改写 FROZEN 母版核心方向。

### Professional English research line

**Beyond Alignment and Control V1.1**

Permanent DOI：https://doi.org/10.5281/zenodo.22858094

GitHub living entry：[research/beyond-alignment-and-control/](research/beyond-alignment-and-control/)

---

## 5. 公众版《当AI越来越强，我们怎样为自己打算？》

当前公众论证与答疑版：**V1.2**

状态：官网完整阅读已上线；十一问连续阅读主链 Q1—Q11 已形成；第一轮公众传播 COMPLETE；真实反馈独立监测，不以平台数据冒充理论验证。

阅读地图：https://www.civitas.top/public/reading/ai-self-interest/map.html

---

## 6. AGI-COS

治理方式：**跨版本不变量 + 多轨道受控版本族**

主要轨道包括危机操作、感知/认知安全、文明免疫/协调、技术接口、后AGI稳定、星际、超长期研究、限制/政策表达。

重要连续性：1.0 的危机操作核心没有因为 3.0 / 4.0 出现而自动失效；1.1 的感知审计仍是高后果判断的重要基础；其余版本按轨道与相位适用。

主仓库不公开私有工程源，不把内部仓库链接作为公众有效入口。

---

## 7. Human-COS

### Public Core

Public repository：https://github.com/Civilization-Leap/human-cos-public-core

当前公开表面：S0/S1 reproducibility baseline；Frozen Contract / Protocol Registry + 9 Schemas；具体能力边界以该仓库当前 README、release 与 provenance 为准。

### FFT-1 Public Mock Trial

Public repository：https://github.com/Civilization-Leap/human-cos-fft1-trial

当前公开试验制品：fixed Mock S5→S8 narrow chain；preview.2 public artifact；用于复现、边界、证据与 false-success 测试。

它不自动代表私有 runtime 当前最高工程状态、真实案例有效性、完整 Human-COS 已完成或理论已被独立验证。

---

## 8. CI-001

Public repository：https://github.com/Civilization-Leap/ci-001

- Stable：**V1.4**
- Review track：**V1.5-RC2 prerelease**

RC2 是公开评审候选，不等于 V1.5 已成为正式 stable。

---

## 9. Competition–Cooperation Mechanisms

Public repository：https://github.com/Civilization-Leap/computable-cooperation-mechanisms

- Latest published release：**v0.1.1**
- DOI：https://doi.org/10.5281/zenodo.22656544

---

## 10. Emergent Meaning Cosmology

Public repository：https://github.com/Civilization-Leap/Emergent-Meaning-Cosmology

Permanent DOI：https://doi.org/10.5281/zenodo.18833846

它是意义研究 / 宇宙论深研分支，不作为整个文明跃迁体系的唯一解释基础。

---

## 11. 网站与 GitHub 主仓库

### civitas.top

https://www.civitas.top/

定位：公众阅读中心、学术入口、公开文库、体系全景与专题传播。

### Civilization-Leap/Civilization-Leap

定位：**GitHub 理论体系总门户 / 项目索引 / 版本导航 / 子仓库续读目的地**。

它不是当前全部工程源码的合并仓库，也不是某个单一子项目的实现仓库。

---

## 12. 早期仓库与历史材料

早期“文明 OS”“大过滤器”“社会熵减”“ERP”“圆梦园”“雄安文明OS”等表达与工程探索可以保留用于追溯。

但除非在本文件或相应现行项目 README 中重新确认：**历史存在 ≠ 当前有效基线。**

---

## 13. 版本冲突怎么办

如果发现两个文件都声称自己是“最新”：

1. 先看是否属于不同轨道；
2. 看是否有 FROZEN / MASTER / Canonical；
3. 看本页是否登记了现行地位；
4. 看子仓库自己的 release / provenance；
5. 仍无法判断时，开 Issue 标记 baseline ambiguity，不要自行用版本号大小裁决。