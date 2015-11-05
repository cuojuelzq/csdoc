# csdoc
Documents about Installation &amp; Management of CS.

## 安装

> 1. Install Hypervisor, NFS Storage, Management Server OS
> 2. Install CloudPlatform & base templates
> 3. Build Zones, Pods, Clusters & Hosts
> 4. Customer & User Management
> 5. Service Offerings and Instances
> 6. Security & Account limits

### MS最小配置
Management Server Requirements
+ Operating system:
	+ Preferred: RHEL 6.2+ 64-bit or CentOS 6.2+ 64-bit
	+ Also supported: RHEL and CentOS 5.4-5.x 64-bit
	+ Ubuntu 10.04 LTS
+ 64-bit x86 CPU (more for better performance)
+ 4 GB of memory
+ At least 250 GB of local disk (500GB recommended)
+ At least 1 NIC
+ Static IP address
+ Fully qualified domain name as returned by the hostname command

### 图片示例

![pic1][1]
---
![pic2][2]
---


## 配置(UI)


### 获取API Key

### 设置**site**变量 


#### 代码示例
```
chkconfig httpd on
chkconfig mysqld on
service cloudstackmanagement restart
```
...

[1]: https://raw.github.com/akinari/csdoc/master/screenshots/ss1.png "pic1 link" 
[2]: https://raw.github.com/akinari/csdoc/master/screenshots/ss1.png "pic2 link" 
