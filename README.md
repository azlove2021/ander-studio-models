# 安德生物工作室 · 教学模型库

**在线直接看：** https://azlove2021.github.io/ander-studio-models/

29 个生物学交互教学模型，纯静态站点，浏览器打开即用 —— 不需要装 Python，不需要下载，不需要联网登录。

每个模型都是一个自包含的小应用：可播放动画、切换阶段、缩放、拖拽、逐帧观察。

## 模型清单

| 模型 | 模块 | 版本 |
|---|---|---|
| [组成细胞的元素（2D）](cell-elements/index.html) | 分子与细胞 | 2.6.1 |
| [噬菌体的繁殖（2D动画）](bacteriophage-reproduction/index.html) | 分子与细胞 | 2.5.0 |
| [DNA 双螺旋结构模型](dna-webgl/index.html) | 分子与细胞 | 2.4.2 |
| [DNA复制模型（2D）](dna-replication/index.html) | 遗传信息的复制 | 2.4.2 |
| [DNA转录与RNA加工模型（2D）](dna-transcription/index.html) | 遗传信息的转录与加工 | 2.2.4 |
| [mRNA翻译模型（2D）](translation/index.html) | 遗传信息的翻译 | 2.2.2 |
| [RNA 结构模型](rna-webgl/index.html) | 分子与细胞 | 2.4.2 |
| [蛋白质的结构模型](protein-webgl/index.html) | 分子与细胞 | 2.4.2 |
| [物质跨膜运输模型](transport/index.html) | 分子与细胞 | 2.3.0 |
| [细胞膜流动镶嵌模型](membrane/index.html) | 分子与细胞 | 2.4.0 |
| [植物细胞结构模型](plant-cell-webgl/index.html) | 分子与细胞 | 2.5.1 |
| [动物细胞结构模型](animal-cell/index.html) | 分子与细胞 | 2.2.3 |
| [光学显微镜模型](optical-microscope/index.html) | 分子与细胞 | 2.7.5 |
| [静息电位与动作电位](resting-action-potential/index.html) | 选择性必修一 · 神经调节 | 2.7.1 |
| [动作电位的传导](action-potential-conduction/index.html) | 选择性必修一 · 神经调节 | 2.7.2 |
| [双相神经干电位](biphasic-nerve-potential/index.html) | 选择性必修一 · 神经调节 | 2.3.1 |
| [PCR的基本过程](pcr/index.html) | 选择性必修三 · 生物技术与工程 | 2.5.1 |
| [PCR的产物类型](pcr-product-types/index.html) | 选择性必修三 · 生物技术与工程 | 2.3.5 |
| [利用引物改造DNA](pcr-primer-engineering/index.html) | 选择性必修三 · 生物技术与工程 | 2.2.1 |
| [Sanger测序](sanger-sequencing/index.html) | 选择性必修三 · 生物技术与工程 | 2.5.1 |
| [种群的增长曲线](population-growth/index.html) | 选择性必修二 · 生物与环境 | 2.3.0 |
| [种间关系曲线变化](species-interactions/index.html) | 选择性必修二 · 生物与环境 | 2.0.4 |
| [群落的演替](community-succession/index.html) | 选择性必修二 · 生物与环境 | 2.2.0 |
| [细胞呼吸的过程](cellular-respiration/index.html) | 必修一 · 分子与细胞 | 2.2.0 |
| [渗透作用](osmosis/index.html) | 必修一 · 分子与细胞 | 2.1.0 |
| [光合作用的过程](photosynthesis/index.html) | 必修一 · 分子与细胞 | 2.1.0 |
| [细胞呼吸电子传递链](respiratory-electron-transport/index.html) | 必修一 · 分子与细胞 | 2.5.0 |
| [光系统电子传递链](photosynthetic-electron-transport/index.html) | 必修一 · 分子与细胞 | 2.2.1 |
| [遗传学三大定律](genetic-inheritance-laws/index.html) | 遗传与进化 | 2.1.2 |

## 本地预览

如果想离线看，把本仓库克隆下来用任意静态服务器打开即可（模型是 ES module，必须经 HTTP 打开，不能直接双击 `index.html`）：

```bash
git clone https://github.com/azlove2021/ander-studio-models.git
cd ander-studio-models
python -m http.server 8000
```

## 完整离线版（含题库）

模型库之外还有 **938 道题库快照**（含高考真题、答案解析、考点筛选）、本地账号登录等完整功能，
需要 Python 后端，见 [ander-studio-offline](https://github.com/azlove2021/ander-studio-offline)。

## 说明

站内内容（模型、题库、图文）的知识产权归原作者所有，仅供学习与教学用途。
