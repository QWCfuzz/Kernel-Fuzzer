# Work
---
这是核心Kernel Fuzzer，其中包含示例库调用和Syscall，用于启动Windows模糊测试。该模糊器已经在Windows 7/10，OS X和QNX上进行了测试。

＃入门

下载并安装Python 3.5

使用随附的.bat脚本为正确的体系结构编译系统的二进制文件（仅Windows！）。已使用Visual Studio 2013测试-如果使用其他版本的VS，请编辑脚本以指向“ vcvarsall.bat”的副本。

运行worker_setup / worker_setup.py

该脚本应根据需要设置虚拟机，重新启动并启动模糊器。

edit---QWC


（已停止该项目，转到另一个实验室同事进行跟进）---做巨人背后的专家
