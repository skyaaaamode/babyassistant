# babyassistant · 育儿工具箱

> 此稿为占位 README(M15),推送 GitHub 时改名 `README.md` 落在仓库根。
> 注意:不含自用服务器地址;截图与在线链接待 Pages 上线后补。

---

**babyassistant** 是一套面向家长的开源育儿工具箱:每个工具一个独立模块,按需取用,不做一体化大应用。数据全部存在你自己的浏览器本地,无账号、无上传。

## 正在做:第一个模块——宝宝疫苗百科

- 📅 **接种排期**:基于宝宝生日生成全程接种计划,剂次建议日期与最早/最晚窗口期,临近提醒与延期警示
- 💊 **品牌程序对比**:同一疫苗不同品牌(国产/进口)的剂次数与时间窗差异,自选品牌后排期自动重算
- 🧬 **人体守护可视化**:基于真实解剖数据(BodyParts3D)的 3D 人体,直观展示每支疫苗守护哪些部位、接种进度如何点亮守护
- 📖 **家长视角百科**:大白话解释每支疫苗防什么病、反应有多常见,接种记录与医嘱逐剂归档

## 路线图

| 阶段 | 模块 | 状态 |
|---|---|---|
| 1 | 疫苗百科 | 🔨 开发中 |
| 2 | 生长曲线(WHO 标准,身高/体重/头围) | 计划中 |
| 3 | 喂养 / 睡眠记录 | 计划中 |
| 4 | 发育里程碑 + 育儿知识 | 计划中 |
| 5 | 健康事件(用药/生病日记/体检) | 计划中 |

## ⚠️ 免责声明

本项目所有疫苗与医学信息**仅供参考,不构成医疗建议**。接种安排、品牌选择与异常反应处理,请以接种门诊和医生的意见为准。

## 如何参与

正式开源前本仓库为占位,暂不接收 PR。欢迎先提 Issue:

- 报医学数据问题(剂次/时间窗/间隔),请附权威来源(药品说明书、国家免疫规划文件、WHO/CDC)
- 功能建议与 bug 描述请尽量带宝宝月龄与所用浏览器

## 许可

- 代码:MIT
- 疫苗数据文件:CC-BY-4.0(正式开源时生效,清单见 DATA-LICENSE.md)
- 3D 解剖模型:衍生自 [BodyParts3D](https://lifesciencedb.jp/bp3d/)(©DBCLS, CC-BY 4.0),详见 THIRD_PARTY_NOTICES.md

---

# babyassistant · An Open-Source Parenting Toolbox

**babyassistant** is a set of independent, open-source tools for parents. Every tool is a standalone module; all data stays in your own browser — no accounts, no uploads.

**Now in development — first module: Baby Vaccine Companion.** It generates a full vaccination schedule from your baby's birthday (with earliest/latest windows per dose), compares brand-specific regimens (domestic vs. imported), keeps per-dose records with doctor notes, and visualizes which body systems each vaccine guards via a 3D anatomy viewer built on BodyParts3D data.

**Roadmap:** vaccines → growth curves (WHO standards) → feeding & sleep logs → development milestones + parenting knowledge → health events.

**⚠️ Disclaimer:** All medical information is for reference only and is not medical advice. Always follow your clinic and physician.

**Contributing:** Issues are welcome before the code lands — medical-data reports must cite an authoritative source (product insert, national immunization program, WHO/CDC).

**Licenses:** Code under MIT; vaccine data files under CC-BY-4.0 (effective at open-sourcing); 3D anatomy derived from BodyParts3D (©DBCLS, CC-BY 4.0).
