
- **1.题目：DiRA: Discriminative, Restorative, and Adversarial Learning for Self-supervised Medical Image Analysis**

连接：https://arxiv.org/abs/2204.10437#

代码连接：https://github.com/fhaghighi/DiRA

上传者：田佳渊

关键词：目标检测 自监督

数据集：ChestXray（医学影像，预训练）

贡献：第一个自我监督学习框架，以统一的方式将歧视性、恢复性和对抗性学习无缝地结合在一起,实验证明了DiRA的泛化性和优越性

- **2.题目：Semi-Supervised Semantic Segmentation Using Unreliable Pseudo-Labels(CVPR2022)**

连接：https://arxiv.org/abs/2203.03884

代码连接：https://github.com/Haochen-Wang409/U2PL/

上传者：岳崝

关键词：语义分割 半监督

数据集：PASCAL VOC 2012

贡献：有效利用了包括不可靠样本在内的无标签数据，大幅提升了语义分割精度

- **3.题目：Leverage Your Local and Global Representations: A New Self-Supervised Learning Strategy**

连接：https://arxiv.org/abs/2203.17205

代码连接：

上传者：田佳渊

关键词：语义分割 自监督

数据集：CIFAR10, STL10, and ImageNet100 (IN-100)

贡献：LoGo提倡两种局部视图具有不同的代表性，鼓励它们的不相似性，从而防止退化解，同时接近全局视图，同一图像的局部视图看起来比来自不同图像的更相似，可以轻松应用于现有的SSL方法，在各种数据集上的广泛实验以及使用不同的自我监督学习框架验证了其优于现有方法的优势

- **4.题目：UniVIP: A Unified Framework for Self-Supervised Visual Pre-training(CVPR2022)**

连接：https://arxiv.org/abs/2203.06965

代码连接：

上传者：田佳渊

关键词：自监督预训练  

数据集：coco train2017;coco+;imagenet

贡献：为了有效克服非标志性图像中随机视图的语义不一致性，我们提出了一种统一的自监督表示学习框架，并可对任意图像进行预训练。出同时利用场景-场景的相似性、场景-实例的相关性和实例-实例的鉴别性来有效地提升模型的性能。在单中心对象和非标志性数据集上用UniVIP预训练的模型在多个下游任务，如图像分类、半监督学习、对象检测和分割等方面都优于以往的SOTA方法。

- **5.题目：Self-Supervised Visual Representations Learning by Contrastive Mask Prediction(ICCV2021)**

连接：https://arxiv.org/abs/2108.07954

代码连接：

上传者：田佳渊

关键词：自监督预训练  

数据集：coco;cc;pascal voc;imagenet

贡献：提出对比掩码预测作为自监督学习的借口任务，设计MASKCo自监督学习方法，通过实验证明该方法在非imagenet数据集上进行预训练并没有像其他sota那样产生性能下降。MaskCo为在自然景象数据集进行自我监督学习提供了基于id的方法之外的一个有前途的选择。

- **6.题目：ST++: Make Self-training Work Better for Semi-supervised Semantic Segmentation(CVPR2022)**

连接：https://arxiv.org/abs/2106.05095

代码连接：https://github.com/LiheYoung/ST-PlusPlus

上传者：岳崝

关键词：半监督，语义分割  

数据集：PASCAL VOC 2012

贡献：通过强大的数据增强，以及基于整体预测水平的稳定性优先考虑可靠的无标签图像来进行选择性的再训练，构建了一个优秀且实用的半监督语义分割框架

- **7.题目：Improving Contrastive Learning by Visualizing Feature Transformation**

链接：https://arxiv.org/abs/2108.02982

代码链接：https://github.com/DTennant/CL-Visualizing-Feature-Transformation

上传者：田佳渊

关键词：特征级特征转换，目标检测

数据集：imagenet coco

贡献：首先设计了一个pos/neg score分布的可视化方案，使我们能够分析、解释和理解学习过程。提出特征级的数据操作，包括正样本的外推和负样本之间的内插。

- **8.题目：Geography-Aware Self-Supervised Learning**

链接：https://arxiv.org/abs/2011.09980

代码链接：https://github.com/sustainlab-group/geography-aware-ssl

上传者：田佳渊

关键词：时间变化正样本，地理位置预测（借口任务）

数据集：fMoW，GeoImageNet

贡献：利用遥感数据的时空结构，利用随时间的空间对齐图像在对比学习中构建时间正样本，并利用地理位置预测充当借口任务。

- **9.题目：RegionCL: Can Simple Region Swapping Contribute to Contrastive Learning?**

链接：https://arxiv.org/abs/2111.12309

代码链接：https://github.com/Annbless/RegionCL

上传者：田佳渊

关键词：剪裁剩余区域

数据集：ImageNet，MS COCO，cityscenes

贡献：1.首次尝试从自我监督学习的完整角度来论证裁剪区域和裁剪剩余区域的重要性。2. 我们提出了一个简单而有效的借口任务，即RegionCL。它与各种流行的SSL方法兼容，只做了少量修改，并提高了它们在许多下游可视化任务上的性能

- **10.题目：Barlow Twins: Self-Supervised Learning via Redundancy Reduction**

链接：https://arxiv.org/pdf/2103.03230.pdf

代码链接：https://github.com/facebookresearch/barlowtwins（不完全）

上传者：田佳渊

关键词：冗余减少，对称结构

数据集：ImageNet，COCO，voc

贡献：它将冗余减少(冗余减少是神经科学中首次提出的原则)应用于自我监督学习。

- **11.题目：Synergistic Self-supervised and Quantization Learning**

链接：https://arxiv.org/abs/2207.05432

代码链接：https://github.com/megvii-research/SSQL-ECCV2022.

上传者：曹茗翔

关键词：量化，自监督学习，迁移学习

数据集：cifar10,cifar100,ImageNet

贡献：提出了一种称为协同自监督和量化学习 (SSQL) 的方法来预训练量化友好的自监督模型，以促进下游部署。




