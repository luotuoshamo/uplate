## v1.0 202004 完成测U盘真实容量的功能
不足：
​    1. 测量很慢（4g的U盘需要11分钟）
​    2. 测量过程占电脑内存过多（电脑明显变卡）
​    3. 代码不整洁

## V1.1 202010 重构代码，优化测量算法
    1. 往磁盘上写大文件，用16MB的块速度最快