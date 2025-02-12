# 简介

用于存放一些文档,如使用[doxygen](https://www.doxygen.nl/)生成的帮助文档。

可使用如下链接阅读此文档:

- [https://heyahong.github.io/#/](https://heyahong.github.io/#/)
- [http://docs.hyhsystem.cn](http://docs.hyhsystem.cn)

# 文档列表

## SimpleModbusRTUPacket

简易Modbus RTU解析。

- <a href="SimpleModbusRTUPacket/" target="_blank">SimpleModbusRTUPacket </a> 

## DeployWin

辅助在使用[MSYS2](https://www.msys2.org/)（包括mingw）与[Cygwin](http://cygwin.org/) 上开发Windows程序

- <a href="DeployWin/" target="_blank">DeployWin</a>

# 第三方文档链接

第三方文档，方便查阅。

## riscv-isa-manual

RISC-V指令集手册。

仓库链接:[https://github.com/riscv/riscv-isa-manual.git](https://github.com/riscv/riscv-isa-manual.git)

- <a href="riscv-isa-manual/riscv-unprivileged.html" target="_blank">riscv-unprivileged.html</a> 
- <a href="riscv-isa-manual/riscv-privileged.html" target="_blank">riscv-privileged.html</a> 

## riscv-opcodes

RISC-V 操作码。

仓库链接:[https://github.com/riscv/riscv-opcodes](https://github.com/riscv/riscv-opcodes)

其中生成的表格可采用[CTex](https://ctex.org/)将tex文件转换为pdf文件。

由于tex文件存放的是表格，需要在tex文件中添加头和尾变成文档才可转换为pdf。

添加的latex头：

```latex
\documentclass{article}
\usepackage[left=1in, right=1in, top=1in, bottom=1in]{geometry}
\begin{document}

\centering
```

添加的latex尾：

```latex
\end{document}
```

- <a href="riscv-opcodes/instr-table.pdf" target="_blank">instr-table.pdf </a> 
- <a href="riscv-opcodes/priv-instr-table.pdf" target="_blank">priv-instr-table.pdf </a> 

# 相关链接

## 个人仓库地址

- [github.com](https://github.com/HEYAHONG)
- [gitee.com](https://gitee.com/HEYAHONG)

## 博客及相关网站

- [mediawiki](http://mediawiki.hyhsystem.cn/)
- [syscall.online](https://syscall.online):代码测试网站
