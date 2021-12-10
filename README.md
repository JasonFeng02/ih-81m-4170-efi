# ih-81m-4170-efi

联想m4500准系统 4170 efi

主板为联想ih 81m，CPU为i3-4170，显卡为核显HD4400，网卡为bcm943302cs。

已驱动：网卡，CPU，核显，蓝牙，WiFi，usb，dp转hdmi输出，

未驱动：dp转dp外接屏幕

attention：主板上仅有11pin usb接口，使用pcie网卡的蓝牙模块需使用11pin转9pin转接线

ps，已做兼容性测试，理论上所有四代平台，不限主板型号皆可以使用本efi

目前bug：hd4400通病，浏览.app打开png等一切图片文件会卡死，目前qq会卡死

未定制usb，efi下载后请自行定制usb及修改三码
