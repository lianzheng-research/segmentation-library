# segmentation-library

This repository is a collection of papers, resources and codes related to image segmentation tasks. The collection is arranged in chronological order to showcase the progression of research and development in this field.

A concise summary of each paper is provided to outline its motivation and main contributions. We welcome any feedback on our comments, including error identification and valuable insights. Please feel free to submit a request at any time.

## segmentation

| Source | Method | Title | Summary |
|:------:|:------:|:----- |:------- |
| ICLR 2023 <br> Outstanding Paper | VTM | Universal Few-Shot Learning of Dense Prediction Tasks with Visual Token Matching [paper](https://openreview.net/pdf?id=88nT0j5jAn) [code](https://github.com/GitGyun/visual_token_matching) [summary](https://github.com/lianzheng-research/segmentation-library/blob/main/2023/iclr-2023-vtm) | VTM is the first universal few-shot learner for arbitrary dense prediction task. It employs non-parametric matching on patch-level embedded tokens of images and labels within a hierarchical encoder-decoder architecture that is optimized with the standard episodic meta-learning protocol. |
| ICCV 2021 | Segmenter | Segmenter: Transformer for Semantic Segmentation [paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Strudel_Segmenter_Transformer_for_Semantic_Segmentation_ICCV_2021_paper.pdf) [code](https://github.com/rstrudel/segmenter) | Segmenter is a Transformer model for semantic segmentation. It obtains class labels from visual embeddings with a point-wise linear decoder or a Mask Transformer decoder. |
| CVPR 2015 | FCN | Fully Convolutional Networks for Semantic Segmentation [paper](https://openaccess.thecvf.com/content_cvpr_2015/papers/Long_Fully_Convolutional_Networks_2015_CVPR_paper.pdf) | FCN is the first dense prediction framework trained end-to-end from supervised pre-training. It takes input of arbitrary size and produces correspondingly-sized output. A skip architecture is defined to combine semantic information from a deep, coarse layer with appearance information from a shallow, fine layer to produce accurate and detailed segmentations. |

## backbones









