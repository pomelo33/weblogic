# weblogic
weblogic常用脚本

### 文件描述
- change_passwd:更改密码



#### 使用方法
通过weblogic的t3协议进行修改,具体查看各目录对应README.md
```
/weblogic/wlserver_12.2/wlserver/common/bin/wlst.sh ${python_filename} username passwd t3://127.0.0.1:7001

```

### 版本
- 更新日期(20201126)
更新内容:  
1.更改用户密码脚本  
2.批量增加筛选器脚本