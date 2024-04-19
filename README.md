# proj360-RuxOS-ML
## RuxOS语言层支持——ML

## 项目描述

RuxOS是由矽望社区开发和维护的一款兼容Linux应用程序的轻量化库操作系统，遵循Unikernel设计思想。

RuxOS运行于QEMU之上，并支持X86_64、AArch64、Riscv64三种架构。目前，在应用支持方面，RuxOS已经支持了多个主流应用：Redis、Nginx、WAMR等；在编程语言方面，RuxOS提供了C标准库API，并完成了musl libc在X86_64和AArch64上的支持。此外，还支持了C++语言，目前正在进行Rust以及Python的支持。

ML是一类静态的函数式编程语言，具有强大的模式匹配功能，支持高阶函数，在编译器和解释器开发、形式化验证、并发编程、AI领域以及数据分析和处理领域有着广泛应用。

本项目的目的是丰富RuxOS的语言层支持，完成对ML的支持。

## 预期目标

- 修改、丰富RuxOS现有组件，设计并完成RuxOS对ML的支持。
- 在RuxOS上运行ML应用，并通过相关的基准测试。

## 特征

- 分析、利用Unikernel的特点设计ML的支持思路，形成详细文档。
- 考虑多架构的支持，分别测试在X86\_64和AArch64上的运行情况。

## 已有参考资源

- [矽望社区](https://syswonder.org/#/)技术文档
- [RuxOS-Book](https://ruxos.syswonder.org)
- [RuxOS](https://github.com/syswonder/ruxos)开源代码

## 赛题分类

- 新型内核（如unikernel、微内核等）
- 编程语言支持（如转换、编码等）

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生

- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖

- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等

## License

Mulan PSL v2

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

- 姓名：陈康
- 单位：清华大学计算机系
- github ID：nk7651
- email：chenkang@tsinghua.edu.cn

## 助理导师

- 姓名：吴政
- email：ken4647@outlook.com

- 姓名：徐金阳
- email：459461160@qq.com
