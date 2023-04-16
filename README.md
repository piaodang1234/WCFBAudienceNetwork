# FBAudienceNetwork （pod超时解决方案）
镜像文件，避免翻墙、pod超时， 原文件地址为：https://developers.facebook.com/resources/FBAudienceNetwork-x.x.x.zip

# 使用
需要修改源就可以下载了

1.转到 /Users/用户名/.cocoapods/repos/master/Specs

2.搜索FBAudienceNetwork.podspec.json 能看到很多版本的 FBAudienceNetwork 

3.打开对应版本的 FBAudienceNetwork.podspec.json 

4.修改 FBAudienceNetwork.podspec.json
> 实例实例的是该repo下 FBAudienceNetwork-6.12.0.zip版本，若没有对应版本可提交mr或issue

```
 "source": {
      "http": "https://github.com/piaodang1234/WCFBAudienceNetwork/blob/dev/FBAudienceNetwork-6.12.0.zip?raw=true"
 },
```
5. pod install, 直接安装即可，避免pod update导致cocoapods repo文件修复被覆盖
