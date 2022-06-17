
<img src="assets/GoodIdea.png" >

## Introduction

We're IDEA Public StoreHouse. Please keep the ideas coming.

As I continue to absorb as much knowledge as I can, I look forward to each new idea that pops into my head.

I love the process of stumbling upon an idea, hashing it out.

It really is an exciting process. You will gain a wealth of knowledge.

## Papers

### Technical blog

- [English Blog] Transformers in Vision [[Link](https://davide-coccomini.medium.com/)]
- [Chinese Blog] 3W字长文带你轻松入门视觉transformer [[Link](https://zhuanlan.zhihu.com/p/308301901)]
- [Chinese Blog] Vision Transformer 超详细解读 (原理分析+代码解读) [[Link](https://zhuanlan.zhihu.com/p/348593638)]

### Survey
  - A Survey of Visual Transformers [[paper](https://arxiv.org/abs/2111.06091)]  - 2021.11.30
  - Transformers in Vision: A Survey [[paper](https://arxiv.org/abs/2101.01169)]   - 2021.02.22
  - A Survey on Visual Transformer [[paper](https://arxiv.org/abs/2012.12556)]   - 2021.1.30
  - A Survey of Transformers  [[paper](https://arxiv.org/abs/2106.04554)]   - 2020.6.09

### AI视觉-实际应用场景下必解决的点


## 图像低质量/模糊/压缩等问题

图像质量是一个属性的组合，表明一个图像如何如实地捕获原始场景。影响图像质量的因素包括亮度、对比度、锐度、噪声、色彩一致性、分辨率、色调再现等。

低质量图像给AI在实际场景下的任务带来极大的挑战，究其根本是其会降低目标的可辨别性。

<details>
<summary>LOSS_IDEA</summary>


- AdaFace: Quality Adaptive Margin for Face Recognition  (**CVPR2022 Oral**)  [[paper](https://arxiv.org/abs/2204.00964)] [[code](https://github.com/mk-minchul/AdaFace)]

出发点： 从度量学习的角度考虑提升特征表示的鉴别性.
新思路： 简单或困难样本的相对重要性应该基于样本的图像质量来给定。
解决方案：通过用feature norms来近似图像质量，在提升低质量图像的识别精度的同时，也没有损失高质量图像的精度。
实验结论：通过对9个不同质量的数据集(LFW、CFP-FP、CPLFW、AgeDB、CALFW、IJB-B、IJB-C、IJB-S和TinyFace)的广泛评估，验证了该方法的有效性。


</details>


<summary>backbone</summary>

```shell
git clone git
pip3 install -v -e .  # or  python3 setup.py develop
```

</details>

## Deployment


1.  [MegEngine in C++ and Python](./demo/MegEngine)
2.  [ONNX export and an ONNXRuntime](./demo/ONNXRuntime)
3.  [TensorRT in C++ and Python](./demo/TensorRT)
4.  [ncnn in C++ and Java](./demo/ncnn)
5.  [OpenVINO in C++ and Python](./demo/OpenVINO)

**AI-视觉实际场景下**

## Cite CV_GoodIdea
If you use CV_GoodIdea in your research, please cite our work by using the following:

```latex
 @article{,
  title={},
  author={},
  journal={},
  year={2022}
}
```
