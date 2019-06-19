# Nvidia CPU

1. **Tesla**                

2. **Fermi**              
3. **Kepler**            
4. **Maxwell**         
5. **Pascal**            
6. **Truing**            

### 术语与概念：

**1、流处理器（stream processor ，SP):也称为core，是GPU运算的最基本计算单元**

**2、渲染核（shader core）：SP的另一个名称，也成为CUDA core**

**3、双精度浮点运算单元（DP):专用于双精度浮点运算的处理单元**

**4、特殊功能单元：用来执行超越函数指令**

**5、流处理器（stream multiprocessor，SM):GPU架构中的基本单元，也是GPU性能的源泉，由SP、DP、SFU等运算单元组成。是一个典型的阵列机，其执行方式为SIMT（单指令多线程），区别于传统的SIMD，能够保证多线程同时执行（向量化）**

**6、SMX:Kepler架构中的SM**

**7、SMM:Maxwell架构中的SM** 

**8、线程处理器簇（thread processing cluster,TPC):由SM和L1 cache组成，存在于最新的Pasal架构中与最旧的Tesla架构**

**9、流处理器阵列（scalable stream processor array，SPA):所有处理器核心和高速缓存综合，包含所有的SM、TPC和GPC。与存储器系统共同总成GPU架构**

**10、存储控制器（memory controller ，MMC):控制存储访问的单元，合并访存。每个存储控制器可以支持一定的位宽（比如64位）的数据合并访存**

**11、光栅操作单元（raster operation processor，POP)**

**12、存储单元（load/store units，LD/ST)**





### 发展历史

**1993年  Nvidia成立，显示芯片为 NV-1和NV-2**

**1997年   Nvidia发布NV-3**

**1999年   Nvidia发布GeForce256，支持Direct7**

**2001年   Nvidia推出可编程着色器GPUGeForce3和GeForce4 支持Direct8**

**2002年   Nvidia推出第一款用32位浮点流水线作为可编程的顶点处理器GeForceFx，支持Direct9**

**有GeForce6和GeForce7**

**2006年  Nvidia系列采用统一渲染架构，同通用渲染单元替代原来分离的顶点着色单元和图像着色**

**单元，支持Direct10，支持CUDA，即Tesla**

**2007年 CUDA正式发布**

**2008年  Nvidia发布支持CUDA1.1计算能力的GeForce9系列，创造神话的9800GT，以及算力1.3的**

**GT200系列GPU，GTX275卡皇～**

**2010年   Nvidia推出了Fermi架构产品M2050、GTX480，计算能力2.x**

**2012年   Nvidia发布了Kepler架构，算力为3.5,**

**2013年   Maxwell架构发布，算力为5.0**

**2015年    Pascal架构发布，算力为6.0**

**2016年    GTC大会发布了NvLin、CoWos HBM2堆叠内存技术的显卡**

**2019年  Truing架构发布，算力为7.x**



**设计架构**

