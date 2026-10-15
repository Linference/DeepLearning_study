# DeepLearning_study

动手学深度学习练习。

代码来源：[《动手学深度学习》](https://zh.d2l.ai/) PyTorch 版，位于 [`pytorch/`](pytorch)。

## 文件夹 ↔ 书本章节对照

`pytorch/` 下的文件夹按**字母序**排列，与书本章节顺序不一致，下表按书的顺序列出。

| 书本章节 | 文件夹 |
| --- | --- |
| 前言 / 安装 / 符号 | [`chapter_preface`](pytorch/chapter_preface) · [`chapter_installation`](pytorch/chapter_installation) · [`chapter_notation`](pytorch/chapter_notation) |
| 1. 引言 | [`chapter_introduction`](pytorch/chapter_introduction) |
| 2. 预备知识 | [`chapter_preliminaries`](pytorch/chapter_preliminaries) |
| 3. 线性神经网络 | [`chapter_linear-networks`](pytorch/chapter_linear-networks) |
| 4. 多层感知机 | [`chapter_multilayer-perceptrons`](pytorch/chapter_multilayer-perceptrons) |
| 5. 深度学习计算 | [`chapter_deep-learning-computation`](pytorch/chapter_deep-learning-computation) |
| 6. 卷积神经网络 | [`chapter_convolutional-neural-networks`](pytorch/chapter_convolutional-neural-networks) |
| 7. 现代卷积神经网络 | [`chapter_convolutional-modern`](pytorch/chapter_convolutional-modern) |
| 8. 循环神经网络 | [`chapter_recurrent-neural-networks`](pytorch/chapter_recurrent-neural-networks) |
| 9. 现代循环神经网络 | [`chapter_recurrent-modern`](pytorch/chapter_recurrent-modern) |
| 10. 注意力机制 | [`chapter_attention-mechanisms`](pytorch/chapter_attention-mechanisms) |
| 11. 优化算法 | [`chapter_optimization`](pytorch/chapter_optimization) |
| 12. 计算性能 | [`chapter_computational-performance`](pytorch/chapter_computational-performance) |
| 13. 计算机视觉 | [`chapter_computer-vision`](pytorch/chapter_computer-vision) |
| 14. 自然语言处理：预训练 | [`chapter_natural-language-processing-pretraining`](pytorch/chapter_natural-language-processing-pretraining) |
| 15. 自然语言处理：应用 | [`chapter_natural-language-processing-applications`](pytorch/chapter_natural-language-processing-applications) |
| 16. 附录：深度学习工具 | [`chapter_appendix-tools-for-deep-learning`](pytorch/chapter_appendix-tools-for-deep-learning) |
| 17. 参考文献 | [`chapter_references`](pytorch/chapter_references) |

## 使用提示

- 每个文件夹里的 `index.ipynb` 是该章目录页，列出本章各节链接。建议从它进入，不必逐个翻文件夹。
- 文件名即小节名，可直接对照书本目录，例如 `linear-regression-scratch.ipynb` 对应「线性回归的从零开始实现」。
- 运行 notebook 需要先安装 `d2l` 包（`pytorch/setup.py`），否则每个 notebook 的导入单元格会报错。
