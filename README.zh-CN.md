# 伍炜杰 · Weijie Wu

[English](README.md) · [个人网站](https://go-bananas-wwj.github.io/) · [魔搭](https://modelscope.cn/profile/WeijieWu) · [邮箱](mailto:wuweijie25@mails.ucas.ac.cn)

我是中国科学院大学信号与信息处理专业直博生，师从李国庆教授，本科毕业于重庆大学人工智能专业。

我研究**遥感基础模型、多模态地理表征和智能体**，也喜欢把研究做成能使用的模型、接口和交互工具。目前在寻找**多模态大模型、AI for Science 方向的科研或工程实习**，远程和线下都可以。

## 代表项目

- **[XuanNv CGRF](https://github.com/go-bananas-wwj/xuannv-cgrf)**：把公共卫星观测与地方高分影像融合成可复用的 64 维地理嵌入。这是我当前的研究与代码发布，提供分地区实验、权重和 CPU 小样本复现。IEEE JSTARS 审稿中。[复现说明](https://github.com/go-bananas-wwj/xuannv-cgrf/blob/main/docs/reproduce.md)
- **[EarthEmbeddingExplorer](https://github.com/go-bananas-wwj/EarthEmbeddingExplorer)**：用文字、图片或坐标检索全球卫星影像。我是共同作者；个人 Fork 保留下载修复和独立的 OlmoEarth 接入实验。[论文](https://arxiv.org/abs/2603.29441) · [上游](https://github.com/OpenGeoScope/EarthEmbeddingExplorer) · [我的魔搭应用](https://modelscope.cn/studios/WeijieWu/EarthEmbeddingExplorer)
- **[XuanNv Embedding](https://github.com/go-bananas-wwj/xuannv_embedding)**：多源月度遥感表征的生产代码，包含数据准备、训练、兼容导出与下游头。海淀是已验证基线，哈尔滨冻结迁移和全国数据试点有各自的适用边界。[评测证据](https://github.com/go-bananas-wwj/xuannv_embedding/blob/main/docs/production/haidian-evidence.md)
- **[Embedding API](https://github.com/go-bananas-wwj/embedding-api)**：通过 FastAPI 提供嵌入查询、任务推理、自定义任务头和 SAM3 交互。完整推理还需要独立管理的模型与数据资产。[复现条件](https://github.com/go-bananas-wwj/embedding-api/blob/main/docs/REPRODUCTION.md)
- **[XuanNv Show](https://github.com/go-bananas-wwj/xuannv_show)**：用 React、Three.js 和 FastAPI 展示观测、地理嵌入和下游结果。[地区接入说明](https://github.com/go-bananas-wwj/xuannv_show/blob/dev/docs/REGION_SETUP.md)

玄女模型代码、API 和展示平台分别负责模型流程、资产服务和交互界面；CGRF 是独立的研究方法与发布，EarthEmbeddingExplorer 侧重跨模态检索。

## 代表论文

- **InstructSAM**：共同作者，NeurIPS 2025。[论文](https://arxiv.org/abs/2505.15818)
- **EarthEmbeddingExplorer**：共同作者，ICLR 2026 ML4RS Workshop Tutorial Track（oral，non-archival）；论文页面也列明 NeurIPS 2026 REO Workshop，non-archival。[论文](https://arxiv.org/abs/2603.29441)
- **Coverage-Aware Viewwise Residual Fusion for Reusable Regional Geospatial Embeddings**：IEEE JSTARS 审稿中。[代码、权重与数据](https://github.com/go-bananas-wwj/xuannv-cgrf)

## 更多项目

- **科学建模**：[SEIMS 复现分支](https://github.com/go-bananas-wwj/SEIMS/tree/validation-2026-05-07) · [红心村 SWAT+ 水文模型](https://github.com/go-bananas-wwj/hongxin_swat_plus)
- **工具与应用**：[AutoResearchClaw Docker 分支](https://github.com/go-bananas-wwj/AutoResearchClaw/tree/docker-setup) · [遥感影像拼字](https://github.com/go-bananas-wwj/rs_word) · [纯音乐生成](https://github.com/go-bananas-wwj/pure_music) · [成分真言](https://github.com/go-bananas-wwj/olaiya_front)
- **历史实验**：[xuannv](https://github.com/go-bananas-wwj/xuannv) · [已归档的 xuannv_embdding](https://github.com/go-bananas-wwj/xuannv_embdding)。当前表征生产代码请看 [xuannv_embedding](https://github.com/go-bananas-wwj/xuannv_embedding)。

## 联系我

[个人网站](https://go-bananas-wwj.github.io/) · [邮箱](mailto:wuweijie25@mails.ucas.ac.cn) · [魔搭](https://modelscope.cn/profile/WeijieWu) · [LinkedIn](https://www.linkedin.com/in/weijie-wu-a04221434/) · [X](https://x.com/weijiewu0306)
