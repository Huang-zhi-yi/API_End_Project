# API_机器学习与人工智能期末项目
![产品文档介绍图](https://www.lucaszy.com/wp-content/uploads/2020/07/1593144680797-b9d57d8c2128fef2.png)

## 一.需求概述
  ### （1）产品背景：
        随着移动互联网的发展与普及，线上沟通变得越来越容易，现代人对手机的依赖越来越严重，
	人与人之间面对面的交流一定程度上在减少，人们更加愿意与机器聊天。
	与此同时，情绪的变化也会影响用户进食的数量、类别，其中不乏一些人因为情绪不佳而暴饮暴食。
	因此一款根据用户心情为他推荐合适的餐厅具有人文关怀的app是我设计的初衷
  ### （2）产品市场：
          经过调查发现，目前市场上智能聊天机器人和与情绪识别有关的api接口已经较为成熟，准确率相对较高。
	  但是，智能聊天机器人与美食推荐相结合的app少之又少。另外，目前美食类app，大多都依赖冰冷的算法，缺乏人性化。
  ###  (3)市场概述：
   #### 1.全国市场概述：
      目前美食推荐类APP已经基本能满足人们的基本生活需求，但是在推荐方式还没有做进一步的细分，
      只是停留在基于大数据基于用户以往的使用记录而做推荐并未没有从用户所处的环境等去进一步的分析。
      而目前智能聊天机器人已经相对成熟，但细分某一领域聊天机器人仍需要使用者做进一步的机器学习
   #### 2.市场特征：
     - 智能聊天机器人市场前景依然比较广阔，针对某一细分领域的机器人会是未来的趋势
     - 基于大数据而推荐的美食APP趋于饱和，但基于人性具有人文关怀的美食推荐app相对较少.
     - 自然语言处理技术发展较好，对语句的情绪识别能比较准确
   ####  3.发展优势：
          * 目前智能聊天机器人与美食推荐结合的app较少，竞争小，市场前景明朗
          * 具有人文关怀的美食类app少之又少，在这个城市人越来越感到孤独的趋势下，人性化app是未来 的发展趋势
          * 着重在人当前心情、当前时间而作的美食推荐市场上少之又少，发展前景良好
 ## 二. 价值宣言
   ### (1)一句话宣言：
    根据用户与机器人的聊天对话识别出你当前的心情，为用户推荐适合当前心情的餐厅。
   ### (2)一分钟版本：
    目前市场上餐饮推荐APP只是根据用户的点击，搜索记录来为用户推荐餐厅，并没有具有根据用户当时的心情来为用户推荐餐厅，
    这样可能导致推荐的餐厅未必是用户所喜欢的。臻选美食app使用到的智能聊天机器人、情绪识别api与高德地图周边搜索api，
    这些api的综合运用能够帮助用户选择适合当前心境的餐厅。
 ## 三. 用户分析
   ### (1) 用户痛点：
      * 推荐的餐厅不是用户想要的
      * 用户食欲非常受心情所影响
      * 内心害怕孤独但不知道找谁聊天
   ### （2）目标用户：
        主要用户：大城市中20~35岁较为年轻群体
   ###  (3)  用户画像及使用场景：
   #### 1.  
   ![用户画像1](https://www.lucaszy.com/wp-content/uploads/2020/07/1593243537420-8ee8ee4577834386.png)
        
	使用场景一：欣悦已经连续加班4天，周五下午临下班前接到上级主管的要求，
	今晚必须把产品设计稿做完，孤独又无助的她打开臻选美食app，与机器人闲聊了几句，
	app为她推选出附近最好欢迎的甜品店。
   #### 2.
   ![用户画像2](https://www.lucaszy.com/wp-content/uploads/2020/07/1593247600597-bea1558d77ed640d.png)
        
	使用场景二：盈影身上有着几个重要比赛需要去准备，但是今天又收到期末作业的要求，
	她面临双重压力，无助而又孤独的她这时打开臻选美食app，机器人简单与她闲聊后，
	为她推荐附近最受欢迎的麻辣店。
   ### (4)核心价值及API价值
   ![API加值](https://www.lucaszy.com/wp-content/uploads/2020/07/1593266603469-41dbbc25e6ad22e7.png)
   ## 四. API使用及其说明
   ### (1) 需求列表及使用的API介绍、优先级
   ![使用的API介绍](https://www.lucaszy.com/wp-content/uploads/2020/07/1593266633064-ce7126c712c55bcf-1024x116.png)
   ### (2)人工智能概率性与用户痛点
   ![人工智能概率性与用户痛点](https://www.lucaszy.com/wp-content/uploads/2020/07/人工智能概率性与用户痛点.png)
   ### (3)API使用价格
   ![机器人价格](https://www.lucaszy.com/wp-content/uploads/2020/07/机器人价格.png)
   ![百度和高德价格](https://www.lucaszy.com/wp-content/uploads/2020/07/百度和高德api.png)
   ### (4)API的运用
   #### 1. 图灵智能聊天机器人API
   ##### HTTP方法：POST
   ##### 请求URL：http://openapi.tuling123.com/openapi/api/v2
   [API输入输出链接](https://blog.csdn.net/lucaszy/article/details/107146697)
   #### 2. 情绪识别
   ##### 百度AI开放平台-对话情绪识别api
   ##### 接口描述
	针对用户日常沟通文本背后所蕴含情绪的一种直观检测，可自动识别出当前会话者所表现出的一级和二级细分情绪类别及其置信度，
	针对正面和负面的情绪，还可给出参考回复话术。帮助企业更全面地把握产品服务质量、监控客户服务质量。在自动监控中如果发现有负面情绪出现，
	可以及时介入人工处理，帮助在有限的人工客服条件下，降低客户流失。
   ##### HTTP方法: POST
   ##### 请求URL: https://aip.baidubce.com/rpc/2.0/nlp/v1/emotion
   [API输入输出链接](https://blog.csdn.net/lucaszy/article/details/107141785)
   #### 3.周边美食推荐 
   ##### 高德地图开放平台-周边搜索POI
   ##### 接口描述：在用户传入经纬度坐标点附近，在设定的范围内，按照关键字或POI类型搜索
   ##### 请求URL:https://restapi.amap.com/v3/place/around?parameters|
   ##### HTTP方式:GET
   [API输入输出链接](https://blog.csdn.net/lucaszy/article/details/107142872)
   ### (5)API使用风险评估
     1. 智能聊天机器人可能会出现无法理解用户的表达：需要不断完善及补充语言库，不断强化机器学习，提高机器人理解力
     2. 百度对话情绪识别会有中性的返回值，对于这种涉及的范围广的返回项无法精准判断用户的真实情绪，
     因此导致该选项的美食推荐不准确。解决方案：加入时间推荐等尽可能覆盖多种推荐，以达到满足用户需求
     3. 推荐餐厅类别不是用户所喜欢的：设置下拉选择框让用户自己选择餐厅类别
   ## 五.产品功能介绍
      1. 功能介绍(结构图)
   ![结构图](https://www.lucaszy.com/wp-content/uploads/2020/07/%E5%8A%9F%E8%83%BD%E5%9B%BE-1-1024x427.png)
      2. 数据流程介绍(数据流程图)
   ![数据流程图](https://www.lucaszy.com/wp-content/uploads/2020/07/%E6%95%B0%E6%8D%AE%E6%B5%81%E7%A8%8B%E5%9B%BE-1024x233.png)
   ## 六.产品竞品分析
   ### (1) 竞品的战略定位
   ![竞品的战略定位](https://www.lucaszy.com/wp-content/uploads/2020/07/竞品分析.png)
   ### (2) 竞品产品结构图
   #### 口碑APP
   ![口碑APP](https://www.lucaszy.com/wp-content/uploads/2020/07/口碑.png)
   #### 大众点评
   ![大众点评](https://www.lucaszy.com/wp-content/uploads/2020/07/大众点评产品结构图.png)
   ## 七.产品未来发展线路构思
   ### (1) 产品迭代过程
   ![产品迭代过程](https://www.lucaszy.com/wp-content/uploads/2020/07/%E8%BF%AD%E4%BB%A3%E8%BF%87%E7%A8%8B.png)
   ### (2) 产品盈利模式
   ![产品盈利模式](https://www.lucaszy.com/wp-content/uploads/2020/07/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20200704165016.png)
   ## 八.产品原型介绍及交互设计
   [点击这里查看原型交互](https://modao.cc/app/cd9f1d6fb16686fcdd326aadbf3ed87093442458?simulator_type=device&sticky)
   ### (1)启动页面
   ![启动页](https://www.lucaszy.com/wp-content/uploads/2020/07/1_启动页.png)
   ### (2)核心页面
   ![聊天页面](https://www.lucaszy.com/wp-content/uploads/2020/07/7_聊天页面.png)
   ![聊天页面-输入界面](https://www.lucaszy.com/wp-content/uploads/2020/07/3_聊天页面-输入框.png)
   ![主页](https://www.lucaszy.com/wp-content/uploads/2020/07/6_主页.png)
   
   ### (3)主要页面
   ![导航界面](https://www.lucaszy.com/wp-content/uploads/2020/07/4_导航页.png)
   ![我的](https://www.lucaszy.com/wp-content/uploads/2020/07/5_我的.png)	
   	
   ## 九.数据使用及其价值
   ![数据使用及其价值](https://www.lucaszy.com/wp-content/uploads/2020/07/%E6%95%B0%E6%8D%AE%E4%BB%B7%E5%80%BC%E5%8F%8A%E7%94%A8%E9%80%94.png)
