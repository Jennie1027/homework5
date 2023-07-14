```python
# 多模态情感分析

## Setup
pandas==1.1.5
anaconda-client==1.7.2
anaconda-navigator==2.0.3
conda==4.11.0
huggingface-hub==0.16.4
ipykernel 
ipython 
jupyter==1.0.0
numpy 
tokenizers==0.13.3
torch==2.0.1
torchaudio==2.0.2+cu117
torchdata==0.6.1
torchtext==0.15.2
torchvision==0.15.2+cu117
transformers==4.30.2



## 文件结构
|-- data/  图片文本训练集
|-- train.txt  训练集
|-- code.ipynb  实验代码
|-- test_without_label.txt  测试集结果
|-- requirements.txt 
|-- README.md
|-- 10203330405_沈杰怡_实验报告.pdf  实验报告
```
## 执行代码完整流程
运行code.ipynb，逐步运行即可
可在主代码中修改lr、batch_size的参数
修改X参数model = MixModel(3,X)可切换分析文本、图像或图文结合


## 参考的库
from transformers import BertModel, BertTokenizer
from torchvision.models import resnet50
```
