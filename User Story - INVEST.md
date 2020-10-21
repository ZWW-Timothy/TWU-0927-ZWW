User Story - INVEST

一
简答题

1
用自己的话简述INVEST原则每个字母的含义。(20分)
答：
I，即independent ，独立的，含义是，故事卡之间不能有会导致开发无法进行的复杂依赖，而按一定顺序先开发一张卡再开发另一张是可以的。
N，即negotiable，可协商的，含义是，交付团队与客户之间可以随时关于需求、方案等进行澄清、修改等。
V，即valuable，有价值的，含义是，开发时需要考虑用户故事是为哪类用户开发的，其业务价值与意义是什么。
E，即estimable，可估计的，含义是，用户故事用于做迭代计划，交付工作量需要是可被估计的。
S，即small，小的，含义是，以不超过两周的迭代周期为基准，期望用户故事是足够小的。
T，即testable，可测试的，含义是，客观地定义用户故事的测试标准，确定其何时可以完成交付。

2
用自己的话简述用户故事两种常见的切分方式。(20分)
答：
Web开发项目的结构一般包含三层，第一层User Interface实现用户与页面的交互，第二层Business Logic处理业务逻辑，第三层Data Store进行数据的存储。用户故事的常见切分方式包括垂直切分与水平切分。垂直切分，会覆盖三层结构，每个用户故事交付后都可用，开发人员要能完成前后端开发，技能要求较高。水平切分，根据前后端切分，前端与后端开发人员分别关注前端与后端用户故事，降低了技能要求，增加了沟通成本。

二
情景题
根据以下用户故事概述，判断该用户故事是不是符合INVEST原则？如果不符合，说明违背了哪个或哪几个原则，并解释原因。

1
<Case 1> (20分)
As a customer,
I want to be able to shop online
So that I can do it wherever and whenever I want, without physically going to the store
答：
我认为违反了EST三个原则。功能描述不客观也不具体，难以进行估点。整体目标很庞大，没有进行拆分。没有给出客观的测试标准。

2
<Case 2>(20分)
As a customer
I want to update and delete items in my shopping cart
So that I can change my mind about what to buy
答：
我认为违反了ST两个原则。包含了更新和删除这两个功能，可以继续拆分。没有给出客观的测试标准。

3.
<Case 3>(20分)
As a customer
I want to search for the items that I needed to buy
So that I can select the items I need to buy
答：
我认为违反了T原则。没有给出客观的测试标准。
