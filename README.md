# Digit-Distinguish
基于python实现的数字字符图片识别

## 简介
* 程序使用KNN算法，计算图片各点与样本图片各点间欧式距离，选取出距离最短的几个样本，然后少数服从多数
* digit文件夹下是训练样本库trainingDigits，国外的数字测试图片testDigits，以及我个人画的一些测试图片myTestDigits，这些文件夹下的图片都已经转成字符画。
* imgToAsc.py脚本用于图片转字符画，script.py脚本用于单独测试一张图片
## 使用说明
* 运行KNN可以显示算法测试结果
* imagToAsc.py用于转换一张256色图片为36乘36的字符画，命令行 filename -o --OutputName
* 使用script即可识别一张图片。

### 备注
* 由于样本库中的图片来自国外，数字写法与国内并不相同，所以识别自己手写的图片成功率只有五成。
