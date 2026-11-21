## [Unreleased]

### Added

- docs：新增提案《先预演后渲染：本地低保真生成与云端高保真重绘的两段式视频工作流提案》（docs/essay/local-preview-cloud-redraw.md）——本地 VACE 480P 预演、云端可灵/Vidu/即梦重绘的两段式链路，含分工、四步操作、甜区雷区与验证计划

# CHANGELOG

所有显著变更都将记录在此文件中。

格式基于 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.0.0/)。

---

- 自 quanttide-founder 迁入内容：`docs/handbook/`（index）、`docs/essay/`（ai-image-to-frame）、`docs/tutorial/`（creative-work-intro、ai-native-creative-work）

- 自 quanttide-founder context 迁入创作草稿：`data/journal/2026-11-17.md`

- 撤回：`data/journal/2026-11-17.md` 归位错误，移回 quanttide-founder `data/journal/fiction/`

- 挂载 `data/journal` → quanttide-journal-of-creative-work、`data/profile` → quanttide-profile-of-creative-work；迁入 context 的 create/ 内容（日志入 journal `default/`，素材入 profile `quanttide-founder/` 租户目录）

- 挂载 `data/context` → quanttide-context-of-creative-work（待归位记忆仓骨架）

- 修订定位：用 AI 做内容的作坊（方法、半成品、未成形的项目）；立项成剧的整套迁 drama

- 补定位理由：高频迭代与中间过程记录；与 fiction（原文，人维护）、drama（立项后成片）的分工

- 挂载 `apps/qtcloud-create` → qtcloud-create（工作台）、`apps/qtcloud-studio` → qtcloud-studio（生成工作室）

- 更正：studio 为 qtcloud-create 仓内 `src/studio`（对齐 qtcloud-media 惯例），撤销独立仓 qtcloud-studio 注册

- 挂载 `docs/gallery` → quanttide-gallery-of-creative-work（案例集：工具与创意配合的元方法探究）

## [Unreleased]

- 注册子模块：`data/library`（quanttide-library-of-creative-work，创意工作图书馆）：工具介绍四篇（EchoShot、Phantom、VACE、FlowEdit/FlowAlign），Wan2.1-1.3B 生态查证带出处
- 更新 `examples/quanttide-create-lab`：1.3B 查证补「对到 profile 素材」逐条对照（同人三镜、9:16 画幅、VACE 参考图路线）；新增 `docs/wan21-13b-community.md`
- 更新 `examples/quanttide-create-lab`：新增 `src/cli`（run-shot，Rust）——跑一镜视频生成实验，产物与 run.md 自动落档 experiments/
- 注册子模块：`examples/quanttide-create-lab`（quanttide-create-lab，创意工作实验室），仓库初始化为骨架，实验室元仓双登记
- 初始化：量潮创意工作 领域第二大脑骨架（README、AGENTS、CHANGELOG、LICENSE）
