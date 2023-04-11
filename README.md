# SemiAutoAnnotation_SAE
基于SAE生成的掩膜切片的半自动图像标注工具
A semi-auto annotation tool based on SAE created mask.

目前只能区分两类

使用时修改maskdir, image的路径即可

首先部署SAE模型
运行SAE模型中的/scirpts/amg.py
生成图像对应的分体掩膜
最后运行本代码，删除错误分割，保留对应类别的mask。
