> 归档说明：本文为2026-11-20产生的2024历史资料审计。历史PDF/PNG未上传到GitHub；原稿末尾的写入状态是生成时的状态。此归档不修改当前SpacePort规范，也不证明旧设施已上线。

# VIRTURA 2114 / Digital Spaceport

## 2024 历史设计资料审计与 2026 三维网页空间重建建议

**审查日期**：2026-11-20  
**时段定义**：用户将本批资料归入约 2024-12-15 的设计阶段；不把导出文件日期、文中引用年份和设定中的未来年份混为一谈。  
**审查对象**：12 份 PDF，合计 **121 页**；1 张 DSVA.2114 / VIRTURA.2114 视觉拓扑图；对照现有 VIRTURA2114、VIRTURA-SpacePort、VIRTURA-Website、SceneForge 的 README/规范与已存历史品牌包。  
**审查结论**：**7 项优先保存并提炼（A）；5 项保存备查、择要引用（B）；1 项作为重复版本存档（C）**。这是对 13 个文件的*归档优先级*，不是对概念数量、原创性或文件独立性的统计。

### 0. 一句话决策

不要用 AI 重新生成一张“未来太空站首页”代替空间系统；应当先把 2024 年存在但尚未被规范化的几何拓扑、空间关系、品牌子系统和感知体验，转换成当前 Station 数据、建筑 Build Card、可运行的浏览器组件与档案链路。

保留旧世界不等于把 2050 废土世界观变成当前主页；2026 年 9 月已经将 `VIRTURA2114` 标为历史模拟。2026 年 11 月的最新讨论稿进一步倾向由 `VIRTURA Space／纬图空间` 承担统一平台入口。二者可以用“历史展馆/旧站参观入口”衔接，而非互相覆盖。

### 1. 原始证据与版本统计

| ID | 文件 | 页数 | 保存级别 | 核心价值 |
|---|---|---:|:---:|---|
| D01 | 什么是太空站？ (1).pdf | 25 | A | 原始空间视觉与项目图录 |
| D02 | 什么是太空站？.pdf | 22 | B | 项目图录的早期/另一导出版本 |
| D03 | 什么是太空站？ (2).pdf | 5 | A | 原始主张与空间文化项目列表 |
| D04 | VIRTURA  空间站详细设计方案.pdf | 6 | A | 原始空间建筑概念 |
| D05 | 修订数字空间建筑设计指南：从贝聿铭到列夫·马诺维奇的跨界思考.pdf | 11 | A | 理论转译与AI辅助创作史 |
| D06 | 数字空间建筑设计指南：多尺度空间解析.pdf | 5 | A | L/M/S 尺度框架 |
| D07 | 数字空间建筑设计指南2.0：多尺度实践与案例解析.pdf | 5 | B | 跨尺度案例类比 |
| D08 | 数字空间建筑设计指南3.0：理论框架与实践方法.pdf | 22 | B | 通用方法词库 |
| D09 | 数字空间体验设计指南3.0：从建筑美学到沉浸体验的跨界探索.pdf | 3 | B | 体验设计清单 |
| D10 | 感知设计-从UX到PX：重塑空间体验的新思维_ 深度解析 (1).pdf | 3 | A | 感知设计历史主张 |
| D11 | VIRTURA  数字空间价值体系完整方案.pdf | 7 | B | 服务/运营方案（附配图） |
| D12 | VIRTURA 数字空间价值体系完整方案.pdf | 7 | C | 服务方案另版 |
| I01 | DSVA1(20261119-164731).png | — | A | DSVA.2114品牌空间拓扑与视觉识别总图 |

**版本关系**：两份《VIRTURA 数字空间价值体系》正文高度重合，但前一份有嵌入图片；25 页和 22 页《什么是太空站？》也是大幅重叠、存在页数和内容差异的两版，不是两套独立的 3D 项目。5 页《什么是太空站？ (2)》则是较短的文本合辑。所有原件都应保留哈希和版本标签，但只选择一个“阅读起点”。

**保存策略**：最初的 PDF、PNG 原件应只读保存、记录 SHA256。约 46MB 的大图录不建议不分来源和权限就直接提交到公共 Git 历史；可先在权限受控的资料库保存完整字节，在仓库放 manifest、缩略图、文本提要和可审计的原件链接。对品牌图等必须核对使用权。

### 2. 最值得继续坚持的六种能力

1. **站点网络，而不是整张巨型地图**：2024 同心轨道、品牌点位、虚拟航线，把空间与功能组织成网络。2026 已明确为可独立加载的 `Station`，有 URL、状态、相邻路线、维护路径。应继承“路线”设计，但默认应允许瞬时跳转，不让人被迫在沉重 3D 中长途步行。
2. **几何/光/尺度就是导航系统**：早期贝聿铭、黑川纪章与新陈代谢派资料中的几何、中心大厅、外围胶囊、空间序列仍有价值。把它们用作布局、采光、转换、构造逻辑，不能只照搬几何造型或归咎于名人权威。
3. **跨尺度、跨端的通用空间语法**：旧 L/M/S 不是真实尺寸标准，却能帮助把城市/馆舍/小屋区分职责。映射到 2026 H96/H48/H24 要逐站验证：H 代表规划半径和 docking 约定，不应把三种旧概念与新参数直接画等号。
4. **非线性知识与作品档案**：列夫·马诺维奇式数据库/可变性讨论最值得复用的不是学术措辞，而是“同一作品可通过地图、展览、时间线、人物、项目档案、3D 场景多入口访问”。建立关系/出处/版本字段。
5. **能停留的感知空间**：从 UX 到 PX 所说的多感官一致性、身体参与、空间音频、气氛层次更适合实际体验。把茶屋作为慢速、高保真、低交互负担的验收场，不要把未经验证的感知公式当作标准。
6. **公共文化空间持续运营**：Balloon 不只是演出海报，MOVA 不只是图片墙，虚拟航线不只是传送动画；应该有真实节目/展映/归档/回看/活动预约或正在测试的产品行为。

### 3. 2024 文本的 AI 症状与判定

**最明显证据**：PDF《修订数字空间建筑设计指南……》第 5 页可见原始讨论中“然后批判一下这个文章……”及“Claude-3.5-Sonnet-200k / Poe”字样。这说明至少一部分属于 AI 辅助迭代稿，而非经过引用核实的正式研究论文。正确的档案标注应为 `historical-ai-assisted-draft`，而不是全盘否定它。

- **关键词膨胀**：元宇宙、AI、6G、区块链、数字资产、脑机接口、远程协作都被提到，但大多缺少可复验的接口、实测指标、操作人或具名代码。旧文本可作“2024 研究假设集合”，不能当现行技术规格。
- **虚构或未经验证的已实现状态**：价值体系里的“已实现案例”、文章里对跨地域实时协奏的“无缝”“极低延迟”等说法，缺少证据链。标记 `proposed/depicted/unverified`，除非找到运行录像、版本、独立记录。
- **建筑隐喻过度物理化**：数字空间的太阳能、自然通风、空气净化、能源循环不应当无条件成为网页站点的真实技术需求。可以转成性能预算、资源管理、生态模拟或叙事布景，必须明确是哪一种。
- **泛化的案例引用**：苏州博物馆、MoMA、威尼斯双年展、CES 等案例在旧 PDF 中多被用作比喻，未附可核实的一手资料或技术实现。引用前需另做文献核验。
- **伪精确标准**：60FPS、20ms、3秒等数字来自设计清单，并未按设备、网络、帧时间/输入延迟定义测试工况。只能作为历史目标，新的 Web/XR 规范应通过真机 profile 验证。
- **表达质量问题**：大量 emoji、重复泛论、前后版本粘贴、商业空话与引用不明；宜压缩为有项目出处的短论文、Build Cards 和测试方案，不适合全文作为网站介绍。

**2026 的变化**：AI 已更适合帮助生成工作代码、规范验证、素材预处理、辅助三维程序化搭建与测试，但仍不保证场景坐标、人尺度、设备兼容、版权、标志形状和可用性。生产顺序应始终是规范 → 源资产 → AI 辅助构建 → 固定视角对比 → 真机验收 → 审批发布。

### 4. 视觉总图的拆解价值

上传的白底轨道拓扑图与 PDF 中的早期场景渲染相互补充。它具有四个可被传承的视觉规则：

- **纸面工程图气质**：黑/银/米白、高密度小字、极细导航圆弧、尺寸轴线、带方向性的轨道，比默认霓虹科幻更具有独立性；支持现代网页中地图/系统状态/导览层。
- **中心集散 + 卫星场馆**：环形母体与外围导览节点直观地表达“多个可独立访问的文化设施”；可用于 A00 的信息可视化，但绝不要求把旧平面截图当实际建筑剖面。
- **共享结构与独立子品牌共存**：DSVA、VAAM、BALLOON、Virtual Airline、Digital Geographic、CCC 各有视觉识别；不要把所有场馆强行统一成一个绿色/黑色主题，也不能随意重画原标志。
- **方向语言**：斜向标注、切线、半径与数字印记可以成为视觉导航标记，同时保留功能性文本入口和适配移动端；不能为了视觉仪式牺牲可访问性。

**命名不一致需单独决策**：图中的 `VAAM` 与现行 `MOVA` 不能未经证据直接当成同名更正；图中 `CCC / Code Talker Collection Centre` 与 PDF《什么是太空站？》中的 `Commerce Collection Centre` 也不能自动合并。建立 `historical_label`、`current_id`、`relation=successor|related|unverified` 字段，让旧版本可被追溯。

### 5. 从旧概念到 2026 Station 的映射（建议，不是既成事实）

| 旧资产/概念 | 2026 对应 | 下一步可验证的功能 | 优先级 |
|---|---|---|---|
| DSVA 中央轨道/入口 | A00 Arrival Terminal | 浏览器首页→站点网络→3D大厅→返回网页；共享 Station manifest | P0 |
| Balloon Live Space | A02 Balloon | 一段录制的 live AV 可在 3D 媒体表面观看；后续再加 WebRTC/空间音频 | P1 |
| 林中茶屋/硒檐 | A03 T-House + A04 Senia | 静态/慢速高保真场景、局部捕捉自然、三种光照、移动与 XR 试验 | P2 |
| VAAM/美术馆线索 | A01 MOVA（**关系待确认**） | 一次现有真实展映，不需要新增三维建筑即可打开观看 | P3 |
| Virtual Airline | Routes 数据层 | URL→站点定位→预加载→过渡→返回；可独立工作于2D | P0组件 |
| Digital Geographic / 3D资料 | A04/A05/A06 候选功能 | 空间扫描、地理记忆/可验证数据展品或研究样本 | P3 |
| CCC 双重命名 | 资产索引/Collection 候选 | 先厘清历史实体和归属，避免误入现行品牌系统 | 调研 |
| 空间站治理/银行/委员会 | 内部业务/世界观附录 | 用真实财务、组织权限与项目记录替代虚构银行和法定实体 | 归档 |

### 6. 仓库归属：四层分工与安全门槛

**历史来源**：`ewanqian/VIRTURA2114`。建议新增：

```text
_历史原始资料/2024-12/README.md
_历史原始资料/2024-12/evidence-manifest.json
_历史原始资料/2024-12/source-index.md
_历史原始资料/2024-12/concepts/architectural-grammar.md
_历史原始资料/2024-12/concepts/brand-route-crosswalk.md
_历史原始资料/2024-12/review/2026-audit.md
```

原始大 PDF/图像字节可先放受控对象库/Drive/Library，再用稳定 URL 和 hash 链接，避免未授权公开和 Git 仓库膨胀。此目录只能描述 2024 证据和后续解释，不能改写当前运行的 Station 状态。

**当期世界/数据层**：`VIRTURA-SPACEPORT/VIRTURA-SpacePort`，沿用 `World Bible` / `Architecture Bible` / `Production Bible` / `Station Bible` 和 `stations/station-manifest.json`, `stations/frontstage-manifest.json`；只加入经过验证的 `legacy_source_refs` / `historical_aliases` / `design_motif_refs`。别维护第二套公开 Studio/Station registry。

**运行与3D**：`ewanqian/SceneForge`。继承站点加载、WebGL2/WebXR、媒体表面、镜头/cue/state、质量分级和真实 QA；不从历史 PDF 自动生成“已上线版本”。

**平台公共入口**：2026-11-18 `VIRTURA Space／纬图空间` 服务讨论稿建议由平台统一承担 SpacePort 的入口角色，别建立第二个重复“门户 App”；先由现有 Website 公共入口与 SpacePort Station 数据对齐。该文件是讨论稿，不代表未来所有实施范围已获批准。

**权限**：审阅源图版权与协作者署名、姓名和联系方式、当年项目合作文件、品牌使用权及 AI 生成物。归档已公开≠自动授权所有下游复用。

### 7. 已找到且应复用的既存资料（勿重复造轮子）

- [VIRTURA 2114历史桥接记录](https://github.com/ewanqian/VIRTURA2114/blob/main/2026_REBUILD_BRIDGE.md)
- [SpacePort World Bible v1.1](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/docs/world-bible/VIRTURA-SPACEPORT-WORLD-BIBLE-v1.1.md)
- [SpacePort Architecture Bible](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/docs/world-bible/VIRTURA-SPACEPORT-ARCHITECTURE-BIBLE-v1.0.md)
- [SpacePort Production Bible](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/docs/world-bible/VIRTURA-SPACEPORT-PRODUCTION-BIBLE-v1.0.md)
- [Station Bible](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/docs/world-bible/VIRTURA-SPACEPORT-STATION-BIBLE-v1.0.md)
- [A00 v0.1 Build Card](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/stations/orbital-arrival-terminal/build-card-v0.1.md)
- [Balloon 2022–23 VRChat档案](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/stations/balloon-live-space/history/2022-2023-vrchat/world-info.md)
- [林中茶屋高保真方向存档](https://github.com/VIRTURA-SPACEPORT/VIRTURA-SpacePort/blob/main/stations/teahouse-forest-pavilion/README.md)
- [SceneForge 运行时](https://github.com/ewanqian/SceneForge)
- 2026-11-18 最新服务体验提案（内部讨论稿，公开仓库不披露私有文件链接）
- [原始VI身份登记](https://github.com/ewanqian/VIRTURA-Website/blob/main/docs/brand/spaceport-brand-registry.v01.json)
- [2026-11-09原标志保真退稿记录](https://github.com/ewanqian/VIRTURA-Website/blob/main/docs/brand/REJECTION-VA-R02-AND-SOURCE-FIDELITY-GATE-2026-11-09.md)

**已核实 ChatGPT Library 保存位置**：`/VIRTURA/Brand-Archive/2026-11-08/`，内有 `VIRTURA_SOURCE_IMAGES.zip`（14项用户原始参考）、`VIRTURA_CONCEPT_STUDIES.zip`（6项 AI 概念）、`ASSET_MANIFEST.json`（包括 SHA256）、`Key-Visuals/` 等。不能把这两类图混成“官方 2024 母版”。

### 8. 还要寻找的原始证据（按价值排序）

1. 2022–2024 **可编辑三维源**：Unity 工程、Blender `.blend`、FBX/GLB/glTF、SPLINE 原场景链接、脚本、材质与灯光参数；若只有截图必须标记“设计效果”而非可用3D模型。
2. **设计母版**：DSVA.2114、VAAM/MOVA、Balloon、Virtual Airline、CCC 的 AI/Figma/PSD/SVG/字体授权，保留源长宽比与独立署名。
3. **可运行证据**：旧部署 URL、网页 HTML/CSS/JS、VRChat 世界 ID、屏幕录像、2023/24 截图、首发时间、用户测试结果与性能日志。
4. **工作过程**：首次空间拓扑、改图/分镜版本、评审与退稿、引用文献、提案/委托/参与权利、技术选型与成本。
5. **2026 既存后续研究**：`SpacePort UIVI 与产品化深度研究总稿.md`、`VIRTURA Spaceport Cultural District.pdf`、已存的 `alpha.html`、A00网页原型、2026十一月品牌存档包，以防再次把已整理过的内容当成空白。

### 9. 具体实施里程碑

**第一轮（证据冻结）**：把这 13 项录入只读来源清单；已有的原始图片 ZIP 和 PDF 保留，不做替换或压缩覆盖；在表内标注“原始来源/AI辅助/历史叙事/真实工程/当前规范/未证实”。完成判定：任一 PDF、标志或旧场景都有可追踪 hash、来源时间判断、存放位置、权利状态。

**第二轮（数据接轨）**：给 A00、A02、A03 各做 1 张 Build Card 复查；建立 `legacy_source_refs` 和变更记录；从当前 SpacePort manifest 派生网页与 3D，禁止双维护。完成判定：同一个链接从网页卡片和 3D 站点导航到相同的目的地与状态。

**第三轮（可体验样板）**：以 A00 为先做一个低带宽访问入口，浏览器2D仍完整可用；再做 A02 一段带回看的 3D 现场展示和 A03 的高保真静坐场景。完成判定：能够记录冷启动、加载大小、交互路径、静止/运动舒适性、移动端回退与真机结果。

**第四轮（开放审阅）**：请内测者辨别5个问题：进入此处的目的、当前开放内容、如何去另一个站、如何回到普通网页、如何分辨旧版档案与正在运行的功能。先解决误解和加载，再优化材质精度。

### 10. 决策底线

保存历史，不能让历史替代现实；AI 可辅助建造，不能替代证据与审美审批；空间必须服务可持续的活动、作品或使用任务，而不是“为了有三维而上三维”。

**写入状态**：审计原稿生成时未修改GitHub仓库。本PR仅提交历史审计文本及来源清单；未修改原始PDF/PNG及当前团队SpacePort工程。