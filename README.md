![聚鼎聚合支付](https://img-blog.csdnimg.cn/739044d2dd79492196eda56fba2fcb89.png)
# 欢迎使用 聚鼎聚合支付系统（四方系统） （使用指引-代理商版）  联系方式：Telegram：juding_henry

------

我们理解您需要更高效，更安全，更顺手，性能更高的四方聚合支付系统。<br/> 
您再也不想经历使用过程中系统突然卡顿，老是刷新不出来，多刷几下直接卡死的情况
您再也不想经历使用过程中要查一条数据，要找一个模块老是不知道该往哪里去找
您再也不想使用过程中，每天对账分析赚了多少钱都很开心，突然有一天账对不上，订单被异常回调。

现在来使用“聚鼎”吧！
> * 系统卡顿，一方面原因是，技术人员编写代码不过关，写的代码性能太低，效率太低，数据量大了之后就开始卡顿
另外一方面也是主要因素，过往情况下这一行的大部分系统都是用php编写的，php的程序性能相比其他语言低下，只是因为php门槛低，便于编写，所以很多人“捡烂便宜”，而我们聚鼎系统，使用golang+vue作为技术栈，前后端分离完成，性能更高，操作更流畅
> * 系统操作不顺手，老是不知道该到哪里去查数据，主要原因还是因为系统编写人员对行业了解不深，没有实际运营过四方聚合支付平台，不知道作为系统运营人员到底需要什么样的功能，导致很多地方想当然，而“聚鼎”的主要设计和开发团队成员是有实际经营四方聚合支付平台的经验的，知道同行业人员到底要什么
> * 使用系统过程中被莫名其妙偷撸？主要原因还是你们之前使用的系统是外界已经传播得很广的“烂大街”产品，源码满天飞，一方面别人已经在流传的代码中安插了后门，你只要使用别人就知道，想搞你的时候顺手就搞了，另一方面这些“烂大街”的系统大部分都是PHP编写的，PHP臭名远扬，漏洞第一好找，一不小心就被别人黑进去了，而“聚鼎”系统，因为后端采用golang语言开发，属于编译型语言，直接编译成可执行文件给你们部署到服务器，本身就自带安全性，而且系统开发过程中也做了防范黑客渗透的操作，第二方面，永远不卖源码，市面上使用的只可能是我们租出去的使用可执行文件部署的系统，所以不用担心系统被人研究或者被传播之后安插后门！


<h2>感谢您选择“聚鼎”，现在您可以开始使用<h2/>

@[toc]
### 1. 进入系统

**登陆进入系统，您会看到当前的统计视图，直观的展示了您的近期运营数据**
![在这里插入图片描述](https://img-blog.csdnimg.cn/1530fbf04bdb44a99fe0a2e2e7ccc411.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3Byb3RlY3R3ZWJzYWZl,size_16,color_FFFFFF,t_70)


### 2.  订单管理
> 查看订单是实时状态

![在这里插入图片描述](https://img-blog.csdnimg.cn/06194317618545768468f3803b2bc3df.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3Byb3RlY3R3ZWJzYWZl,size_16,color_FFFFFF,t_70)

### 3. 钱包管理
> 该菜单可以查看钱包余额

![在这里插入图片描述](https://img-blog.csdnimg.cn/64c7773d210349168a1f8a4a586bce19.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3Byb3RlY3R3ZWJzYWZl,size_16,color_FFFFFF,t_70)
 > 钱包日志记录，可以查看钱包的变动记录 包含订单入账，提现等

![在这里插入图片描述](https://img-blog.csdnimg.cn/c3b11255a164444585f7c55bd4301b45.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3Byb3RlY3R3ZWJzYWZl,size_16,color_FFFFFF,t_70)
> 商户提现，提现之前应该先在**结算管理**-**结算卡管理**里边添加结算卡

![在这里插入图片描述](https://img-blog.csdnimg.cn/8ff0dd1d54f942a987e9b9bbb275fad2.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3Byb3RlY3R3ZWJzYWZl,size_16,color_FFFFFF,t_70)


### 4. 结算管理（商户/代理商提现管理）
#### a. 结算卡管理
> 查看提交到系统的的结算卡

#### a. 提现记录
>  查看所有的提现记录

### 5. 订单管理
> 订单信息比较多，主要展示商户订单的动态，以及完成查单，补发回调，手动补单等操作，基本属于行业标准，自行探索即可

### 6. 系统其他支持
> *   系统支持对接三方API代付，为商户的提现实现API自动代付
>  * 系统支持商户通过对接API往后台添加结算卡信息
>   * 系统支持商户通过对接API往后台提交下发请求，但是如果平台未对接三方API代付的话，还是需要人工去打款并审核提现请求。只是给商户提供了便利，不用每笔提现都登录后台提交。
>   更多DIY的开发需求，可以联系“聚鼎”开发团队


### 本系统最终解释权归“聚鼎”聚合支付开发团队所有，所有有权使用本系统的主体，均以获得授权并且租用的方式使用，所有源码永远不外泄，如市面上出现其他茂名系统，并因此导致的经济损失于本团队无关，“聚鼎”聚合支付 只此一家，别无分号！

