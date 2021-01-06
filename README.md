# AI-Job-Notes
AI算法岗求职攻略：涵盖校招时间表、准备攻略、刷题指南、内推、AI公司清单和答疑等资料

AI算法岗方向：深度学习、机器学习、计算机视觉、图像处理和SLAM等

>  注：如果你看到这篇文章，且有一些疑问或者想提供一些资源，欢迎提交issues！

# 目录

<!-- MarkdownTOC depth=4 -->

- [1 校招时间表](#Scheduled)
- [2 准备攻略](#Strategy)
- [3 AI 面经和刷题指南](#Coding)
- [4 内推](#Recommend)
- [5 简历模板](#Resume)
- [6 AI 类公司清单（以CV岗为主）](#Company)
- [7 往届AI算法岗薪资情况](#Salary)
- [8 答疑（含130个问答）](#Q&A)

<a name="Scheduled"></a>

## 1 校招时间表

![](imgs/校招时间表.png)

以今年(2021)为例，默认为2022届学生（2021届学生称为上届）

| 时间           | 任务                                |
| -------------- | ----------------------------------- |
| 2021年3月~6月  | 找暑期实习/上届春招（补招）         |
| 2021年6月~8月  | 秋招提前批（神仙打架）              |
| 2021年9月~11月 | 秋招正式批（神仙继续打架+菜鸡互啄） |

### 1.1 暑期实习

2021年3月~6月：暑期实习。

实习一般分成两种：

- 日常实习
- 暑期实习

![](imgs/实习.png)

**日常实习**：日常实习是任何时候都可以找的，通常是根据具体部门的需求，由公司HR、部门主管或者部门员工发布招聘消息，相对较为零散也比较灵活。

**暑期实习**：很多公司，特别是大公司（如BAT等大厂），都会组织专项的**暑期实习生**招聘活动。一方面是针对在校学生的情况（很多学生只有暑期才有假期，或者导师暑假才放人），另一方面就是为了秋季校招（大规模招聘）吸引人才。暑期实习具有很大的意义，对学生来说，最直接的好处就是转正机会。暑期实习，一般6月底左右实习入职（也可以根据自己的时间，提前入职），一般8月底或9月份会有专项暑期实习答辩，根据综合表现，答辩通过后就可以基本结束秋招了。

注：这里建议在进入公司参加暑期实习的期间，也要参加秋招提前批和秋招正式批，并多投递一些公司，即使在实习，所谓的很忙，没时间准备秋招了，那也要多投。暑期实习的另一个好处是增加可贵的实习经验，简历会好看很多。

### 1.2 秋招提前批

**2021年6月~8月：秋招提前批（神仙打架）**

据我了解上届打响秋招第一枪的是大疆(DJI)科技，其在6月底就已经结束简历投递了，然后BAT等大厂都是7月份开始。这时候的校招，绝大部分都是内推/提前批，而不是正式批，大家一定要珍惜这个时间点：6月~8月。虽然我调侃着说神仙打架，但还是要注意这时候性价比特别高。一方面是薪资普遍高，通常一些SP/SSP Offer都是这个节点发出来的，另一方面是投递的人数还不是很多，因为有些人没有意识到这个提前批的重要性，老想着多准备一点，到秋招正式批再大干一场。

需要注意的是：参与秋招提前批的大佬特别多，同时岗位hc并不多（因为企业要考虑正式批的情况，会控制招聘人数），所以我把秋招提前批比作：神仙打架。另外，秋招提前批大多以内推为主，后面章节中我会说到如何获取招聘信息以及如何内推。

注：提取批挂了，正式批可以再继续投（具体看不同公司的招聘介绍）。

### 1.3 秋招正式批

**2021年9月~11月：秋招正式（神仙继续打架+菜鸡互啄）**

有句话叫做金九银十，也就是9月份的 Offer 比10月份的 Offer 更可贵，这话其实很有道理，所以大家可以脑补到7、8月份的 Offer 属于什么 level 了。这时候也很考验大家的心态，比如9月份或10月份了，如果你手里还没有Offer，再看看身边已经拿到Offer的同学，一定变成柠檬精。

所以 Amusi 这里强烈建议一定要把握住 1.2节中的**秋招提前批 **。当然了，如果9月份手里还没有Offer，心态千万别崩，继续投继续干，记住一句话：多投准没错！其实大部分同学都是9月、10月才陆续收到Offer的，所以你多投继续努力，收获肯定会有的。

<a name="Strategy"></a>

## 2 准备攻略

因为这就好像是学习计划一样，每个人都要自己的习惯，我的你并不一定适用。所以我就用一个精简的公式来介绍。
~~公式1.0：刷题+背题+项目+实习(可选)+竞赛(可选)+顶会/顶刊(可选)~~

**公式2.0：刷题(LeetCode/剑指Offer) + AI基础知识 + 编程基础知识 + 项目 + 实习 + 竞赛 +顶会/顶刊(可选)**

<a name="Coding"></a>

## 3 AI面经和刷题指南

### 3.1 深度学习面试宝典

详见：[深度学习面试宝典（含数学、机器学习、深度学习、计算机视觉、自然语言处理和SLAM等方向）](<https://github.com/amusi/Deep-Learning-Interview-Book>)

**Deep Learning Interview Book** 部分内容如下：

- 😃 [自我介绍](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E8%87%AA%E6%88%91%E4%BB%8B%E7%BB%8D.md)
- 🔢 [数学](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%95%B0%E5%AD%A6.md)
- 🎓 [机器学习](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%9C%BA%E5%99%A8%E5%AD%A6%E4%B9%A0.md)
- 📕 [深度学习](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0.md)
- 📗 [强化学习](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E5%BC%BA%E5%8C%96%E5%AD%A6%E4%B9%A0.md)
- 👀 [计算机视觉](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E8%AE%A1%E7%AE%97%E6%9C%BA%E8%A7%86%E8%A7%89.md)
- 📷 [传统图像处理](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E4%BC%A0%E7%BB%9F%E5%9B%BE%E5%83%8F%E5%A4%84%E7%90%86.md)
- 🀄️ [自然语言处理](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E8%87%AA%E7%84%B6%E8%AF%AD%E8%A8%80%E5%A4%84%E7%90%86.md)
- 🏄 [SLAM](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/SLAM.md)
- 👥 [推荐算法](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%8E%A8%E8%8D%90%E7%AE%97%E6%B3%95.md)
- 📊 [数据结构与算法](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95.md)
- 🐍 [编程语言：C/C++/Python](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E7%BC%96%E7%A8%8B%E8%AF%AD%E8%A8%80.md)
- 🎆 [深度学习框架](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0%E6%A1%86%E6%9E%B6.md)
- ✏️ [面试经验](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E9%9D%A2%E8%AF%95%E7%BB%8F%E9%AA%8C.md)
- 💡 [面试技巧](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E9%9D%A2%E8%AF%95%E6%8A%80%E5%B7%A7.md)
- 📣 [其它（计算机网络/Linux等）](https://github.com/amusi/Deep-Learning-Interview-Book/blob/master/docs/%E5%85%B6%E5%AE%83.md)

### 3.2 刷题指南

刷题的目的是为了学习数据结构和算法，锻炼编程能力和熟悉刷题技巧

刷题建议：先刷[《剑指Offer》](https://www.nowcoder.com/ta/coding-interviews)（66题），再刷 [LeetCode](https://leetcode.com/)（目前LeetCode已经有1000+题，可以根据类别来刷，但强烈建议先刷完 [LeetCode 面试高频题](https://leetcode.com/problemset/top-interview-questions/)）

> 注：根据去年校招提前批的情况来看，LeetCode 建议至少刷200-300题，所以2021年（2022届）找工作的同学一定要努力刷起来了！

#### 3.2.1 刷题编程语言

- C/C++
- Python
- JAVA（不推荐）

> 注：如果时间充裕，而且有 C++ 基础，那么强烈建议使用 C++和 Python 同时刷题。
>
> 根据 2021 年(2022届)校招提前批的情况来看，会 C++ 的同学具有有一定优势。

#### 3.2.2 书籍推荐

| 书籍                                                         | 豆瓣评分 | 推荐指数 |
| ------------------------------------------------------------ | -------- | -------- |
| [《剑指Offer》](https://book.douban.com/subject/25910559/)   | 9.1      | ☆☆☆☆☆    |
| [《数据结构(C++语言版)》](https://book.douban.com/subject/25859528/) | 9.4      | ☆☆☆☆     |
| [《算法图解》](https://book.douban.com/subject/26979890/)    | 8.4      | ☆☆☆☆     |
| [《大话数据结构》](https://book.douban.com/subject/6424904/) | 7.9      | ☆☆☆      |
| [《算法》(第四版)](https://book.douban.com/subject/19952400/) | 9.4      | ☆☆☆      |

>  注：其实还有很多方向没有涉及，如linux、数据库，但暂时先推荐这些，后面再补充

#### 3.2.3 在线刷题网站

- [LeetCode(英文)](https://leetcode.com/)
- [LeetCode(中文)](https://leetcode-cn.com/)
- [牛客网](https://www.nowcoder.com/)：推荐剑指Offer和各大公司往年题库，牛客网的优势在于很多公司都会使用其作为在线刷题平台，所以在这上面刷题，有利于懂得输入输出等"套路"

#### 3.2.4 刷题方法

- 《剑指Offer》全刷完
- LeetCode选择性刷：可以类别来刷题，如数组类、链表类，或者面试高频类

#### 3.2.5 刷题时间

现在起~2021-10-15

#### 3.2.6 刷题重要性

正常校招流程都要进行在线笔试，面试中也可能会手撕代码，所以刷题十分影响面试结果。

<a name="Recommend"></a>

## 4 内推

国内公司人工智能方向岗位的内推机会，含机器学习、深度学习、计算机视觉和自然语言处理等方向。

[AI-Job-Recommend](https://github.com/amusi/AI-Job-Recommend) 主要以全职、实习和校招为主，并且全都是内推方式！

- [实习内推](https://github.com/amusi/AI-Job-Recommend/blob/master/%E5%AE%9E%E4%B9%A0/README.md)：已含腾讯、京东和商汤等公司

- [全职内推](https://github.com/amusi/AI-Job-Recommend/blob/master/%E5%85%A8%E8%81%8C/README.md)：已含腾讯等公司

注：2021年6月开始，[AI-Job-Recommend](https://github.com/amusi/AI-Job-Recommend) 会推出大量校招内推资源，欢迎star/fork/watching。

### 4.1 内推的重要性

内推，真的太重要了。其实现在找实习也一样，内推的重要性就提醒出来了，比如我这边的资源就可以内推到BAT、商汤、旷视等公司，一般常规操作是网上投递简历，而快速直接的就是将简历送到leader/主管那里。而且内推是建立在一种互信的基础上(虽然不大)，该走的流程还是要走，但无形中增大了面试通过概率。你要知道，很多人的简历在官网或者其他第三方招聘网站上就直接卡死了。

### 4.2 如何内推？

内推的方式很多，比如：

1. 强关联：直接找已经毕业的师兄师姐或朋友内推（缺点是身边朋友去的企业有限，很多人是第一批从事算法岗的，可能都没有师兄师姐搞这个）
2. 常规操作：上牛客网论坛看企业人员发内推帖子、关注一些招聘公众号（这里我就不推荐，因为很多公众号都很有套路，内推一个企业，还要转发文章到其它群里，然后截图给他们，可是对于大多数人，为了内推，只能这么干）
3. Amusi 内推。这里感觉像似打广告一样，但确实是一个方式，因为我手里资源挺多的，很多公司的人都认识，可以直接内推。感兴趣的可以关注一下这个求职群[「2021年AI算法岗求职群」](https://t.zsxq.com/VFUZR3n) 或者 [AI-Job-Recommend](https://github.com/amusi/AI-Job-Recommend)

![](imgs/2021年AI算法岗求职群.png)

<a name="Resume"></a>

## 5 简历模板

提供了三份简历模板，详见：[AI 算法岗简历模板](https://github.com/amusi/AI-Job-Resume)

![](imgs/Resume-Demo.png)

<a name="Company"></a>

## 6 AI类公司清单（以CV岗为主）

首先 AI > CV，所以提供CV岗的公司肯定就提供 AI岗。但至于这些公司是否还有 NLP、机器学习、语音识别、推荐算法和 SLAM等岗位，这个需要大家自行去官网进行了解。

荐读：[国内提供计算机视觉(CV)算法岗位的公司名单(含外企和国内公司)](https://github.com/amusi/CV-Company-List )

**北京提供CV算法岗的公司名单**

![](/imgs/Beijing.png)

更多城市信息（上海，深圳，杭州，南京，广州和成都等）详见：https://github.com/amusi/CV-Jobs

<a name="Salary"></a>

## 7 往届AI算法岗薪资情况

这里说说2019届AI算法岗的薪资情况。

我只以**硕士及一线左右城市**为例（北上广深、南京、杭州等），因为像武汉、成都，你即使找的AI算法岗，但城市不一样，薪资还是多少有区别，明显不能只看Money，不考虑城市大环境。

- **白菜价：25w~30w**

- **SP：30w~40w**

- **SSP：40w+**

说年薪有点笼统，我再说细一点，大家也可以提取熟悉一下。

一般企业薪资构成是：

- 年薪 = 月薪*12 + 年终奖

年终奖一般是2~5个月的薪资，大概是3个月

所以，年薪=月薪*15

如果你月薪2w，那么年薪就是30w=2*15（白菜的Top，SP的Down）

如果你月薪2.7w，那么年薪就是40.5w=2.7*15（SP的Top，SSP的Down）

这里po一张很全很全的高薪图，来自OfferShow

注：跟hr谈薪资的时候，如果她/他问你：你的希望薪资是多少？！这时候你一定要往高了要，至少比你想要的高30%。听我的，没有错，不然...

![](imgs/salary.png)

<a name="Q&A"></a>

## 8 答疑

130个问答请戳—> [Q&A](Q&A.md)