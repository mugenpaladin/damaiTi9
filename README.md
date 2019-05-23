# damaiTi9
基于Python和Selenium实现的ti9抢票脚本——
这是一名玩了10年dota依然还是卫士的dotaer为了信仰编写的Ti9抢票工具，仅能帮助你填写特权码并迅速完成第一个页面的提交工作

## 依赖
仅支持python3 + Chrome浏览器

安装依赖包
```
pip3 install -r requirements.txt
```
## 用法
1. 修改config.ini文件，保存你的信息
2. 执行脚本(首次执行会有防火墙提示，通过后关闭并重新运行)
```
python main.py
```
3. 根据网页提示登陆你的大麦账号
4. 成功登陆后会进入买票页面，页面会判断“确定”按钮是否可用而不断刷新，一旦可用会自动开始抢票
5. 继续手动操作
6. 如果进入了“订单确认”页面，会自动填写联系人信息并提交(注意，这里默认使用电子票方式订票)
(祝你抢票成功,我们上海见)
## 免责声明 
本脚本仅在浏览器端运行，源码公开可见，仅做研究使用，不得用于非法获利， 如产生法律纠纷与脚本作者无关!!!