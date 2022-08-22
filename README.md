# 反向面试

> 大部分翻译自：https://github.com/viraptor/reverse-interview ，亦有其他网友补充。

> 译者总结的一份适合突击记忆的简洁版 LeetCode 题解和面试问题，也欢迎 Star。https://github.com/yifeikong/interview

下面列表里的问题对于参加技术面试的人来说可能有些用。
列表里的问题并不一定适用于某个特定的职位或者工作类型，也没有排序
最开始的时候这只是我自己的问题列表，但是慢慢地添加了一些我觉得可能让我对这家公司亮红牌的问题。
我也注意到被我面试的人提问我的问题太少了，感觉他们挺浪费机会的。

如果你问过的问题没有被列出来，请提交一个 PR。

翻译：

[English](https://github.com/viraptor/reverse-interview)
[Korean](https://github.com/JaeYeopHan/Interview_Question_for_Beginner/blob/master/Reverse_Interview/README.md)
[Portuguese](https://github.com/viraptor/reverse-interview/blob/master/translations/PORTUGUESE.md)

## 预期使用方式

- 检查一下哪些问题你感兴趣
- 检查一下哪些是你可以自己在网上找到答案的
- 找不到的话就向面试官提问

绝对不要想把这个列表里的每个问题都问一遍。（尊重面试官的时间，而且你可以通过查找已经发布的答案来显示
你的主动性）

请记住事情总是灵活的，组织的结构调整也会经常发生。拥有一个 bug 追踪系统并不会保证高效处理 bug。
CI/CD （持续集成系统） 也不一定保证交付时间会很短。


# 职责

- On-call （电话值班）的计划或者规定是什么？值班或者遇到问题加班时候有加班费吗？
- 我的日常工作是什么？
- 有给我设定的特定目标吗？
- 团队里面初级和高级工程师的比例是多少？（有计划改变吗）
- 入职培训 (onboarding) 会是什么样的？
- 每个开发者有多大的自由来做出决定？
- 在你看来，这个工作做到什么程度算成功？
- 你期望我在最初的一个月 / 三个月能够完成什么？
- 试用期结束的时候，你会怎么样衡量我的绩效？
- 自己单独的开发活动和按部就班工作的比例大概是怎样的？
- 一个典型的一天或者一周的工作是怎样安排的？
- 对我的申请你有什么疑虑么？
- 在这份工作上，我将会和谁紧密合作？
- 我的直接上级他们的上级都是什么样的管理风格？（事无巨细还是着眼宏观）
- 我在这个岗位上应该如何发展？会有哪些机会？
- 每天预期 / 核心工作时间是多少小时？
- 我入职的岗位是新增还是接替之前离职的同事？（是否有技术债需要还）？(zh)
- 入职之后在哪个项目组，项目是新成立还是已有的？(zh)

# 技术

- 公司常用的技术栈是什么？
- 你们怎么使用源码控制系统？
- 你们怎么测试代码？
- 你们怎么追踪 bug?
- 你们怎样监控项目？
- 你们怎么集成和部署代码改动？是使用持续集成和持续部署吗 (CI/CD)？
- 你们的基础设施搭建在版本管理系统里吗？或者是代码化的吗？
- 从计划到完成一项任务的工作流是什么样的？
- 你们如何准备故障恢复？
- 有标准的开发环境吗？是强制的吗？
- 你们需要花费多长时间来给产品搭建一个本地测试环境？（分钟 / 小时 / 天）
- 你们需要花费多长时间来响应代码或者依赖中的安全问题？
- 所有的开发者都可以使用他们电脑的本地管理员权限吗？
- 介绍一下你们的技术原则或者展望。
- 你们的代码有开发文档吗？有没有单独的供消费者阅读的文档？
- 你们有更高层次的文档吗？比如说 ER 图，数据库范式
- 你们使用静态代码分析吗？
- 你们如何管理内部和外部的数字资产？
- 你们如何管理依赖？
- 你们的数据库是怎么进行版本控制的？(zh)
- 业务需求有没有文档记录？是如何记录的？(zh)

# 团队

- 工作是怎么组织的？
- 团队内 / 团队间的交流通常是怎样的？
- 你们使用什么工具来做项目组织？你的实际体会是什么？
- 如果遇到不同的意见怎样处理？
- 谁来设定优先级 / 计划？
- 如果团队没能赶上预期发布日期怎么办？
- 每周都会开什么类型的会议？
- 会有定期的和上级的一对一谈话吗？
- 产品 / 服务的规划是什么样的？（n 周一发布 / 持续部署 / 多个发布流 / ...)
- 生产环境发生事故了怎么办？是否有不批评人而分析问题的文化？
- 有没有一些团队正在经历还尚待解决的挑战？
- 你们如何跟踪进度？
- 预期和目标是如何设定的？谁来设定？
- Code Review 如何实施？
- 给我介绍下团队里一个典型的 sprint
- 你们如何平衡技术和商业目标？
- 你们如何共享知识？
- 团队有多大？
- 公司技术团队的架构和人员组成？(zh)
- 团队内开发、产品、运营哪一方是需求的主要提出方？哪一方更强势？(zh)

# 问未来的同事

- 开发者倾向于从哪里学习？
- 你对在这里工作最满意的地方是？
- 最不满意的呢？
- 如果可以的话，你想改变哪里？
- 团队最老的成员在这里多久了？
- 在小团队中，有没有出现成员性格互相冲突的情况？最后是如何解决的？

# 公司

- 公司为什么在招人？（产品发展 / 新产品 / 波动...)
- 有没有会议 / 旅行预算？使用的规定是什么？
- 晋升流程是怎样的？要求 / 预期是怎样沟通的？
- 绩效评估流程是怎样的？
- 技术和管理两条职业路径是分开的吗？
- 对于多元化招聘的现状或者观点是什么？
- 有公司级别的学习资源吗？比如电子书订阅或者在线课程？
- 有获取证书的预算吗？
- 公司的成熟度如何？（早期寻找方向 / 有内容的工作 / 维护中 / ...)
- 我可以为开源项目做贡献吗？是否需要审批？
- 你认为公司未来五年或者十年会发展成什么样子？
- 公司的大多数员工是如何看待整洁代码的？
- 你上次注意到有人成长是什么时候？他们在哪方面成长了？
- 在这里成功的定义是什么？如何衡量成功？
- 公司支持开源项目吗？
- 有竞业限制或者保密协议需要签吗？
- 你们认为公司文化中的空白是什么？
- 能够跟我说一公司处于不良情况，以及如何处理的故事吗？
- 您在这工作了多久了？您觉得体验如何？(zh)
- 大家为什么会喜欢这里？(zh)
- 公司的调薪制度是如何的？(zh)

# 社会问题

- 你们关于多元化招聘什么看法？
- 你们的公司文化如何？你认为有什么空白么？
- 这里的工作生活平衡地怎么样？

# 冲突

- 不同的意见如何处理？
- 如果被退回了会怎样？（“这个在预计的时间内做不完”）
- 当团队有压力并且在超负荷工作的时候怎么处理？
- 如果有人注意到了在流程或者技术等其他方面又改进的地方，怎么办？
- 当管理层的预期和工程师的绩效之间有差距的时候如何处理？
- 能给我讲一个公司深处有毒环境以及如何处理的故事吗？
- 如果在公司内你的同事因涉嫌性侵犯他人而被调查，请问你会如何处理？
- 假设我自己很不幸是在公司内被性侵的受害者，在公司内部有没有争取合法权益的渠道？

# 商业

- 你们现在盈利吗？
- 如果没有的话，还需要多久？
- 公司的资金来源是什么？谁影响或者制定高层计划或方向？
- 你们如何挣钱？
- 什么阻止了你们挣更多的钱？
- 公司未来一年的增长计划怎样？五年呢？
- 你们认为什么是你们的竞争优势？
- 你们的竞争优势是什么？
- 公司未来的商业规划是怎样的？有上市的计划吗？(zh)

# 远程工作

- 远程工作和办公室工作的比例是多少？
- 公司提供硬件吗？更新计划如何？
- 使用自己的硬件办公可以吗？现在有政策吗？
- 额外的附件和家具可以通过公司购买吗？这方面是否有预算？
- 有共享办公或者上网的预算吗？

# 办公室布局

- 办公室的布局如何？（开放的 / 小隔间 / 独立办公室）

# 终极问题

- 该职位为何会空缺？
- 公司如何保证人才不流失？
- 这份工作 / 团队 / 公司最好和最坏的方面是？
- 你最开始为什么选择了这家公司？
- 你为什么留在这家公司？

# 待遇

- 如果有奖金计划的话，奖金如何分配？
- 如果有奖金计划的话，过去的几年里通常会发百分之多少的奖金？
- 有五险一金(zh)/401k(us)或者其他退休养老金等福利吗？
- 五险一金中，补充公积金一般交多少比例？/401k一般交多少比例？我可以自己选择这一比例吗？
- 有什么医疗保险吗？如果有的话何时开始？
- 有额外商业保险吗？例如人寿保险和额外的养老/医疗保险？
- 更换工作地点，公司付费吗？

# 休假

- 带薪休假时间有多久？
- 病假和事假是分开的还是一起算？
- 我可以提前使用假期时间吗？也就是说应休假期是负的？
- 假期的更新策略是什么样的？也就是说未休的假期能否滚入下一周期
- 照顾小孩的政策如何？
- 无薪休假政策是什么样的？
- 学术性休假政策是怎么样的？

# 其他资源

Find more inspiration for questions in:

  - [The Joel Test: 12 Steps to Better Code](https://www.joelonsoftware.com/2000/08/09/the-joel-test-12-steps-to-better-code/) by Joel Spolsky
  - [Questions I'm asking in interviews](https://jvns.ca/blog/2013/12/30/questions-im-asking-in-interviews/) by Julia Evans

# License

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).
