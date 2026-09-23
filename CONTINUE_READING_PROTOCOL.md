# 子仓库续读与返回总体系协议 · CONTINUE READING PROTOCOL

**Version: 1.0｜2026-09-24**

目的：让每个专业子仓库保持独立可理解，同时在读者需要更大上下文时，能够稳定返回文明跃迁总体系。

这不是 SEO 互链规则，也不是要求所有仓库把 README 写成同一种文风。

---

## 1. 适用范围

适用于文明跃迁体系的公开 GitHub 子仓库与公开研究目录，包括 Human-COS public surfaces、CI-001、CCM、Emergent Meaning Cosmology、AGI / purpose generation research repositories，以及后续公开专业研究仓。

私有工程仓不要求公开添加入口。

---

## 2. 每个公开子仓库 README 最低应有

### A. 本仓库是什么

必须能独立说明当前项目的 research question / 工程问题、当前公开范围，以及当前不证明什么。

### B. 本仓库与文明跃迁的关系

只需一句到两句，不要求接受总理论才能使用子项目。

推荐英文：

> This repository studies one specific problem within the wider Civilization Leap research program. You do not need to accept the wider framework to reproduce, criticize, falsify, or reuse this project within its stated license.

推荐中文：

> 本仓库只研究文明跃迁体系中的一个具体问题。使用、复现、批评、证伪或在许可范围内复用本项目，不要求先接受完整文明跃迁理论。

### C. Continue exploring / 继续阅读

README 末尾应提供稳定返回入口。

---

## 3. 标准页脚模板

### Continue exploring / 继续阅读

This repository covers one specific research surface. It does not by itself validate the wider Civilization Leap theory.

- **Civilization Leap main map / 理论体系总门户：** https://github.com/Civilization-Leap/Civilization-Leap
- **Current version baseline / 当前有效版本：** https://github.com/Civilization-Leap/Civilization-Leap/blob/main/VERSION_BASELINE.md
- **Research index / 研究索引：** https://github.com/Civilization-Leap/Civilization-Leap/blob/main/RESEARCH_INDEX.md
- **Public website / 文明跃迁网站：** https://www.civitas.top/
- **Public library / 公开文库：** https://www.civitas.top/library/

Agreement with the wider framework is not required to test or criticize this project.

---

## 4. 可选的相关研究区

子仓库可以在标准页脚前增加最多 3 个真正相关项目。

例如 Human-COS 可以连接 CI-001、AGI goal / purpose research 与 CCM。

但不要机械把全部仓库列一遍。

原则：**只链接读者下一步最可能真的需要的内容。**

---

## 5. 禁止产生的暗示

页脚不得暗示：子项目通过测试等于文明跃迁理论被验证；主仓库是子项目的技术认证机构；文明跃迁方向判断等于工程通过标准；某 DOI / 论文发表等于整个体系被同行验证；加入主仓库等于成为组织成员；公开 repo 等于同意全部理论。

---

## 6. 本地优先原则

每个子仓库自己的 README、RELEASE_STATUS、LICENSE、SECURITY、provenance、versioning 与 test evidence，对该子项目的具体事实具有优先解释权。

主仓库只负责总地图与跨项目版本导航，不应覆盖本地事实。

---

## 7. 历史仓库

历史 / 早期实验仓库如果继续公开，应在 README 显眼位置增加：

> **Historical / Early Experimental Repository**
> This repository is retained for provenance and historical traceability. It is not the current authoritative baseline of the Civilization Leap theory or implementation program.

中文：

> **历史 / 早期实验仓库**
> 本仓库保留用于工程与思想演化追溯，不代表当前文明跃迁理论或实施方案的权威基线。

---

## 8. 更新纪律

当主仓库路径不变时，子仓库不需要因总体系内部版本变化频繁修改页脚。

只有以下情况需要改：主门户 URL 改变；研究索引路径改变；子仓库自身定位变化；子仓库从 active 变成 historical / archived；出现更直接的上游 / 下游研究入口。