# [HS-ResNet](https://arxiv.org/abs/2010.07621)
#### 收录到[PytorchNetHub](https://github.com/bobo0810/PytorchNetHub)

## 说明
- 非官方(官方PaddlePaddle版暂未开源)
- 建议HSBottleNeck(显存过大)、BottleNeck搭配使用

## 环境

| python版本 | pytorch版本 | 系统   |
|------------|-------------|--------|
| 3.6        | 1.6.0       | Ubuntu |

## 使用

```python
import hs_resnet50,hs_resnet101,hs_resnet152
pred=model(imgs)
```

## 算法框架
![](https://github.com/bobo0810/HS-ResNet/blob/main/imgs/hs_block.png)