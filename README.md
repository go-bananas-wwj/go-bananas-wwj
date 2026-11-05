# Weijie Wu · 伍炜杰

[中文](README.zh-CN.md) · [Website](https://go-bananas-wwj.github.io/) · [ModelScope](https://modelscope.cn/profile/WeijieWu) · [Email](mailto:wuweijie25@mails.ucas.ac.cn)

I am a PhD student in Signal and Information Processing at the University of Chinese Academy of Sciences, advised by Prof. Guoqing Li. I received my B.S. in Artificial Intelligence from Chongqing University.

I work on **remote sensing foundation models, multimodal geospatial representations, and agents**. I enjoy taking research ideas through to usable models, APIs and interactive tools. I am looking for **research or engineering internships in multimodal models and AI for Science**, with both on-site and remote opportunities welcome.

## Selected projects

### [XuanNv CGRF](https://github.com/go-bananas-wwj/xuannv-cgrf)
Coverage-aware fusion of public satellite observations and local high-resolution imagery into reusable 64-D embeddings. This is my current research and released implementation, with region-specific experiments, weights and a CPU mini-sample quickstart. **IEEE JSTARS: under review.**

[Code & reported results](https://github.com/go-bananas-wwj/xuannv-cgrf) · [Reproduction guide](https://github.com/go-bananas-wwj/xuannv-cgrf/blob/main/docs/reproduce.md) · [Data](https://modelscope.cn/datasets/WeijieWu/xuannv-cgrf-data)

### [EarthEmbeddingExplorer](https://github.com/go-bananas-wwj/EarthEmbeddingExplorer)
Search global satellite images with text, images or coordinates. I am a co-author of the work; this personal fork includes download fixes and separate OlmoEarth integration experiments. The upstream project and my fork are linked separately.

[Paper](https://arxiv.org/abs/2603.29441) · [Upstream](https://github.com/OpenGeoScope/EarthEmbeddingExplorer) · [Personal fork](https://github.com/go-bananas-wwj/EarthEmbeddingExplorer) · [My ModelScope app](https://modelscope.cn/studios/WeijieWu/EarthEmbeddingExplorer)

<img src="https://raw.githubusercontent.com/go-bananas-wwj/EarthEmbeddingExplorer/main/images/Text_Search.jpg" alt="EarthEmbeddingExplorer text-to-satellite-image retrieval example" width="760">

*Retrieval example from the EarthEmbeddingExplorer project.*

### [XuanNv Embedding](https://github.com/go-bananas-wwj/xuannv_embedding)
A maintained implementation for monthly, multi-source geospatial embeddings: data preparation, training, checkpoint-compatible export and lightweight downstream heads. Haidian is the validated production baseline; frozen Harbin transfer and the China data pilot have separate evidence and limitations.

[Code](https://github.com/go-bananas-wwj/xuannv_embedding) · [Model card](https://github.com/go-bananas-wwj/xuannv_embedding/blob/main/docs/production/haidian-model-card.md) · [Evaluation evidence](https://github.com/go-bananas-wwj/xuannv_embedding/blob/main/docs/production/haidian-evidence.md)

### [Embedding API](https://github.com/go-bananas-wwj/embedding-api)
The serving layer for regional embeddings, downstream inference, user-trained task heads and SAM3 interaction. The repository contains the FastAPI service, API examples, deployment configuration and tests. Full inference requires separately managed model and data assets.

[Code & API guide](https://github.com/go-bananas-wwj/embedding-api) · [Reproduction requirements](https://github.com/go-bananas-wwj/embedding-api/blob/main/docs/REPRODUCTION.md)

### [XuanNv Show](https://github.com/go-bananas-wwj/xuannv_show)
The interactive viewer for the XuanNv workflow: a React/Three.js map interface with a FastAPI backend for exploring observations, embeddings and downstream outputs.

[Code & local setup](https://github.com/go-bananas-wwj/xuannv_show) · [Region setup](https://github.com/go-bananas-wwj/xuannv_show/blob/dev/docs/REGION_SETUP.md)

**How they fit together:** XuanNv Embedding provides the model workflow, Embedding API serves model assets, and XuanNv Show provides an interactive interface. CGRF is a separate research method and release; EarthEmbeddingExplorer focuses on cross-modal retrieval.

## Selected publications

- **InstructSAM: A Training-Free Framework for Instruction-Oriented Remote Sensing Object Recognition** — co-author, **NeurIPS 2025**. [Paper](https://arxiv.org/abs/2505.15818)
- **EarthEmbeddingExplorer: A Web Application for Cross-Modal Retrieval of Global Satellite Images** — co-author, **ICLR 2026 ML4RS Workshop, Tutorial Track (oral, non-archival)**; also listed for the non-archival REO Workshop at NeurIPS 2026. [Paper](https://arxiv.org/abs/2603.29441)
- **Coverage-Aware Viewwise Residual Fusion for Reusable Regional Geospatial Embeddings** — **IEEE JSTARS, under review**. [Code, weights and data](https://github.com/go-bananas-wwj/xuannv-cgrf)

## More projects

- **Scientific modelling:** [SEIMS — Linux/agent work and reproduction branch](https://github.com/go-bananas-wwj/SEIMS/tree/validation-2026-05-07) · [Hongxin SWAT+ — watershed modelling](https://github.com/go-bananas-wwj/hongxin_swat_plus)
- **Tools and applications:** [AutoResearchClaw — Docker branch](https://github.com/go-bananas-wwj/AutoResearchClaw/tree/docker-setup) · [rs_word — satellite-image typography](https://github.com/go-bananas-wwj/rs_word) · [pure_music — instrumental generation](https://github.com/go-bananas-wwj/pure_music) · [成分真言 — ingredient evidence explorer](https://github.com/go-bananas-wwj/olaiya_front)
- **Earlier XuanNv experiments:** [xuannv](https://github.com/go-bananas-wwj/xuannv) · [archived xuannv_embdding](https://github.com/go-bananas-wwj/xuannv_embdding). For the maintained embedding pipeline, start with [xuannv_embedding](https://github.com/go-bananas-wwj/xuannv_embedding).

## Contact

[Personal website](https://go-bananas-wwj.github.io/) · [Email](mailto:wuweijie25@mails.ucas.ac.cn) · [ModelScope](https://modelscope.cn/profile/WeijieWu) · [LinkedIn](https://www.linkedin.com/in/weijie-wu-a04221434/) · [X](https://x.com/weijiewu0306)
