要对已有代码进行重构，重新组织文件分布。
按功能建立文件夹，将相似的文件放在一起
makefile 怎么写是个问题，这里要学一下
# 方案一
架构：随不同架构变化的程序
    启动，涉及到汇编的程序，硬件，底层的函数等。
通用：c语言程序，全平台通用
    内核等
    
    
    
arch/
    i386/
        boot/
    x64/
include/
    libc/
kernel/
    fs/
    dev/
    mm/
    ...
