# lithium-ion-battery-solver-examples
examples of lithium-ion battery simulations, including various material systems, operating conditions.  
Sec 代表文章中第几章所用到的案例。Sec4代表第四章， Sec5代表第五章。case 代表每一章中的第几个算例。
-----------------------------------------------------------------------------------------------------
第四章算例的目的：空间方法鲁棒性测试
Sec4case1: 单晶NCM（实心球）-石墨（实心球）体系
Sec4case2: NCM（团聚体）-石墨（实心球）体系
Sec4case3：磷酸锰铁锂（LiMn1-yFeyPO4，LMFP）（实心球）-石墨（实心球）体系
Sec4case3：复合正极（NCM团聚体和LMFP实心球）-石墨（实心球）负极体系
-----------------------------------------------------------------------------------------------------
第五章算例目的：选取粒径分布、复合电极及工艺缺陷三类典型场景开展数值仿真。
Sec5case1：粒径设计
Sec5case2：复合正极
Sec5case1：涂布缺陷
-----------------------------------------------------------------------------------------------------
每个算例文件夹下：
stl_dir 包含了几何文件；
generalProperties：为热动力学参数；interpolateProperties为插值所需要用的参数表；workingControl为工况设置
其他文件是求解器运行多需要的一些文件。
