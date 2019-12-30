# T460s-Clover
适用于ThinkPad T460的Clover Bootloader，Kexts，config和ACPI补丁。

## 支持什么硬件
- 触摸板驱动程序已更改为acidanthera的VodooPS2（https://github.com/acidanthera/VoodooPS2）。此驱动程序可在Synaptic触摸板上启用多点触摸手势（但顶部按钮不起作用）
- 三叶草已更新为5102，支持macOS Catalina
- The other kexts were updated
- 支持DW1560无线网卡和补丁
- 增加了对DW1820a的支持
- Legacy_Sierra_QMI已添加以支持内部调制解调器
- 添加了CPUFriend，可将基本频率降至800MHz。
- 添加了老的的Mac启动的开机音

## 未支持的硬件
- SD读卡器
- 触摸板顶部物理鼠标按钮

## 已测试硬件
此处上传的配置已在配备i7-6600U CPU，Intel HD Graphics 520 GPU，8GB RAM，256GB NVMe驱动器和FHD屏幕的ThinkPad T460s上进行了测试。英特尔WiFi卡被DW1820a取代。如果您的配置不同于我的配置，则可能需要重新编译ACPI补丁。
