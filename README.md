# flexEFI
![0](https://github.com/user-attachments/assets/bb280b88-e93e-49d1-83c6-ac25dc37cfaa)
一个集硬件检测、USB定制精准、EFI定制和EFI编辑的融合工具，在线自动下载、升级驱动，保持OC和驱动为最新版本。

![1](https://github.com/user-attachments/assets/f30e4821-08ba-44d2-a090-2f781a31abaf)
**硬件检测：** <br>
不像鲁大师、360等只是罗列硬件，该检测提取的硬件信息更为详细;<br>
1.检测硬件，提取硬件信息更为详细；<br>
2.提取分析DSDT，为量身定制EF打下基础；<br>
3.并在线分析是否支持黑苹果，并指出一些硬件应该怎么处理才能支持黑苹果。<br>

![2](https://github.com/user-attachments/assets/8bcca448-6728-4d31-855e-e4165aa678a1)
**USB定制：** <br>
1.采用了图形化展示和操作；<br>
2.加入了声音提示不用再一边插拔一边观看界面；<br>
3.检测采用终端触犯，检测更为迅速；<br>
4.定制出来的驱动自动判定机型生成机型相关或机型无关的驱动；<br>
5.机型相关的驱动采用了hactool的机制生成，稳定性更高。<br>

![3](https://github.com/user-attachments/assets/f1a5224b-bee9-42c5-a9f3-24d23fdeec47)
**EFI定制：** <br>
1.根据硬件信息量身定制，自动生成、重新编译SSDT补丁；<br>
2.自动适配驱动，没有一丝冗余；<br>
3.对声卡、网卡、显卡、硬盘自动处理内置、屏蔽处理等处理；<br>
4.对macOS系统需要打OCLP补丁时，会自动打EFI补丁，后续直接打OCLP补丁即可；<br>
5.自动在线下载最新版OC和kext驱动；<br>

![4](https://github.com/user-attachments/assets/6312fd84-3c66-4e77-8a47-8ffa690bfffc)
**镜像下载：** <br>
采用500M专线直接下载，避免网盘的尴尬；<br>

![5](https://github.com/user-attachments/assets/141bf33e-074f-497e-a20b-43aa2874339f)
**特色功能：** <br>
针对安装、安装后一些特殊机子的问题进行修复，比如Dell的重启不断地、HP的RTC错误、Lexa核心显卡驱动等。<br>
1.修复后直接合入Config文件，不需要手工改动；<br>
2.需要驱动时，自动下载，自动放入相应目录；<br>
3.需要SSDT补丁时会自动生成或下载；<br>
全程无感操作，自动化处理。<br>

使用过程如遇到程序崩溃，请把黑色监视界面的报错信息拍照发给我。VX：fike1116，更多功能和下载见：[haconln.com](https://haconln.com)





