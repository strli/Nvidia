Nvidia CPU

1、Tesla               CUDA1.0
2、Fermi               CUDA2.0
3、Kepler              CUDA3.0
5、Maxwell             CUDA5.0
6、Pascal              CUDA6.0
7、Truing              CUDA7.0


一、术语与概念
1、流处理器（stream processor ，SP):也称为core，是GPU运算的最基本计算单元
2、渲染核（shader core）：SP的另一个名称，也成为CUDA core
3、双精度浮点运算单元（DP):专用于双精度浮点运算的处理单元
4、特殊功能单元：用来执行超越函数指令
5、流处理器（stream multiprocessor，SM):GPU架构中的基本单元，也是GPU性能的源泉，由SP、DP、SFU等运算单元组成。是一个典型的阵列机，其执行方式为SIMT（单指令多线程），区别于传统的SIMD，能够保证多线程同时执行（向量化）
6、SMX:Kepler架构中的SM
7、SMM:Maxwell架构中的SM 
8、线程处理器簇（thread processing cluster,TPC):由SM和L1 cache组成，存在于最新的Pasal架构中与最旧的Tesla架构
9、流处理器阵列（scalable stream processor array，SPA):所有处理器核心和高速缓存综合，包含所有的SM、TPC和GPC。与存储器系统共同总成GPU架构
10、存储控制器（memory controller ，MMC):控制存储访问的单元，合并访存。每个存储控制器可以支持一定的位宽（比如64位）的数据合并访存
11、光栅操作单元（raster operation processor，POP)
12、存储单元（load/store units，LD/ST)

二、

