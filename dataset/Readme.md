### zi2zi 训练样本

本文件夹提供用于 zi2zi 模型训练的样本字体，包含：

* **样本文楷 / Sample WenKai**：基于「霞鹜文楷 轻便版」[v1.234](https://github.com/lxgw/LxgwWenKai-Lite/releases/tag/v1.234) 制作，作为来源（source）字体
* **样本臻楷 / Sample ZhenKai**：基于「霞鹜臻楷」**[v0.554](https://github.com/lxgw/LxgwZhenKai/releases/tag/v0.554)** 制作，作为目标（target）字体

为保证训练质量，目标字体**剔除了骨架不一致干扰字形**（如「氟」「氯」「跻」等），确保源字体与目标字体的汉字骨架高度一致。

训练出模型后，可利用该模型在「霞鹜文楷」或其他 Klee One 衍生字体基础上，生成对应的加粗字形。