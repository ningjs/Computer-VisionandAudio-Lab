# 实验一 语音端点检测

* 双门限法

 1. 第一步是取一个较高的短时能量作为阈值MH。
 2. 第二步是取一个较低的能量阈值ML。
 3. 第三步是利用短时过零率，短时过零率的阈值为Zs。
 
# 实验二 差分编码（DPCM）

* 语音差分编码（DPCM）**边压缩，边解压**

# 实验三 命令词识别

 1. 设计命令词识别任务

 2. 特征提取

 3. 识别测试

 4. 计算测试结果

 5. 扩展尝试
	* 将经过实验验证的算法，转化为能实时采集。

# 实验四 图像颜色空间的转换

1. 完成如下颜色空间的转换。

* RGB -> YIQ 
* RGB -> HSI 
* RGB -> YCbCr 
* RGB -> XYZ 

2. 选做：自己实现对 BMP 文件头的读取，并解析 BMP 图像文件。

# 实验五 亮度、对比度、饱和度、色度 & 空域滤波 & 边缘检测

 1. 实现对图像的亮度、对比度、饱和度、色度的调整。 
 2. 统计图像的直方图。
 3. 实现图像的空域滤波：中值滤波和均值滤波。
 4. 实现图像的边缘检测：Roberts 算子和 Sobel 算子。
 5. 以下实验选做一个 
	* 实现中值滤波的快速算法 
	* 利用 CUDA 加速均值滤波

# 实验六 图像修复

 1. 去除图像中的背景和水印的去除。 
 2. 去除人脸图像中的雀斑。

 3
