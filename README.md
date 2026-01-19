# Re-Align: Structured Reasoning-guided Alignment for In-Context Image Generation and Editing

> ## Re-Align: Structured Reasoning-guided Alignment for In-Context Image Generation and Editing
>
> Runze He<sup>1,2,3</sup>, Yiji Cheng<sup>1</sup>, Tiankai Hang<sup>1</sup>, Zhimin Li<sup>1</sup>, Yu Xu<sup>1</sup>, Zijin Yin<sup>1</sup>, Shiyi Zhang<sup>1</sup>, Wenxun Dai<sup>1</sup>, Penghui Du<sup>3</sup>, Ao Ma<sup>3</sup>, Chunyu Wang<sup>1,✝</sup>, Qinglin Lu<sup>1</sup>, Jizhong Han<sup>2,3</sup>, Jiao Dai<sup>2,3,‡</sup>
> 
> <sup>1</sup>Hunyuan, Tencent, <sup>2</sup>IIE, CAS, <sup>3</sup>UCAS

![1768824629720](assets/README/1768824629720.png)

> **In-context image generation and editing** (ICGE) enables users to specify visual concepts through interleaved image-text prompts, demanding precise understanding and faithful execution of user intent. Although recent unified multimodal models exhibit promising understanding capabilities, these strengths often fail to transfer effectively to image generation. We introduce Re-Align, a unified framework that bridges the gap between understanding and generation through structured reasoning-guided alignment. At its core lies the **In-Context Chain-of-Thought** (IC-CoT), a structured reasoning paradigm that decouples semantic guidance and reference association, providing clear textual target and mitigating confusion among reference images. Furthermore, Re-Align introduces an effective RL training scheme that leverages a surrogate reward to measure the alignment between structured reasoning text and the generated image, thereby improving the model’s overall performance on ICGE tasks. Extensive experiments verify that Re-Align outperforms competitive methods of comparable model scale and resources on both in-context image generation and editing tasks.
