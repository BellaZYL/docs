## torch.nn.Dropout2d
### [torch.nn.Dropout2d](https://pytorch.org/docs/stable/generated/torch.nn.Dropout2d.html?highlight=dropout2d#torch.nn.Dropout2d)
```python
torch.nn.Dropout2d(p=0.5,
                   inplace=False)
```
### [paddle.nn.Dropout2D](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/nn/Dropout2D_cn.html#dropout2d)
```python
paddle.nn.Dropout2D(p=0.5,
                    data_format='NCHW',
                    name=None)
```

其中 Pytorch 和 Paddle 均支持了更多的参数，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| inplace       | -            | 表示在不更改变量的内存地址的情况下，直接修改变量的值，PaddlePaddle 无此参数，一般对网络训练结果影响不大，可直接删除。  |
| -             | data_format  | 指定对输入的数据格式，PyTorch 无此参数，Paddle 保持默认即可。 |
