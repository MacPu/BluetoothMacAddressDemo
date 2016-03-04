# BluetoothMacAddressDemo
这是一个iOS获取蓝牙Mac地址的例子，苹果官方并没有提供获取蓝牙Mac地址的方法，这个例子是基于MPBluetoothKit写的
这里是[MPBluetoothKit](https://github.com/MacPu/MPBluetoothKit)的地址。

## 关于这个DEMO
因为我之前有写过一篇关于如何获取苹果蓝牙Mac地址的博客，但是没有例子，所以有读者表示希望能有一个例子。

## Tips

也不是每个蓝牙设备都可以从这个例子中获取Mac地址，这个蓝牙设备必须提供以下两个通道
![](http://img.blog.csdn.net/20151112220356607)

所以在测试是这个例子的时候，请先检查你的蓝牙设备是否支持。否者可能无法通过此方法获取Mac地址
