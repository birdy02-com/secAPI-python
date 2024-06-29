# secAPI

    这是一个为个人工作开发的协助平台，有分析网页、分析ip、分析域名、ICP等查询的功能
    
    这是一个 v1.2 版本，在这之前还有 Python+Sqlite3的 版本
    目前已经将代码迁移到Golang语言中，Python版本的更新将变得缓慢

## 部署
    开发环境：Python 3.10.11 + MySQL 5.7
    
    1. 请在Config/__init__.py中配置好数据库配置信息
    2. 运行 python init.py 实现初始化
    3. 由于这只是个API，图形化界面调用暂定使用以下平台来使用

林乐天的协助平台，https://tools.birdy02.com，将会开发一个 api 更换功能

## 文件说明
    Append_User.py 文件用来新增用户，用户信息需要在文件中修改
    test.py 可以看到平台中有的漏洞数量和漏洞类型有哪些


## 联系我
如果有好的建议或者一起更新，请联系我
<img src="https://github.com/Lin-Letian/secAPI/blob/main/Config/WeChatCode.jpg">
