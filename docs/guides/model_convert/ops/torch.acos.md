## torch.acos
### [torch.acos](https://pytorch.org/docs/stable/generated/torch.acos.html?highlight=acos#torch.acos)

```python
torch.acos(input,
           *,
           out=None)
```

### [paddle.acos](https://www.paddlepaddle.org.cn/documentation/docs/zh/api/paddle/acos_cn.html#acos)

```python
paddle.acos(x,
            name=None)
```

其中 Pytorch 相比 Paddle 支持更多其他参数，具体如下：
### 参数差异
| PyTorch       | PaddlePaddle | 备注                                                   |
| ------------- | ------------ | ------------------------------------------------------ |
| input         | x            | 输入的 Tensor。                                      |
| out           | -            | 表示输出的 Tensor，PaddlePaddle 无此参数。               |


### 转写示例
#### out：指定输出
```python
# Pytorch 写法
torch.acos([3, 5], out=y)

# Paddle 写法
y = paddle.acos([3, 5])
```
