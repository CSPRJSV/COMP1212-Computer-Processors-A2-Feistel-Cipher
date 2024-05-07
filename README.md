# COMP1212-Computer-Processors-A2-Feistel-Cipher
# COMP1212 Computer Processors A2 Feistel Cipher 1v1 专业远程辅导助攻、讲题和VIP定制服务 保证原创 严厉拒绝一份多售
# 源头导师 科班出身 可全英文听说读写流畅丝滑 非中介甩单！
# 支持 零散答疑 lecture同步辅导 assignment专题辅导 test prep 等多种灵活辅导方式
# VX: csprojhelp 备注：github

【重点解析: 】

考察和练习 Hack Assembly 编程。三个 parts 层层递进，最终实现 4 轮的 Feistel 加密算法。

Part A: 实现 XOR 运算，RAM[5] = RAM[3] XOR RAM[4]。关键点在于将 XOR 转换成 Hack 汇编所支持的运算

Part B: 实现将 RAM[3] 中的值向左轮换 RAM[4] 次的 rotate 操作。轮换指的是所有 bit 向左移一位，原来最左边的 bit 成为移动后最后边的 bit

Part C: 实现 4 轮 Feistel 加密。观察 Feistel  Encryption 的定义不难发现其中用到了大量 XOR 与 rotate 操作，于是设法把 PartA/B 中的代码转化为工具函数调用，这样将大大简化 Part C 的编程。难点在于如何用 Hack 汇编实现函数调用与返回，以及如何将 Feistel 的数学操作转换为对 PartA/B 相应的函数调用

【debug小技巧： 】

1. .tst 文件可自定义输出格式和测试数据，方便用自己的 testcases
2. 项目自带的 CPU Emulator 自带 breakpoint 功能，对 debug 非常有利



#comp1212 #UniversityOfLeeds #利兹大学 #留学生辅导 #留学生作业辅导 #留学生补习

================================================

欢迎有需要辅导的同学dd～
