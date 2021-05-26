# ECS708P---MACHINE-LEARNING

### Mini项目包含两个任务：

基本解决方案 ：使用MLEnd数据集，建立一个预测短音频片段音调的模型。<br><br>
高级解决方案 ：有两个选项。 <br><br>
(1)提出可以使用MLEnd数据集尝试的机器学习问题并建立解决方案模型（例如，识别numeral）。<br><br>
(2)创建一种产品，该产品使用在MLEnd数据集上训练的模型提供的功能（例如，基于identification of individual numerals来识别number）。<br><br>

### 简单思路：

#### 推荐在Google Colab上进行实验，以防函数报错。 training数据集过大无法上传。

MLEnd数据集是一个语音数据集，分为4种不同语气读出数字。 具体在MLEnd_starter_kit里面有介绍。本项目主要任务是做语调分类。<br><br>

在基本解决方案中，建立一个模型来预测短音频片段的音调。 主要使用的语音特征是是MFCC和Log-Mel，相比来说MFCC更加重要。<br><br>

在高级解决方案中，建立了一个模型，该模型可以在短时间内识别数字。 主要特征是MFCC。<br><br><br>


ECS708P mini-project submission
The mini-project consists of two components:

Basic solution [6 marks]: Using the MLEnd dataset, build a model that predicts the intonation of a short audio segment.
Advanced solution [10 marks]: There are two options. <br><br>
(i) Formulate a machine learning problem that can be attempted using the MLEnd dataset and build a solution model (e.g. identify a numeral in a short sequence). <br><br>
(ii) Create a product that uses the functionality provided by a model trained on the MLEnd dataset (e.g. identify a number based on the identification of individual numerals).
