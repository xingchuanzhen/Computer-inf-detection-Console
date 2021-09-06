# Computer-inf-detection-Console
用于检测电脑硬件配置信息

### 项目介绍

此项目是用于检测电脑硬件配置信息，如型号，状态，电压，频率和一些其他信息

项目采用WMI读取各项信息，采用控制台作为主要输入对象

### 使用方法

用法：    

          Detect [-p] [-z] [-n] [-w] [-c] [-b] [-j] [-x] [-m]



选项：    

          -p      输出处理器信息

          -z      输出主板信息
          
          -n      输出内存信息
          
          -w      输出网卡信息
          
          -c      输出磁盘信息
          
          -b      输出BIOS信息
          
          -j      输出监视器信息
          
          -x      输出显卡信息
          
          -m      输出系统信息
          
          -l      输出逻辑磁盘信息
          
          -s      输出声卡信息
          
## 使用示例

获得处理器信息

          Detect -p
          
获得内存信息

          Detect -n
          
获得处理器和内存信息

          Detect -p -n 
          
### 最后

由于采用的是WMI读取的信息，一切信息以操作系统获取到的为主，可能存在少许错误

          
          
