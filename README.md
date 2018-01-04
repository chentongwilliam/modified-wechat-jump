# modified-wechat-jump
New jump function with random tap position.
Original code from: https://github.com/wangshub/wechat_jump_game
Needed: Bluestacks, ADB, Annaconda(Python2.x)
Instruction: https://zhuanlan.zhihu.com/p/32492610
使用说明：
1.将py文件保存在ADB文件夹下,ADB文件夹添加到path路径中
2.创建一个1.png文件在目标文件夹下
3.在文件夹中空白处按住Shift并右键点选打开cmd
4.同时打开Bluestacks并运行微信（记得升级到最新版），进入跳一跳，并点开始游戏
5.在cmd中输入adb devices,若无设备信息，则手动添加：输入：adb connect 127.0.0.1:5555
6.输入python wechat jump.py运行程序
