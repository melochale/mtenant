# 致谢

2010年3月4日我在我邮箱中看到CEO Steve Ballmer的邮件。我不常收到他的邮件，因此我格外重视。邮件标题是：“我们会全身心投入其中”。它总结了微软对云计算委以重任。如果还需要再次确认，那也一定就是微软对待云技术的重视程度。

我第一次接触现在成为Windows Azure及Windows Azure Platform是在几年前。那时我正在开发者及平台布道团队（DPE: Developer & Platform Evangelism team），我的工作职责是探索如何把软件作为一种服务进行交付。读者中一些人甚至可能还记得我早在2007年开发的软件模型叫Northwind Hosting。它探索如今Windows Azure提供的很多特性。（看着当初我开创的一些初步的东西如今已经成为现实，我非常开心。）

在2009年2月，我离开了DPE团队加入了模型实践团队。我的任务是领导“云计算项目”——一些关于考察打造云端软件的颇具设计挑战性的子项目。当Windows Azure平台宣布时，需要他们做指导的需求与日俱增。

我们考察了不同软件开发的场景，清楚的认识到身份识别管理是你首要考虑的问题。特别是你有一个公司包含了大量的本地（on-premises）资产，并且想把它们迁移到云中。这描述了我们很多的客户情况。

在2009年12月，我们发布了“基于声明的身份识别和接入控制指南”第一版，这是模式实践团队的第一次可交付版本，云项目的一次重要里程碑。接下来发布了“Windows Azure应用迁移指南”。这是我们Windows Azure开发指南的三部曲中第一部，他们都已经随着Windows Azure发展而更新。

Windows Azure在很多方面是特别的，其中一点就是创新性。许多交付Azure平台系统的团队证明了他们可以很快的完成功能，为了赶上他们的脚步，我觉得我们开发内容必须跟着快。所以我们给项目两个月的冲刺期，其中一点是专注于一系列特殊的考虑。


本书讨论了未被涉足的场景：为Windows Azure平台设计和开发一个多租户应用。这紧跟着上一个指导手册《Windows Azure应用迁移指南》，它假象了一个案例来进行学习指导，内容是一步一步解释我们的客户可能会遇到的挑战。

首先，我想感谢以下话题专家和贡献者对本指南的帮助，他们是：Dominic Betts（Content Master Ltd），Scott Densmore（Microsoft Corporation）， Ryan Dunn，Steve Marx，和Matias Woloski。Dominic有不凡的技巧来熟悉一个包含大量细节的课题，并且他知道如何找到一种精确、完整和简单易懂的方法解释给其他人。Scott带给我们打造可伸缩性的Windows Azure应用丰富的知识，他加入我们团队之前正是做这个事情的，另外它也给我们带来了多年的经验，是关于如何为开发者打造框架和工具。我有幸与Ryan在之前的项目中合作过，我总是从他的敏锐性、洞察力和经验中受益良多。作为一个Windows Azure的布道者，他总能向我们展示客户真正需要的东西。Steve是Windows Azure的技术战略家，他在塑造本指导书方面给予了很多帮助。我们依赖他向我们展示不仅Azure云平台目前能做什么，而且包括该平台将来如何演进。这非常的重要，因为我们想要我们提供的指南与长远的目标一致。最后同样重要的是，Matias是和我很多项目在一起的专家，在Windows Azure初期他就已经加入其中，他的努力对创建本书有宝贵的价值。

我们有覆盖了大部分章节的示例代码与书籍内容同步进行，它演示本书讨论的东西。我要感谢该项目的开发和测试团队在技术上合理和专注的取舍平衡才有了简单易懂的代码，他们是：Masashi Narumoto (Microsoft Corporation)，Scott Densmore (Microsoft Corporation)，Federico Boerr (Southworks)，Adrián Menegatti (Southworks)，Hanz Zhang (Microsoft Corporation)，Ravindra Mahendravarman (Infosys Ltd.)， Rathi Velusamy (Infosys Ltd.)。

本书必须技术上是准确的且也有寓教于乐性。这不是简单的任务，我想感谢编辑团队成员Dominic Betts (Content Master Ltd)，RoAnn Corbisier (Microsoft Corporation)，Alex Homer (Microsoft Corporation)，和Tina Burden，正是他们擅长的。 

本书的可视化设计概念原是由Roberta Leibovitz和Colin Campbell(Modeled Computation LLC)在《 基于声明的身份识别和接入控制指南》中提出的。由于受到良好的反馈，我们决定在本书中重用它。本书设计是由John Hubbard (eson)完成的。卡通表情是源于西雅图的获奖漫画家Ellen Forney绘画的。技术插图是由Rob Nance和Katie Niemer根据我的PC平板模型适配完成的。

所有本书的内容都被大批的客户、伙伴、同事审核、评论和校对过。我们也收到了来自CodePlex的更大的社区的反馈。Windows Azure平台广泛、跨越了多个领域。我们非常幸运能够有如此多样和娴熟的读者智囊团。

我也想感谢所有本书早期草稿志愿贡献时间和专家意见的人士，在他们中，有特别贡献的有：David Aiken (Microsoft Corporation) Graham Astor (Avanade), Edward Bakker (Inter Access), Vivek Bhatnagar (Microsoft Corporation), Patrick Butler Monterde (Microsoft Corporation), Shy Cohen, James Conard (Microsoft Corporation), Brian Davis (Longscale), Aashish Dhamdhere (Windows Azure, Microsoft Corporation), Andreas Erben (DAENET), Giles Frith, Eric L. Golpe (Microsoft Corporation), Johnny Halife (Southworks), Simon Ince (Microsoft Corporation), Joshy Joseph (Microsoft Corporation), Andrew Kimball, Milinda Kotelawele (Longscale), Mark Kottke (Microsoft Corporation), Chris Lowndes (Avanade), Dianne O’Brien (Windows Azure, Microsoft Corporation), Steffen Vorein (Avanade), Michael Wood (Strategic Data Systems)。

希望本书对您有益。

Eugenio Pace

模式和实践团队高级项目经理

微软公司


## 第三版致谢

Windows Azure是一个不断演进的平台，我们最初在2010年发布了它的第一个版本，介绍了它的一些基础特性。我非常开心现在能够发布本书的第三个版本，该版本更多的关注与多租户场景，它描述了多租户应用软件或服务一些挑战，比如数据分区、数据可扩展性、自动配置、组合定制等等。

随着我们的领域逐渐壮大，我们也加入许多新的社区成员和业界专家，他们对本书的第三版提供了重大的帮助。我想感谢如下特殊贡献的人士：Dominic Betts (ContentMaster), Alex Homer (Microsoft Corporation), Alejandro Jezierski (Southworks), Mauro Krikorian (Southworks), Jorge Rowies (Southworks), Marcos Castany (Southworks), Hanz Zhang (Microsoft Corporation), Rathi Velusamy (Infosys), RoAnn Corbisier (Microsoft Corporation), Nelly Delgado (Microsoft Corporation), Eugenio Pace (Microsoft Corporation), Carlos Farre (Microsoft Corporation), Trent Swanson (Full Scale 180 Inc.), Ercenk Keresteci (Full Scale 180 Inc.), Jane Sinyagina (Microsoft Corporation), Hatay Tuna (Microsoft Corporation), Patrick Butler Monterde (Microsoft Corporation),Michael Wood。我也想感谢所有参与我们Codeplex社区的成员。

Masashi Narumoto

模式和实践团队高级项目经理

微软公司

雷德蒙德州，2012年10月

