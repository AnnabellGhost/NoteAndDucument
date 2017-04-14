懒星人项目页面文件夹及路由命名
=====

* 需要OTP验证的采用如下子路由
    * child router:
        * /otp

-----

* 首页  IndexPage 
    * router : index

-----

* 选择计划类型页 PlanTypes
    * router : plantypes

-----

* 30天内待执行计划页 PlanList
    * router : planlist 

-----

* 计划详情页 PlanDetail
    * router : plandetail

-----

* 选择信用卡页 SelectCreditCard
    * router:selectcredit

-----

* 信用卡转出 TransferOutCreaditCard
    * router : creditout
        * child router : 
            * /paylimits    ` <PayLimits />`

-----

* 转出 TransferOut
    * router  transferout  
        * child router:
            * /amount
            * /frequency 
            * /contacts     ` <SelectContacts />`
            * /paylimits    

-----

* 转入 TransferIn
    * router : transferin

-----



* 结果页 Result
    * router : result
    
-----

**命名应该没问题，但是子路由我不太确定。会及时更新的**

>Created by Zhang Xingping on 20170405,supervised by Xu Jia.
