# 外设接口规范

标签： RT-Thread规范 文档模版

---

> 文档面向专业的BSP驱动工程师，所以在文档中并不需要详细介绍外设工作原理，也不需要介绍太多上层应用使用方法；

## 外设

> 外设的简单介绍;
> 最简单的数据、控制交互逻辑是什么样的；

### 驱动需要实现的接口

> 以驱动ops模式介绍外设驱动需要实现什么样的接口；
> 对于接口中的配置、数据结构体需要进行详细的解释；

### RT-Thread Device接口

> 如果要实现 `rt_device_*` 的接口，需要依次进行说明；

### 注意事项

> 可以结合skeleton中的代码模版，说明相关的一些注意事项；