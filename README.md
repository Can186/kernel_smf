## 红米10X(Pro)国行版内核源代码工程

全新体验，多种优化

### 特性

高刷新率、快速充电、修复构建错误等等
```
本内核仅供开发人员参考，请勿构建成品并发表到MIUI社区
为了避免SB骚扰，请不要在MIUI社区提及本工程，万分感谢
仅供自行测试使用
如有修改建议欢迎提交PR
```
------
注意，内核源代码需要遵循GPLv3协议进行开源
请使用本工程的内核注明出处
------
联系方式：1@die.lu

------
QQ 2737996094

------
网站：http://www.die.lu/
---------------
```
构建方式：
mkdir out
export环境变量，或者修改Makefile，target aarch64
红米10X
make atom_user_defconfig O=./out
红米10X Pro
make bomb_user_defconfig O=./out
make menuconfig O=./out
修改你的交叉编译器（或者本机编译器）路径
make -j8 O=./out
```
