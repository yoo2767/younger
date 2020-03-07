## 安装 Linux 系统时自定义分区
- Linux安装系统时可以默认分区，也可以自定义分区

### 自定义分区：
- 首先，需要明白的是安装新的 Linux 系统的时候，我们需要设置三个分区，分别是 `/` ，`/boot` ，`swap` 三个分区；
- 如果是在工作环境中，对于数据库及存储的服务器还可以再分出一个 `/data` 分区
- 门户网站一般的分区方案：
- 假设服务器内存是`16G`，硬盘为`1T`
- `/` 分区: 一般分配80~200G；
- `/boot` 分区: 一般分配100~200MB；
- `/swap` 分区: 一般内存的1-1.5倍
- 其余空间部分，保留作为其他业务