## 简介
使用`Charles`抓包时，需要将主机ip/port手动填写到手机端。  
借助`Shadowrocket`等工具，使用http代理可以避免这个麻烦。
本项目是一个`utool`插件，用于快速生成一条`Shadowrocket`代理链接，扫码即可用。  
![预览](https://yunke-oss.oss-cn-hangzhou.aliyuncs.com/bff-basis-fe-sites/imgs/2022/11/08/1667879226466-0-%E4%BC%81%E4%B8%9A%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_f9df1441-2d29-4916-ba5d-ab228846c500.png)

## 使用
1. `utool`安装本插件
2. 主机开启`Charles`或其他抓包工具。
3. 呼出utool，使用`抓包`关键字唤起插件。
4. 手机打开`Shadowrocket`,扫码导入代理。
