# 特点
- 高 I/O

# 性能测试
- I/O 负载：当前的配置可以处理多大的并发
- 同一域名下浏览器的并发连接数限制是多少？主域名和子域名是不是一样的？

- 硬盘：7200 转 / 15000 转
- 文件系统：inode size 大小，决定了可以存储图片的数量


## 文件系统
- 分布式文件系统
 - kubernetes 分布式文件系统？
- CDN


---


# 图片上传
- 新上传的图片存储在当前年份目录下

# 图片同步
- rsync：文件数量特别大的时候，扫描耗时太大，可能要几个小时
- inotify + ftp

# 图片下载
- 按路径配置 nginx ingress /2017/12/


---


# 存储
- 路径 hash
- nginx hash 分流
- 图片修改

/2017/
/2018/

## NFS
- 挂载多台 nfs

### NFS 缺点


## MySQL
- 相对路径：/upload/2017/12/xxx.jpg


---


# 图片尺寸

## 头像
- 100 x 100

## 手机 


# 图片大小
- 小于 500K


- 水印
- 缩略图
- 防盗链

---

# 缓存


# 参考文献
- [图片服务器的架构演进](https://www.cnblogs.com/1995hxt/p/6096710.html)
