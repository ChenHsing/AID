# AID

This repository is the official implementation of **AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction**.

**[AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction](https://arxiv.org/abs/)**
<br/>
[Zhen Xing](https://chenhsing.github.io/) , [Qi Dai](https://scholar.google.com/citations?user=NSJY12IAAAAJ), Zejia Weng, [Zuxuan Wu](https://zxwu.azurewebsites.net/), [Yu-Gang Jiang](https://scholar.google.com/citations?user=f3_FP8AAAAAJ&hl=zh-CN)
<br/>

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Project Website](https://img.shields.io/badge/Project-Website-orange)](https://chenhsing.github.io/AID/) [![arXiv](https://img.shields.io/badge/arXiv-2311.18837-b31b1b.svg)](https://arxiv.org/abs/2311.18837)

<p align="center">
<img src="overview.jpg" width="1080px"/>  
<br>
<em>AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction.</em>
</p>


## Abstract
> Text-guided video prediction (TVP) involves predicting the motion of future frames from the initial frame according to an instruction, which has wide applications in virtual reality, robotics, and content creation. Previous TVP methods make significant breakthroughs by adapting Stable Diffusion for this task. However, they struggle with frame consistency and temporal stability primarily due to the limited scale of video datasets. We observe that pretrained Image2Video diffusion models possess good priors for video dynamics but they lack textual control. Hence, transferring Image2Video models to leverage their video dynamic priors while injecting instruction control to generate controllable videos is both a meaningful and challenging task. To achieve this, we introduce the Multi-Modal Large Language Model (MLLM) to predict future video states based on initial frames and text instructions. More specifically, we design a dual query transformer (DQFormer) architecture, which integrates the instructions and frames into the conditional embeddings for future frame prediction. Additionally, we develop Long-Short Term Temporal Adapters and Spatial Adapters that can quickly transfer general video diffusion models to specific scenarios with minimal training costs. Experimental results show that our method significantly outperforms state-of-the-art techniques on four datasets: Something Something V2, Epic Kitchen-100, Bridge Data, and UCF-101. Notably, AID achieves 91.2% and 55.5% FVD improvements on Bridge and SSv2 respectively, demonstrating its effectiveness in various domains.

## Contact
If you have any suggestions or find our work helpful, feel free to contact us

Homepage: [Zhen Xing](https://chenhsing.github.io)

Email: zhenxingfd@gmail.com


If you find our work useful, please consider citing it:

```
@article{AID,
  title={AID: Adapting Image2Video Diffusion Models for Instruction-guided Video Prediction},
  author={Zhen Xing and Qi Dai and Zejia Weng and Zuxuan Wu and Yu-Gang Jiang}, 
  journal={arXiv preprint arXiv},
  year={2024}
}
```
