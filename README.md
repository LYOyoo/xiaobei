# 小北每天自动健康打卡
## 该代码可直接运行在本地，只需要将2.py中代码复制到本地和修改账号密码即可，每天得手动运行该程序，如需每天自动打卡，请往下阅读
## **首先准备好一个github账号,注册链接[github](https://github.com/)**
## 该步骤非必须，注册server酱做签到成功提醒作用，如不需要请直接跳到Github Actions说明中
### 自行去server酱官网注册账号[server酱](http://sc.ftqq.com/),注册成功后在发送消息中得到SCKEY值
# Github Actions说明
## 一、Fork此仓库
![](http://tu.yaohuo.me/imgs/2020/06/f059fe73afb4ef5f.png)
## 二、设置账号密码

添加名为**XIAOBEI_USERNAME**、**XIAOBEI_PASSWORD**、**XIAOBEI_SCKEY**的变量  
值分别为**账号**、**密码**、**server酱SCKEY值**（若不知道什么是server酱该空可不填）  
![](http://tu.yaohuo.me/imgs/2020/06/748bf9c0ca6143cd.png)
![](https://i.loli.net/2021/02/05/KrHSRJk3xYAdGy5.png)
## 三、启用Action
1 点击**Action**，再点击**I understand my workflows, go ahead and enable them**  
![](http://tu.yaohuo.me/imgs/2020/06/34ca160c972b9927.png)

2，点击**code**，再点击笔,在第十行随便输入东西，然后往下滑动点击commint change
![步骤1](https://i.loli.net/2021/02/05/qwFmINBZp3fgiQP.png)
![步骤2](https://i.loli.net/2021/02/05/irWEo63dkwpAPyc.png)
![步骤3](https://i.loli.net/2021/02/05/gAuwbIxyaJdWPYe.png)
## 四、查看运行结果
Actions  > xioabei daka > build  
能看到如下图所示，表示成功  
![](http://tu.yaohuo.me/imgs/2020/06/b9e596c99f3835e0.png)

此后，将会在每天10:00和22:00各签到一次  
若有需求，可以在[.github/workflows/run.yml]中自行修改 
