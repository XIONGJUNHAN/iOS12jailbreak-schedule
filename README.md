GeoSn0w整合多个漏洞发布iOS12开发者越狱工具Osiris。

该工具实现：

1：沙盒逃逸（sandbox escape）

2：a clean kernel task port （TFP0）

3：注销 respring

该工具未实现（待实现）：

1：remount 重新挂载Root分区为可写

（自然就没有写入BootStrap 和当然也没有Cydia）

2：没有绕过CoreTrust 代码签名检查

越狱开发进度时间线：
Ian Beer (@i41nbeer) has just released three bugs for iOS 12.0-12.1.2 - 

iOS/MacOS kernel heap overflow in PF_KEY due to lack of bounds checking when retrieving statistics

XNU vm_map_copy optimization which requires atomicity

Arbitrary mach port name deallocation in XPC

2019-02-01 01:19
RazMashat(@RazMashat)

the project that im working on righ now：

1. v1ntx12 addapting v1ntx to iOS 12

2. xSpirial root kit to learn and test iOS 12 post exploitaion

links to his projects:

https://github.com/razmashat/v1ntex
