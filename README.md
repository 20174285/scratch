# scratch
划痕缺陷数据：cqu_scratch_data

工业检测上的划痕缺陷数据，标签类型是像素级的标注，可用于深度学习中的训练和验证。

划痕数据介绍：

每张图片分辨率大小是912*912，都包含了划痕缺陷。

一共包含80张图片，从中随机挑选了70张作为训练集，其余10张作为测试集。

原图像训练集：train/80/train。其中images是划痕训练集中的图像，labels是划痕训练集中的标签。

原图像测试集：train/80/val。其中images是划痕测试集中的图像，labels是划痕测试集中的标签。

除了上述提及的文件夹之外的其他图像都是经过数据扩充后的数据集。

上传者：重庆大学计算机学院主教416学生
