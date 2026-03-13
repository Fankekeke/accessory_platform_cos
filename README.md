### 基于SpringBoot + Vue的计算机配件购买平台.

电脑配件电商平台、计算机硬件购物系统、数码配件交易平台

####  商铺管理员功能模块介绍：
###### 商铺信息：维护店铺名称、logo、简介及营业状态等资料。我的商品：管理本店上架的计算机配件，支持编辑与下架。商铺订单：处理用户下单、发货及售后相关订单操作。订单评价：查看顾客对商品质量与服务的评分和留言。消息回复：及时响应用户咨询或平台发送的站内通知。商铺审核：提交资质材料，配合完成平台入驻审核流程。用户沟通：与买家在线交流，解答产品或订单问题。

#### 系统管理员功能模块介绍：
###### 收货地址管理：监管用户收货地址，确保配送信息规范有效。商铺审核管理：审核新申请商铺资质，决定是否批准上线。公告信息：发布平台规则、促销活动或系统维护通知。商品管理：监督全平台计算机配件信息，处理违规商品。用户评价：审核并管理用户对商品和商铺的评论内容。消息管理：统一处理平台与用户、商铺之间的通信记录。订单管理：监控所有交易订单状态，协调异常处理。贴子管理：审核论坛发帖，维护社区内容健康合规。商铺管理：管理所有入驻商铺资料，支持冻结或推荐操作。用户管理：维护用户账号安全，处理举报或封禁操作。商品类型：配置配件分类，如CPU、内存、显卡、电源等。

####  用户功能模块介绍：
###### 商铺详情：查看商家信息、主营配件、评分及联系方式。查看公告：阅读平台或商铺发布的最新通知与活动信息。搜索商品：通过关键词快速查找所需计算机配件产品。系统论坛：参与技术讨论、装机分享或配件使用交流。发帖回复：在社区中发表观点或回复他人帖子内容。用户订单：查看历史订单状态、物流信息及售后服务。加入购物车：将心仪配件暂存购物车，便于批量结算。收货地址管理：添加、编辑或删除多个收货地址信息。订单评价：对已完成的配件订单进行评分与文字反馈。联系客服：通过在线方式向商铺或平台客服寻求帮助。

#### 安装环境

JAVA 环境 

Node.js环境 [https://nodejs.org/en/] 选择14.17

Yarn 打开cmd， 输入npm install -g yarn !!!必须安装完毕nodejs

Mysql 数据库 [https://blog.csdn.net/qq_40303031/article/details/88935262] 一定要把账户和密码记住

redis

Idea 编译器 [https://blog.csdn.net/weixin_44505194/article/details/104452880]

WebStorm OR VScode 编译器 [https://www.jianshu.com/p/d63b5bae9dff]

#### 采用技术及功能

后端：SpringBoot、MybatisPlus、MySQL、Redis、
前端：Vue、Apex、Antd、Axios
报表：Spread.js

平台前端：vue(框架) + vuex(全局缓存) + rue-router(路由) + axios(请求插件) + apex(图表)  + antd-ui(ui组件)

平台后台：springboot(框架) + redis(缓存中间件) + shiro(权限中间件) + mybatisplus(orm) + restful风格接口 + mysql(数据库)

开发环境：windows10 or windows7 ， vscode or webstorm ， idea + lambok

#### 商铺管理员
商铺信息、我的商品、商铺订单、订单评价、消息回复、商铺审核、用户沟通

#### 系统管理员
收货地址管理、商铺审核管理、公告信息、商品管理、用户评价、消息管理、订单管理、贴子管理、商铺管理、用户管理、商品类型

#### 用户
商铺详情、查看公告、搜索商品、系统论坛、发帖回复、用户订单、加入购物车、收货地址管理、订单评价、联系客服


#### 前台启动方式
安装所需文件 yarn install 
运行 yarn run dev

#### 默认后台账户密码
[管理员]
admin
1234qwer

[商家]
test1
1234qwer

[用户]
小程序登录

#### 项目截图

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486564347.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486456478.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486548843.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486431158.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486525733.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486413597.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486506984.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486399413.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486490130.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486379063.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486468710.png)

|  |  |
|---------------------|---------------------|
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484796733.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484676820.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484780924.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484667620.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484764760.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484579710.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484746086.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484568568.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484701584.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484539246.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486308010.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484310133.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733486290210.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484291183.png) | 
| ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733484262993.png) | ![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/1733485631990.png) | 


#### 演示视频

暂无

#### 获取方式

Email: fan1ke2ke@gmail.com

WeChat: `Storm_Berserker`

`附带部署与讲解服务，因为要恰饭资源非免费，伸手党勿扰，谢谢理解😭`

> 1.项目纯原创，不做二手贩子 2.一次购买终身有效 3.项目讲解持续到答辩结束 4.非常负责的答辩指导 5.**黑奴价格**

> 项目部署调试不好包退！功能逻辑没讲明白包退！

![](https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/work/936e9baf53eb9a217af4f89c616dc19.png)

#### 其它资源

[2025年-答辩顺利通过-客户评价🍜](https://berserker287.github.io/2025/06/18/2025%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2024年-答辩顺利通过-客户评价👻](https://berserker287.github.io/2024/06/06/2024%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2023年-答辩顺利通过-客户评价🐢](https://berserker287.github.io/2023/06/14/2023%E5%B9%B4%E7%AD%94%E8%BE%A9%E9%A1%BA%E5%88%A9%E9%80%9A%E8%BF%87/)

[2022年-答辩通过率100%-客户评价🐣](https://berserker287.github.io/2022/05/25/%E9%A1%B9%E7%9B%AE%E4%BA%A4%E6%98%93%E8%AE%B0%E5%BD%95/)

[毕业答辩导师提问的高频问题](https://berserker287.github.io/2023/06/13/%E6%AF%95%E4%B8%9A%E7%AD%94%E8%BE%A9%E5%AF%BC%E5%B8%88%E6%8F%90%E9%97%AE%E7%9A%84%E9%AB%98%E9%A2%91%E9%97%AE%E9%A2%98/)

[50个高频答辩问题-技术篇](https://berserker287.github.io/2023/06/13/50%E4%B8%AA%E9%AB%98%E9%A2%91%E7%AD%94%E8%BE%A9%E9%97%AE%E9%A2%98-%E6%8A%80%E6%9C%AF%E7%AF%87/)

[计算机毕设答辩时都会问到哪些问题？](https://www.zhihu.com/question/31020988)

[计算机专业毕业答辩小tips](https://zhuanlan.zhihu.com/p/145911029)

#### 接JAVAWEB毕设，纯原创，价格公道，诚信第一

`网站建设、小程序、H5、APP、各种系统 选题+开题报告+任务书+程序定制+安装调试+项目讲解+论文+答辩PPT`

More info: [悲伤的橘子树](https://berserker287.github.io/)

<p><img align="center" src="https://fank-bucket-oss.oss-cn-beijing.aliyuncs.com/img/%E5%90%88%E4%BD%9C%E7%89%A9%E6%96%99%E6%A0%B7%E5%BC%8F%20(3).png" alt="fankekeke" /></p>
