根据何凯明的仓库描述，对`pytorch-cifar100`的代码进行修改，使其和`resnet-1k-layers`的结构一致

修改点：
- `pytorch-cifar100`的仓库没有在四个block之后添加BN层和ReLU层，本仓库修正了这一BUG

参考仓库：
1. https://github.com/weiaicunzai/pytorch-cifar100
2. https://github.com/KaimingHe/resnet-1k-layers
