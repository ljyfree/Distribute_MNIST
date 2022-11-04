## 目的
* 原来的例子于2017年提交，在现在普遍tensorflow 2.x的环境下无法运行
* 通过conda构造python2.7的环境，方便运行distributed.py

## 使用方法
* 修改dmnist.yaml文件最后一行，将"your-path-to-miniconda3"替换为你的miniconda3的路径
* 加载
```
conda env create -n my_tensorflow -f dmnist.yaml
```
