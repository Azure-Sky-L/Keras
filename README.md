# Keras
### 1.手写数字识别：<br>
>> 1）对数据进行归一化处理<br>
>> 2）搭建 CNN 网络结构为 : -> [[Conv2D->relu]*2 -> MaxPool2D -> Dropout]*2 -> Flatten -> Dense -> Dropout -> Out <br>
>> 3) 构建损失函数和优化器 <br>
>> 4) 使用 ImageDataGenerator进行数据扩增： 还不熟悉 ImageDataGenerator参数使用的看这里：https://keras-cn.readthedocs.io/en/latest/preprocess <br>
>> 5）训练数据及评估模型<br>
### 2.猫狗识别：<br>
>> 1)对数据进行归一化处理<br>
>> 2)搭建 CNN 网络模型： [[Conv2D->relu]*2 -> MaxPool2D  -> Droupt] -> [[Conv2D->relu]*2 -> MaxPool2D]*3 -> Flatten -> Dense -> Droupot -> Dense
>> 3)Activation: sigmoid; optimizer:optimizer
>> 4）训练数据及评估模型<br>
### 3.幼苗识别：<br>
>> 1) 对数据进行归一化处理<br>
>> 2) VGG16 预训练模型<br>
>> 3) optimizer:Adam; loss=:categorical_crossentropy<br>
>> 4) ImageDataGenerator 进行数据集扩增<br>
>> 5) 训练数据及评估模型<br>
