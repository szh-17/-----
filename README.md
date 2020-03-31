#需求规格说明书
##0. 目录
- 需求规格说明书
    - 0. 目录
    - 1. 引言
        - 1.1 目的
        - 1.2 预期读者
        - 1.3 背景
        - 1.4 定义
        - 1.5 参考文献
    - 2. 项目概述
        - 2.1 产品背景
        - 2.2 产品描述
        - 2.3 产品功能
        - 2.4 未来市场
        - 2.5 用户群体
        - 2.6 用户场景
        - 2.7 假设与约束
            - 2.7.1 假设
            - 2.7.2 约束
    - 3. 具体需求
        - 3.1 外部接口需求
            - 3.1.1 用户接口
            - 3.1.2 硬件接口
            - 3.1.3 软件接口
            - 3.1.4 通信接口
        - 3.2 功能需求
            - 3.2.1 界面设计
            - 3.2.2 UML类图
        - 3.3 性能需求
            - 3.3.1 精度需求
            - 3.3.2 静态数量化需求
            - 3.3.3 动态数量化需求
        - 3.4 属性
            - 3.4.1 可用性
            - 3.4.2 安全性
            - 3.4.3 可维护性
        - 4. 验证验收标准
            - 4.1 文档验收标准
            - 4.2 软件验收标准
            - 4.3 界面验收标准
            - 4.4 功能验收标准
##1. 引言

###1.1 目的

为准确描述软件定位，明确软件需求，减少开发工作以及便于软件升级和产品转移撰写本文档
本篇软件规格需求说眀书详细描述了“用心聚”这一软件的用户需求、软件规格等内容。方便用户深入
了解该软件，同时也是开发者进行开发、测试以及软件验收的主要依据

###1.2 预期读者

- 项目经理:项目经理可以根据本文档了解产品的实现预期以及产品的诸多细节，便于进行项目管理
- 设计员:根据软件的需求有针对性地设计出各种框架，其中包括数据库设计、UⅠ界面设计等
- 程序员:程序员可以根据本文档详细阐述的软件功能进行软件开发编码
- 测试员:测试员可以通过本文档阐述功能描述进行功能测试，测试接口以及各种细节。
- 用户:用户可以根据本篇文档了解产品的出发点以及软件的功能，有助于用户确定该软件是否
满足其需求以及是否解决痛点。协助用户与开发者更好地协商讨论。

本文档用于指导软件开发者于软件工程实践课程中开发软件项目的过程，通过规范软件项目承担
团队的开发过程达到提高软件质量，降低维护成本的目的。开发者应根据本文档进行软件开发和编制
软件开发文档。本指南是对软件项目承担单位的基本要求。在进行具体软件开发时，开发者可根据实
际情况采编写，但必须提供双方约定的文档，文档中约定的内容必须描述清楚。

###1.3 背景

软件名称：用心聚
项目开发者：福州大学2017级软件工程 “用心聚落步”小组
本项目经过大量问卷充分了解潜在用户需求，从用户的需求以及对于当前市场上产品不能解决的
用户痛点出发，经过组内讨论从而确定了软件定位和主要功能。本产品主要面向。。。。

###1.4 定义

| 序号|缩写| 定义  |
|:------:|:-----:|-----|
|1 | App | 应用程序，'Application'，一般指手机软件。 |
|2| Android|Android 是一种基于 Linux 的自由及开放源代码的操作系统，主要使用于移动设备，如智能手机和平板电脑，由 Google 公司和开放手机联盟领导及开发。|
|3|BUG|	狭义概念是指软件程序的漏洞或缺陷，广义概念除此之外还包括测试工程师或用户所发现和提出的软件可改进的细节、或与需求文档存在差异的功能实现等。|

###1.5 参考文献

【1】《GB9385-288计算机软件需求规格说明规范》
【2】《GB9386-28计算机软件测试文档编制规范》

##2. 项目概述

###2.1 产品背景

- 现如今就业是一大难题，就业形势日益严峻，许多人对就业深感忧心。
- 有些人有着创业的想法却苦于无从下手，该软件致力于为用户便捷，快速，高效的找到自己的团队。
- 根据国家统计局显示，2019年1-12月大城市的失业率逐年增加。许多失业者有意图有想法做自己的创业项目，而且国家对其也有政策支持。
- 但是最大的难题是无法找到与自己有相同兴趣爱好和专长并且相创业的小伙伴，这款软件还融合一系列的聊天系统,我们的目标是把最合适的人放在最合适的岗位上。
- 在校大学生也正在为毕业后因为没有好的履历而害怕找不到工作，所以我们的组队功能将实现2-8人组队的效果，这样他们可以通过参加比赛得奖，并且得到实战的机会，达到履历丰富的效果。

###2.2 产品描述

- 1.用心聚一款完全针对用户的软件，用于收集用户信息，将求职者与企业配对的软件；
- 2.一款针对现在的失业人群而做的一款软件, 想进行自主创业但是没有门路和渠道找到小伙伴的软件，填写你的专业和资料，自动匹配的适合你的创业小组。
- 3.我们也很多需要组队参加比赛的比赛而服务,为有意愿参加比赛的在校大学生寻找一位知音人。（现阶段必须完成）

###2.3 产品功能

- 初期:
  - 网页实现浏览功能，推荐比赛项目，公告一些获奖团队信息，这样有利于推广而且也为相应的团队打响了名气。
  - app实现组队功能，自主创建小队（人数受限），发布招募队员页面，系统自分配功能，自由选择小队功能。注册页实现实名注册。聊天功能。
- 中期：
  - 
- 后期:
  - 1.app设置了搜索推荐功能，为您推荐了当下热门的职业方向，搜素相关职业的关键字，便于用户查找分析。
  - 2.app设置了定位系统，用户可以选择自己想就职的城市和地区。
  - 3.增加了就职方向选择功能，并推荐相关群聊，方便对该职业就业情况的了解。
  - 4.增加了分区选择功能，用户可以从大概方向选择到具体擅长技术
![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331120741806-1655098608.png)

###2.4 未来市场

本产品针对失业而且有意向创业的用户，但是找不到途径和志同道合的其他小伙伴，具体到（）领域。
根据系统自动分配创业小组或用户自己选择小组，方便用户快速获取创业小组资料以及选择最适合自己的创业小组。

###2.5 用户群体

- 1.失业者
- 2.有意向创业的用户
- 3.有意向参加各类比赛的在校大学生

###2.6 用户场景

- ![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331121121953-2038534843.png)


###2.7 假设与约束
####2.7.1 假设

- 人员调配:假设在开发过程中组长能够合理调度人员,分配任务合理,组员在都能在交稿日完成自己的任务。
- 团队协作:假设小组如家,每位组员都能够把自己当做小组内的一份子,每位组员心里都报有一颗为自己做事的心态。
- 

####2.7.2 约束

- 人员约束：团队成员皆为大三学生，共 8 人
- 管理约束: 本次开发实行以一人担任组长，分工合作的模式进行。力求每个人的分工涉及开发过程中的所有流程，并按照进度表进行，开发过程遇到的问题通过小组会议得到一致解决
- 技术约束：小组成员在相关技术水平方面存在一定的欠缺，缺乏相关的项目经验，需要在开发中不断学习新的技术.
- 时间约束：本项目开发周期短，时间相对紧张，需要开发者合理规划时间，做到多项任务并发
- 安全和保密考虑:对于用户个人信息的存储保护，对于数据库结构合理性、安全性需要严谨的考虑。
- 其他约束：开发期间，小组成员还有其他科目的学习任务，将对项目进度造成一定影响

##3. 具体需求
###3.1 外部接口需求
####3.1.1 用户接口
- 无特殊需求
####3.1.2 硬件接口
- 无特殊需求
####3.1.3 软件接口
- 无特殊需求
####3.1.4 通信接口
- 无特殊需求
###3.2 功能需求
####3.2.1 界面设计

####3.2.2 UML类图
![](https://img2020.cnblogs.com/blog/1969029/202003/1969029-20200331134827491-248395620.png)


###3.3 性能需求
####3.3.1 精度需求

- 账号:帐户,不超过16个字符
- 用户密码：密码由6-20个字符组成。密码只能由数字、英文字符、下划线组成。不可为空。
- 用户名：长度不超过20个字符，不包含中文、大写英文、小写英文、数字、下划线及其组合以外的特殊字符。不可为空。
- 专业：长度不超过16个字符，不可为空
- 电子邮箱:符合邮箱的正则表达式。包含@字符。
- 想参加的比赛名称：长度不超过16个字符。可包含中文、大写英文、小写英文、数字。不可为空。
- 小组名：长度不超过8个字符，不可为空
- 参加比赛名称：长度不超过16个字符。可包含中文、大写英文、小写英文、数字。不可为空。

####3.3.2 静态数量化需求
- 待定
###3.4 属性
####3.4.1 可用性

- 并发性：支持多用户同时在线。
- 易操作：本产品操作简单，任意使用。
- 稳定性：在产品的升级中修复出现的bug，使系统越来越稳定。
- 界面友好：本软件产品界面对用户友好、直观。

####3.4.2 安全性

- 权限限制：本产品软件的数据库中对普通用户的访问控制设置权限，以防消息泄露。
- 最小权限原则：降低代码在被恶意用户利用时,造成的损失。
- 备份与恢复：本产品软件数据库采用记录生产日志文件、个人信誉度备份等方式保证信息安全。
- 审计：对于服务端每一次非自动的数据库操作进行审计记录，方便事后追究，控制数据泄露。

####3.4.3 可维护性

- 用户反馈：提供用户反馈途径，及时收集用户反馈的各种信息，方便软件维护。
- 更新：在每次更新过程中，修复系统出现的bug，实现软件的维护。
- 编码规范：本产品软件的开发编码按照事先约定好的编码规范进行，便于软件维护

###4. 验证验收标准
<table width="3202.93" border="0" cellpadding="0" cellspacing="0" style='width:2402.20pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="142.67" style='mso-width-source:userset;mso-width-alt:4565;'/>
   <col width="145.53" style='mso-width-source:userset;mso-width-alt:4657;'/>
   <col width="165.80" style='mso-width-source:userset;mso-width-alt:5305;'/>
   <col width="258.33" style='mso-width-source:userset;mso-width-alt:8266;'/>
   <col width="254.47" style='mso-width-source:userset;mso-width-alt:8142;'/>
   <col width="173.47" style='mso-width-source:userset;mso-width-alt:5550;'/>
   <col width="103.13" span="20" style='mso-width-source:userset;mso-width-alt:3300;'/>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl65" height="22" width="142.67" style='height:16.50pt;width:107.00pt;' x:str>测试功能</td>
    <td class="xl65" width="145.53" style='width:109.15pt;' x:str>测试项</td>
    <td class="xl66" width="165.80" style='width:124.35pt;' x:str>输入<font class="font27">/</font><font class="font1">操作</font></td>
    <td class="xl67" width="258.33" style='width:193.75pt;' x:str>检验点</td>
    <td class="xl65" width="254.47" style='width:190.85pt;' x:str>预期结果</td>
    <td class="xl65" width="173.47" style='width:130.10pt;' x:str>验收情况</td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
    <td class="xl68" width="103.13" style='width:77.35pt;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl69" height="270" rowspan="6" style='height:202.50pt;border-right:.5pt solid #000000;border-bottom:none;' x:str>登录页面</td>
    <td class="xl70" rowspan="5" style='border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2">本地功能</font></td>
    <td class="xl71" x:str>点击账号和密码的文本框</td>
    <td class="xl72" x:str>账号密码键入提示</td>
    <td class="xl73" x:str>账号和密码的文本框显示键入提示且可键入</td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl72" x:str>键入账号文本框，输入文本</td>
    <td class="xl72" x:str><font class="font2">账号为手机号</font></td>
    <td class="xl72" x:str><font class="font2">对非法文本进行识别并提示</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl72" x:str><font class="font2">键入密码文本框，输入文本</font></td>
    <td class="xl72" x:str><font class="font2">密码长度6-20位（设置边界），可为数字，英文，下划线组合</font></td>
    <td class="xl72" x:str><font class="font2">判断长度并对非法文本进行识别并提示</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl72" x:str><font class="font2">点击注册</font></td>
    <td class="xl72" x:str><font class="font2">能否进入注册页面</font></td>
    <td class="xl72" x:str><font class="font2">进入注册页面</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl72" x:str><font class="font2">点击忘记密码</font></td>
    <td class="xl72" x:str><font class="font2">能否进入修改密码页面</font></td>
    <td class="xl72" x:str><font class="font2">进入密码修改页面</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl76" x:str><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>登录功能</td>
    <td class="xl76" x:str><font class="font2">点击登入</font></td>
    <td class="xl76" x:str><font class="font2">账号密码校验</font></td>
    <td class="xl76" x:str><font class="font2"> 成功：进入主页，失败：返回账号密码不正确</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl77" height="135" rowspan="3" style='height:101.25pt;border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>管理员功能</font></td>
    <td class="xl76" x:str><font class="font2"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp; </span>审核被举报用户</font></td>
    <td class="xl76" x:str><font class="font2">选择被举报用户，输入举报理由，选择违规行为</font></td>
    <td class="xl76" x:str><font class="font2">核实有无违规</font></td>
    <td class="xl78" x:str><font class="font2">若被举报用户确有违规，则查封账号，若无违规，则降低举报用户信用分</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl76" x:str><font class="font2"> <span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp; </span>删除空白小组</font></td>
    <td class="xl76" x:str><font class="font2">选择空白小组</font></td>
    <td class="xl76" x:str><font class="font2">是否空白</font></td>
    <td class="xl78" x:str><font class="font2">若是空白小组，则删除小组。若不是空白小组，返回</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="45" style='height:33.75pt;mso-height-source:userset;mso-height-alt:675;'>
    <td class="xl76" x:str><font class="font2"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>用户信息管理</font></td>
    <td class="xl76" x:str><font class="font2">输入用户名、修改用户密码、确认密码</font></td>
    <td class="xl76" x:str><font class="font2">用户名、密码是否违规，密码两次是否一致</font></td>
    <td class="xl78" x:str><font class="font2">若无违规，修改密码成功</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="54" style='height:40.50pt;mso-height-source:userset;mso-height-alt:810;'>
    <td class="xl69" height="252" rowspan="5" style='height:189.00pt;border-right:.5pt solid #000000;border-bottom:none;' x:str><font class="font2">注册页面</font></td>
    <td class="xl72" rowspan="4" style='border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2"><span style='mso-spacerun:yes;'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </span>本地功能</font></td>
    <td class="xl81" x:str>点击注册手机号，密码，再次确认密码文本框</td>
    <td class="xl81" x:str>注册手机号，密码，再次输入密码，键入提示</td>
    <td class="xl82" x:str>注册手机号，密码，再次输入密码，显示键入提示且可键入</td>
    <td class="xl73"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="54" style='height:40.50pt;mso-height-source:userset;mso-height-alt:810;'>
    <td class="xl83" x:str>键入注册手机号密码，再次确认密码，输入文本框</td>
    <td class="xl81" x:str><font class="font28">手机号是否正确，两次密码是否统一切不违规</font></td>
    <td class="xl82" x:str><font class="font6">两者不违规则可以点击注册，否则注册失败，返回注册页面</font></td>
    <td class="xl73"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="54" style='height:40.50pt;mso-height-source:userset;mso-height-alt:810;'>
    <td class="xl81" x:str>点击同意用户服务协议前的方框</td>
    <td class="xl72" x:str><font class="font2">用户同意《用户服务协议》</font></td>
    <td class="xl72" x:str><font class="font2">初始空白，可以勾选，也可以取消勾选。勾选情况下可以点击注册，取消情况下注册按钮不可选</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="46" style='height:34.50pt;'>
    <td class="xl81" x:str>点击“已有账号”立即登录</td>
    <td class="xl72" x:str><font class="font2">能否返回登录页面</font></td>
    <td class="xl72" x:str><font class="font2">返回到登录页面</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="44" style='height:33.00pt;'>
    <td class="xl76" x:str><font class="font2">注册功能</font></td>
    <td class="xl76" x:str><font class="font2">点击注册按</font></td>
    <td class="xl76" x:str><font class="font2">注册信息校验</font></td>
    <td class="xl76" x:str><font class="font2">注册信息合法显示注册成功，反之显示注册失败</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl84" height="66" rowspan="3" style='height:49.50pt;border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2">主界面</font></td>
    <td class="xl72" x:str><font class="font2">个人资料</font></td>
    <td class="xl72" x:str><font class="font2">点击个人资料</font></td>
    <td class="xl72" x:str><font class="font2">能否正常显示个人资料</font></td>
    <td class="xl72" x:str><font class="font2">进入个人资料页</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl72" x:str><font class="font2">小组列表</font></td>
    <td class="xl72" x:str><font class="font2">点击小组列表</font></td>
    <td class="xl86" x:str><font class="font2">点击后能否进入小组列表</font></td>
    <td class="xl72" x:str><font class="font2">进入小组列表</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl76" x:str><font class="font2">小组群聊</font></td>
    <td class="xl76" x:str><font class="font2">点击小组群聊</font></td>
    <td class="xl76" x:str><font class="font2">点击后能否进入小组群聊</font></td>
    <td class="xl76" x:str><font class="font2">进入小组群聊</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl70" height="110" rowspan="5" style='height:82.50pt;border-right:.5pt solid #000000;border-bottom:none;' x:str><font class="font2">个人资料</font></td>
    <td class="xl88" x:str><font class="font2">头像</font></td>
    <td class="xl88" x:str><font class="font2">点击，上传图片</font></td>
    <td class="xl88" x:str><font class="font2">能否进入头像修改，图片是否违规</font></td>
    <td class="xl88" x:str><font class="font2">照片合规，修改头像成，不做修改返回</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl88" x:str><font class="font2">显示个人信息</font></td>
    <td class="xl88" x:str><font class="font2">点击个人信息</font></td>
    <td class="xl88" x:str><font class="font2">能否正常显示个人信息</font></td>
    <td class="xl88" x:str><font class="font2">显示个人信息</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl88" x:str><font class="font2">修改个人信息</font></td>
    <td class="xl88" x:str><font class="font2">点击修改个人信息</font></td>
    <td class="xl88" x:str><font class="font2">能否进入个人信息修改页面</font></td>
    <td class="xl88" x:str><font class="font2">进入个人信息修改</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl88" x:str><font class="font2">退出登入</font></td>
    <td class="xl88" x:str><font class="font2">点击</font></td>
    <td class="xl88" x:str><font class="font2">能否退出</font></td>
    <td class="xl88" x:str><font class="font2">退出登入反回登入页</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl77" x:str><font class="font2">修改密码</font></td>
    <td class="xl77" x:str><font class="font2">点击</font></td>
    <td class="xl77" x:str><font class="font2">能否进入修改密码页面</font></td>
    <td class="xl77" x:str><font class="font2">进入密码修改页</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="44" style='height:33.00pt;'>
    <td class="xl70" height="44" style='height:33.00pt;' x:str><font class="font2">个人信息修改页</font></td>
    <td class="xl88" x:str><font class="font2">修改信息</font></td>
    <td class="xl72" x:str><font class="font2">输入用户名，选择专业，想参加的比赛</font></td>
    <td class="xl88" x:str><font class="font2">是否为合法信息</font></td>
    <td class="xl88" x:str><font class="font2">信息合法显示修改成功，否则显示修改失败</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl70" height="81" rowspan="2" style='height:60.75pt;border-right:.5pt solid #000000;border-bottom:none;' x:str><font class="font2">密码修改页</font></td>
    <td class="xl88" rowspan="2" style='border-right:.5pt solid #000000;border-bottom:none;' x:str><font class="font2">修改密码</font></td>
    <td class="xl72" x:str><font class="font2">输入手机号获得验证码，输入验证码</font></td>
    <td class="xl72" x:str><font class="font2">是否在60秒内输入正确的验证码</font></td>
    <td class="xl88" x:str><font class="font2">输入新的密码</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="44" style='height:33.00pt;'>
    <td class="xl77" x:str><font class="font2">键入密码文本框，输入文本</font></td>
    <td class="xl76" x:str><font class="font2">密码长度6-20位（设置边界），可为数字，英文，下划线组合</font></td>
    <td class="xl76" x:str><font class="font2">无非法文本显示修改成功</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl70" height="140" rowspan="4" style='height:105.00pt;border-right:.5pt solid #000000;border-bottom:none;' x:str><font class="font2">小组列表</font></td>
    <td class="xl88" x:str><font class="font2">系统自动分配小组</font></td>
    <td class="xl88" x:str><font class="font2">点击自动分配</font></td>
    <td class="xl72" x:str><font class="font2">根据个人资料自动返回合适的小组</font></td>
    <td class="xl72" x:str><font class="font2">根据个人资料自动返回合适的小组(点击可进入小队资料页)</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl88" x:str><font class="font2">初始状态</font></td>
    <td class="xl88" x:str><font class="font2">不做操作</font></td>
    <td class="xl72" x:str><font class="font2">能否正常显示所有小组信息</font></td>
    <td class="xl88" x:str><font class="font2">显示所有小组(点击可进入小队资料页)</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="44" style='height:33.00pt;'>
    <td class="xl88" x:str><font class="font2">用户自己选择小组</font></td>
    <td class="xl88" x:str><font class="font2">输入筛选条件</font></td>
    <td class="xl72" x:str><font class="font2">根据筛选条件返回小组，且小组不满员</font></td>
    <td class="xl72" x:str><font class="font2">根据筛选条件返回小组(点击可进入小队资料页)</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl77" x:str><font class="font2">创建小组</font></td>
    <td class="xl77" x:str><font class="font2">输入小组的名，比赛名</font></td>
    <td class="xl77" x:str><font class="font2">比赛名</font></td>
    <td class="xl77" x:str><font class="font2">创建小组</font></td>
    <td class="xl75"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl70" height="44" rowspan="2" style='height:33.00pt;border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2">小组群聊</font></td>
    <td class="xl88" x:str><font class="font2">聊天界面</font></td>
    <td class="xl88" x:str><font class="font2">输入要发送的对话</font></td>
    <td class="xl88" x:str><font class="font2">是否存在敏感词</font></td>
    <td class="xl88" x:str><font class="font2">屏蔽敏感词后发出对话</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl88" x:str><font class="font2">查看小组资料</font></td>
    <td class="xl88" x:str><font class="font2">点击小队资料</font></td>
    <td class="xl88" x:str><font class="font2">能否正常显示小队资料页</font></td>
    <td class="xl88" x:str><font class="font2">进入小队资料页</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl70" height="155" rowspan="5" style='height:116.25pt;border-right:.5pt solid #000000;border-bottom:.5pt solid #000000;' x:str><font class="font2">小队资料页</font></td>
    <td class="xl88" x:str><font class="font2">转移组长</font></td>
    <td class="xl88" x:str><font class="font2">点击转移组长，选择成员</font></td>
    <td class="xl88" x:str><font class="font2">是否是组长</font></td>
    <td class="xl88" x:str><font class="font2">是：转移成功 否：转移失败</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl88" x:str><font class="font2">退出小组</font></td>
    <td class="xl88" x:str><font class="font2">点击退出小组</font></td>
    <td class="xl72" x:str><font class="font2">1：是组长且不是最后一人 2：是组长且是最后一人<span style='mso-spacerun:yes;'>&nbsp; </span>3：不是组员 4：是组员</font></td>
    <td class="xl72" x:str><font class="font2">1：请先转移组长 2：解散小队 3：你还不是组员 4：退出成功</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl88" x:str><font class="font2">加入小组</font></td>
    <td class="xl88" x:str><font class="font2">点击加入小组</font></td>
    <td class="xl88" x:str><font class="font2">不是小组成员</font></td>
    <td class="xl72" x:str><font class="font2">小组成员：你已经是小组成员了<span style='mso-spacerun:yes;'>&nbsp;&nbsp; </span>不是小组成员：进入申请等待区</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="22" style='height:16.50pt;'>
    <td class="xl88" x:str><font class="font2">查看小组成员基本资料</font></td>
    <td class="xl88" x:str><font class="font2">点击对应成员</font></td>
    <td class="xl88" x:str><font class="font2">能否正差显示队员基本资料</font></td>
    <td class="xl88" x:str><font class="font2">显示基本资料</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
   <tr height="37" style='height:27.75pt;mso-height-source:userset;mso-height-alt:555;'>
    <td class="xl88" x:str><font class="font2">申请等待区</font></td>
    <td class="xl72" x:str><font class="font2">点击头像查看基本资料/点击拒绝/点击接受</font></td>
    <td class="xl88" x:str><font class="font2">拥有组长权限才能接受/拒绝</font></td>
    <td class="xl72" x:str><font class="font2">拒绝：移出等待区 接受：加入小队，移出等待区</font></td>
    <td class="xl74"></td>
    <td class="xl68" colspan="20" style='mso-ignore:colspan;'></td>
   </tr>
  </table>

