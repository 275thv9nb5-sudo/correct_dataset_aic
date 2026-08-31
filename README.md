# AIC 2026 原始数据集 (校准前)

**内容**: 训练集 2000 张三模态 (visible/infrared/depth) + 旧版 labels + 测试集 1000 张三模态 (无标签)。

**注意**:
- 这是赛方 2026-08-31 标签校准**之前**的原始版本 (旧 labels, 有约 382 张欠标/错标)
- 校准后的标签在赛方下载链接的单独文件夹 new_labels_2000 (本仓库不含); 修正版完整数据集见 aic_corrected_dataset 仓库
- 原始的两个 zip 包 (12.6G+5.8G) 超过 GitHub 100MB 单文件限制未上传, 内容与解压文件完全一致

**三模态**: visible (RGB 可见光) / infrared (红外热成像) / depth (16-bit 毫米深度, PNG为uint16, 小图JPG为8-bit灰度)
