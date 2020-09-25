# Colab大内存副本

colab直接上传这个文件，然后在里面写代码！

GPU后端可以用25G RAM/68G 硬盘，TPU后端 35G RAM/107G 硬盘

白嫖前：

```
 physical_device_desc: "device: XLA_GPU device", name: "/device:GPU:0"
 device_type: "GPU"
 memory_limit: 14640891840
 ```

白嫖后：

```
 physical_device_desc: "device: XLA_GPU device", name: "/device:GPU:0"
 device_type: "GPU"
 memory_limit: 15695488000
```
