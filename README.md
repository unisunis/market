Android App 一键商业化 
 ----------------------
 目前支持商业化模型自定义投放、卡密系统、广点通(优量汇)、穿山甲广告联盟、百度ssp、极光推送
 ---------
 项目已经以服务的形式部署，使用请移步
 ---
 [9A App商业化](https://ianpei.com)


一、前置条件
------------

1、请确保需要商业化的Android App没有自校验

2、请确保需要商业化的Android App有support v4包的支持

3、在进行第三方商业化模型接入时，请确原App没有手动进行过该商业化模型SDK的接入

二、添加母包
------------

登录到9A控制台，选择”我的母包”，点击“添加母包”
![image](https://github.com/ianpei/market/blob/master/pic/1.jpg) 
![image](https://github.com/ianpei/market/blob/master/pic/2.jpg) 
上传过程中请勿关闭当前页面

三、派生
------------

点击“我的母包”列表种的派生按钮
![image](https://github.com/ianpei/market/blob/master/pic/3.jpg) 
选择需要接入的模型，然后点击构建按钮
![image](https://github.com/ianpei/market/blob/master/pic/4.jpg) 
![image](https://github.com/ianpei/market/blob/master/pic/5.jpg) 
因系统任务负载原因有有快有慢，大约需要3分钟左右

四、配置运营位
------------
![image](https://github.com/ianpei/market/blob/master/pic/6.jpg) 
点击“构建记录”列表或者“派生包管理”中的“配置”按钮，选择相应的页面进行配参关联


对于系统模型“自定义投放”或者“卡密系统”的配参分别由“系统模型/自定义投放”和“系统模型/卡密系统”中创建。
![image](https://github.com/ianpei/market/blob/master/pic/7.jpg) 

对于三方模型，则由模型相对应的官方平台中创建，并填添加到9A配参管理中

![image](https://github.com/ianpei/market/blob/master/pic/8.jpg) 
