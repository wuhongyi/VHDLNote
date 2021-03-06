<!-- README.md --- 
;; 
;; Description: 
;; Author: Hongyi Wu(吴鸿毅)
;; Email: wuhongyi@qq.com 
;; Created: 五 7月 28 16:36:00 2017 (+0800)
;; Last-Updated: 四 2月  8 00:03:49 2018 (+0800)
;;           By: Hongyi Wu(吴鸿毅)
;;     Update #: 11
;; URL: http://wuhongyi.cn -->

# README

参考书：

- [VHDL入门教程 ppt](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL入门教程.ppt)  
- [VHDL语言入门教程 ppt](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL语言入门教程.ppt)  
- [VHDL-语言入门 pdf](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL-语言入门.pdf)


- [VHDL硬件描述语言与和数字逻辑电路设计_侯伯亭顾新](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL硬件描述语言与和数字逻辑电路设计_侯伯亭顾新.pdf)  
- [VHDL硬件描述语言与数字逻辑电路设计第三版](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL硬件描述语言与数字逻辑电路设计第三版.pdf)  
- [VHDL语言100例详解](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL语言100例详解.pdf)
- [FPGA Prototyping by VHDL Examples](http://wuhongyi.cn/FPGANote/pdf/VHDL/FPGAPrototypingbyVHDLExamples.pdf)
- [VHDL入门·解惑·经典实例·经验总结](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL入门·解惑·经典实例·经验总结.pdf)
- [VHDL设计表示和综合](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL设计表示和综合.pdf)
- [VHDL数字电子学](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL数字电子学.pdf)
- [](http://wuhongyi.cn/FPGANote/pdf/VHDL/)


参考网站：

- [VHDL Tutorial: Learn by Example](http://esd.cs.ucr.edu/labs/tutorial/)
- [VHDL reference material](https://www.csee.umbc.edu/portal/help/VHDL/)
- [nandland 卖开发板](https://www.nandland.com/)
- [surf-vhdl](http://surf-vhdl.com/)


[VHDL Simulation of Trapezoidal Filter for Digital Nuclear Spectroscopy systems](http://wuhongyi.cn/FPGANote/pdf/VHDL/VHDL Simulation of Trapezoidal Filter for Digital Nuclear Spectroscopy systems.pdf)

----

一个完整的VHDL设计应该包括：
- 实体（entity）。主要是用于描述和外部设备的接口信号以及类属等。
- 结构体（architecture）。用于描述系统的具体逻辑行为功能。
- 配置（configuration）。配置用来从库中选择所需单元爱组成系统设计的不同版本。
- 包集合（package）。包存放设计使用到的公共数据类型、常数和子程序等。
- 库（library）。库存放已经编译的实体、构造体、包集合和配置等。


## VHDL 实体

一个实体由实体头部和实体声明部分构成。其语法格式为：

```vhdl
entity identifier is
	entity_header  --实体头部
	entity_declarative_part  --实体声明部分
begin
	[entity_atatement_part]  --实体的描述部分
end [entity] [entity_simple_name]

-- [] 表示可选的参数
-- 如果出现entity_simple_name，该名字必须和identifier一致。
```


###实体头部

实体头部由类属说明列表和端口说明两部分组成。








<!-- README.md ends here -->
