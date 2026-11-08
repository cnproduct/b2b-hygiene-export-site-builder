# 卫生用品与医护无纺布出海标准、技术参数与 MA-DPP 规约

## 1. 行业覆盖与典型客户站点
- `leohygiene.com` (利奥卫生用品 - 成人失禁护理、医用护理垫)
- `shdhygiene.com` (泉州盛鸿达 - 婴儿纸尿裤、经期裤、拉拉裤 OEM)
- `chinabaronhygiene.com` (男爵卫生用品 - 医护级母婴个护出口)
- `huifengsanitary.com` (汇丰卫浴五金与卫生耗材)

## 2. 国际标准与准入认证对照
- **美洲准入**：FDA 510(k) 豁免/登记、ASTM F1670/F1671 (血液/病毒穿透)、CPSC 无毒测试。
- **欧洲准入**：CE MDR (EU 2017/745 Class I 医用器械)、OEKO-TEX Standard 100 Class I (婴幼儿皮肤接触级)、ISO 13485 医疗器械质保体系、ISO 9001。
- **环保与社会责任**：FSC 森林产销监管链认证 (Fluff Pulp 木浆来源)、BSCI / Sedex 验厂代码。

## 3. 核心物理参数与实测真理锚点
- **吸水量 (Absorbency Capacity / CRC)**：$\ge 800\text{ ml}$ (婴儿夜用) / $\ge 2500\text{ ml}$ (成人重度失禁)。
- **回渗量 (Rewet / Strike-Through)**：$\le 0.5\text{ g}$ (80 ml 生理盐水加压 $0.5\text{ psi}$ 测试)。
- **渗透吸收速度 (Absorption Speed)**：第一轮 $\le 15\text{ s}$，第二轮 $\le 25\text{ s}$。
- **透气膜水汽透过率 (MVTR / Breathability)**：$\ge 3500\text{ g/m}^2/24\text{h}$。
- **微生物限度 (Bioburden)**：细菌菌落总数 $< 20\text{ CFU/g}$，真菌菌落总数 $< 10\text{ CFU/g}$，致病菌零检出。

## 4. MA-DPP 欧盟数字产品护照与循环规范 (EU ESPR)
每个卫生用品/母婴个护落地页（`/dpp-diaper-{sku}`）必须静态声明：
- **原材料构成比**：无氯漂白高吸水木浆 (Fluff Pulp, FSC 认证, ~42%)、住友/三井高吸水性树脂 (SAP, ~38%)、亲水 ES 热风无纺布 (~12%)、可降解透气底膜 (PLA/PE 复合, ~8%)。
- **微塑料与全生命周期循环**：符合 EU Single-Use Plastics Directive (SUPD) 标签规范。
- **独立 Sitemap 契约**：生成 `sitemap-dpp.xml` 并在页面注入 `rel="canonical"` 自引用契约。
