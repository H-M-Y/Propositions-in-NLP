# Propositions-in-NLP

> Contributed by Mengyang Hu.

## Introduction

In this repo, we list some related work on propositions in NLP. Corrections and suggestions are welcomed.

## Contents

1. Glossary
2. Field Overview
3. Propositions in Linguistic & Logic
4. Propositions in NLP
5. Related Datasets

### Glossary

1. Propositions: Propositions are defined as the meaning of declarative sentences in linguistics and logic, which can be identified true or false. The ”meaning” here is understood as a non-linguistic entity shared by all sentences with the same meaning.
2. Natural language contains a large number of propositions, like "He smiles." and "If you are human, then you need to eat.".
3. Explicit proposition: A proposition that guided by complete logical connectives.
4. Implicit proposition: A proposition that does not belong to the explicit proposition.
5. Proposition classification: Categorical proposition, Conjunctive proposition, Hypothetical proposition, Disjunctive proposition etc.
6. Categorical proposition： Make a direct and unconditional judgment on whether an object logically contains a certain property and whether it belongs to a certain category.
7. Conjunctive proposition: A kind of compound proposition, which reflects the simultaneous existence of several situations or properties of objects, and logically has a conjunctive relationship.
8. Hypothetical proposition: A kind of compound proposition, which contains a previous or tentative explanation, and logically has a conditional relationship.
9. Disjunctive proposition: A kind of compound proposition, which reflects the fact that at least one existence of either conditions or properties of objects, and logically has a disjunctive relationship.

### Field Overview

The research on propositions in linguistics and logic has already been very in-depth, but in NLP has not been carefully explored. Thus, there are no review articles on propositions in NLP.

### Propositions in Linguistic & Logic

#### Relevant books

1. [《形式逻辑》_华东师范大学出版](https://www.amazon.cn/dp/B0734HCVCN)
2. [《逻辑学十五讲》_陈波](https://cread.jd.com/read/startRead.action?bookId=30319395&readType=1)
3. [《Philosophical Propositions: An Introduction to Philosophy 》](https://www.amazon.com/Philosophical-Propositions-Introduction-Jonathan-Westphal/dp/0415170532)
4. [《Introduction to Logic 》_12th Edition](https://www.amazon.com/Introduction-Logic-Irving-Copi/dp/0131898345)
5. [《New Essays on the Nature of Propositions》](https://www.routledge.com/New-Essays-on-the-Nature-of-Propositions/Hunter-Rattan/p/book/9781138082960)
6. [《Propositional Structure and Illocutionary Force: A Study of the Contribution of Sentence Meaning to Speech Acts》](https://www.alibris.com/Propositional-Structure-and-Illocutionary-Force-A-Study-of-the-Contribution-of-Sentence-Meaning-to-Speech-Acts-Jerrold-J-Katz/book/5427635)
7. [《Propositions and Attitudes》](https://books.google.es/books/about/Propositions_and_Attitudes.html?id=r_jWAAAAMAAJ&redir_esc=y)
8. [《New thinking about propositions》](https://books.google.es/books?hl=zh-CN&lr=&id=RkieAgAAQBAJ&oi=fnd&pg=PP1&dq=propositions++&ots=aTctgflwHH&sig=P6EKDw4XpRMunZApgGY5f_IyOm0)

#### Relevant articles

[形式逻辑和自然语言_周礼全 *哲学研究* 12 ,1993](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/80454x/199312/1002573106.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=11124725418585985099&ei=Fd0fYaQbhOSYAYbRhOAL&scisig=AAGBfm3L5Vse2wY0cr4jONd58ht65CjHIg)

自然语言的指谓性和交际性自然语言有两个基本性质,一个是指谓性,另一个是交际性。自然语言中有许多语词,由语词根据语法形成许多语句。语词指称一个或一类事物。例如,“孔子”这个语词指称一个个别的人。“苹果”这个语词指称一类事物。“孔子是一位哲学家”和“苹果是富于营养的水果”这两个语句分别指称两个不同的事物情况。

[浅论形式逻辑对语言研究的作用_高逢亮*现代语文: 下旬. 语言研究* ,2017](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/87478a/201712/7000407426.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=15682410221143170066&ei=SN0fYeKZC-mSy9YPps2T4AM&scisig=AAGBfm26ktN9-fDvheTcsDxXukJneecooA)

逻辑学和语言学的关系尤为密切。从语义学、语法学、语用学、修辞学等不同的学科层面展开探讨,可以更好地观察逻辑学和语言学之间的互动。

[论直言判断的种类_马佩 *逻辑学文集*, 1978](https://scholar.google.com/scholar_url?url=https://cpfd.cnki.com.cn/Article/CPFDTOTAL-ZLJX197809001015.htm&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=9362221075073630379&ei=iuIfYbbnLsWKy9YPtvGwiA0&scisig=AAGBfm2AFdRekrboDZvjfMGSDRC7w0FJzQ)

直言判断的定义判断按其结构的不同,可分为简单判断和复合判断。简单判断一般来说是只有一个主项一个谓项的判断,复合判断则是几个简单判断的复合。直言判断是只有一个主项的判断,它属于简单判断。

[逻辑常项隐性形式初探_黄士平 *江汉大学学报 (社会科学版)*, 1991](https://scholar.google.com/scholar_url?url=https://www.cnki.com.cn/Article/CJFDTotal-JHDX199104021.htm&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=7661366569715209848&ei=md0fYcfyLMWKy9YPtvGwiA0&scisig=AAGBfm1XliGaPWLDsqGI3OXVDjt6kNRslA)

逻辑常项是逻辑形式中不变的部分, 即在同类型的逻辑形式中都存在的部分. 根据格· 克劳斯的说法,“逻辑的基本任务之一就在于: 区分出这些常项, 了解它们的用法, 研究它们所服从的规律.”《 普通逻辑》 也明确指出, 逻辑常项“是区别不同类型逻辑形式的主要依据”. 在现代汉语中, 复合判断的逻辑常项即其逻辑联结词一般是由起关联作用的虚词来表述的. 张志公先生认为, 这些“虚词是表示关联组合内部的逻辑联系的必不可少的标志.” 逻辑常项在逻辑研究及应其用中的重要性于此可见.

[金岳霖命题思想初探，景豪，2017](https://cdmd.cnki.com.cn/Article/CDMD-10475-1017238038.htm)

本文主要立足于《知识论》中的有关资料,对金岳霖的命题思想进行研究。全文共分四个部分。第一章分别从命题的定义、命题的构造和命题的分类三个方面把金岳霖的命题思想与其他学者进行对比,并对金岳霖的命题分类提出了不同观点。

[命题的一个新定义与命题的同一性问题_周文华 *云南大学学报: 社会科学版* , 2016](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/87060x/201604/669273653.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=5875051359367290280&ei=IN4fYd6QH6zcsQLI_oWACw&scisig=AAGBfm1peoeE9AKfsaNlbWj5_sPxo9_zFw)

命题曾被定义为某些句子, 但句子没有固定的真值. 命题曾被定义为句子的意义, 但" 意义" 这个概念并不比" 命题" 更清晰. 还原论把命题定义为一种由可能世界, 可能的个体等组成的集合论性的构造物, 但这种理论意味着全部的逻辑真理表达的是同一个命题. 

[逻辑判断基本类型及其在语言中的反映_沈园 *当代语言学* , 2000 ](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/82143x/200003/10511429.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=9538730411415556706&ei=cOEfYbmDC8qgmQHcyobgDw&scisig=AAGBfm3xiYEUbprsnA3Df0B_wyvZqqyiwA)

本文从讨论逻辑判断基本类型的划分, 到综合逻辑判断两种基本类型各自的句法, 语义, 语用特点及语调模式, 回顾了(主要是近三十年来) 语言学界以不同语言为材料围绕逻辑判断基本类型这一课题进行的多角度研究, 说明逻辑判断是与语法, 语用等各方面有着密切联系而又相对独立的一个范畴.

[浅谈逻辑常项的语言表达形式_韩铁稳 *思维与智慧: 上半月*, 1989](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/80722x/198903/683879070198903003.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=15180833293313515288&ei=4eEfYc26BZKAmwG32qHQBA&scisig=AAGBfm3MpKpT5MVCzuhcac5RN7JGih_1OQ)

逻辑常项简称常项, 它与变项是逻辑学里的一对范畴. 二者是对立统一关系. 常项相对于变项而言, 是同一类型的思维逻辑形式内的不变部分; 变项相对于常项而言, 是同一类型的思维逻辑形式内的可变部分. 在某一类型的思维形式里, 无论变项如何变化, 只要常项不变, 这一类型的思维形式就不变. 如果常项变了, 这一思维逻辑形式就变了. 常项在思维逻辑形式中起决定作用, 它是区分思维逻辑形式的标志. 这是二者的区别性, 可谓之对立性.

[论句子语义中的命题_李勤 *燕山大学学报: 哲学社会科学版* , 2006](https://scholar.google.com/scholar_url?url=http://www.cqvip.com/qk/83724x/200601/21269658.html&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=3885440512858199366&ei=M-IfYd7tMc2By9YP-IOS4AY&scisig=AAGBfm0be8IMHRtq17w0m1al_BviPgr6Cw)

本文从命题的角度对句子的语义组织进行探讨,分析了命题在语言学中的理解及其与句子的关系。认为命题是与句子的事态有关的语义,但也并不能完全摆脱句子的模态语义。文章重点阐述了对命题结构的两种不同理解和三种分类。

[命题推理的新图式(英文)，黄万徽. 华中师范大学学报 (自然科学版), 1988](https://www.cnki.com.cn/Article/CJFDTotal-HZSZ198804002.htm)

本文引进新图式的概念,并且给出一个关于命题推理有效判定的方法。它解决了证明论中命题逻辑部分的一个重要问题。由于此方法直观,机械,可用于计算机对人工智能问题的处理。

[论命题推理前提假值的先舍后取——兼及命题推理有效必然性的理论阐释，倪荫林. 信阳师范学院学报: 哲学社会科学版, 2003](http://www.cqvip.com/qk/80765x/2003004/8890785.html)

推理的目的在于使前提的真传递到结论 ,因而必须舍去前提中的假值。结论是以扩大断定范围的方式必然地保有前提的真。在验证推理是否有效时 ,将前提的真与假值均考虑在内 ,看结论是否完全包含了前提断定的事态 (真 ) ,以确定推理是否必然有效。

[Propositions_Bealer G. Mind, 1998](https://academic.oup.com/mind/article-abstract/107/425/1/963602)

本文主要解决两组问题。第一个与还原论有关，特别是试图将命题还原为外延实体——外延函数或集合。第二组涉及细粒度内容的问题——传统的“西塞罗”/“塔利”谜题和它们最近面临的科学本质主义的变体。在对问题进行表征后，我概述了一种非还原论的方法——代数方法——它避免了与还原论相关的问题。然后我继续展示该理论如何结合非柏拉图（以及柏拉图）的呈现方式。当这些以非描述性方式实施时，它们会产生文章一直无法理解的细粒度区别。

[Inference method for fuzzy quantified and truth qualified natural language propositions](https://onlinelibrary.wiley.com/doi/abs/10.1002/(SICI)1520-6440(200002)83:2<22::AID-ECJC3>3.0.CO;2-S?casa_token=giJntNow-IYAAAAA:qEaWCJ7WHXEDfCvcxBdbuhQic1JPrXOWQ-YJgBaheGnAOIPUazyr5u0hOLwzOfiqHFSdnmTmmfEMfw)

本文提出了一种模糊量化和真实限定的自然语言命题的推理方法。例如，对于“大多数高个子男人很重是真的”，可以通过推理推导出修改后的命题“或多或少高个子男人很重是真的”。对于量词“more or less”，模糊量词“many”可以通过解析推导出来。三种类型的模糊量词（单调非增型如“few”，单调非减型如“most”，单峰型如“several”），以及单调注入型真值量化限定词如真假，都考虑在内。对于包含这些量词/限定词的命题，表明模糊量词可以通过模糊推理解析导出，用于修改量化模糊主题部分。

[Causal inference without counterfactuals: comment. Robins J M, Greenland S.  Journal of the American Statistical Association, 2000](https://www.jstor.org/stable/2669381)

统计学，潜在因果，反事实

[Symposium: Facts and propositions, Ramsey F P,Proceedings of the Aristotelian Society, Supplementary Volumes, 1927](https://www.jstor.org/stable/4106403)

任何术语判断、信念或断言可能会调用的内容进行逻辑分析。

[Propositions, warranted assertibility, and truth, Dewey J. The Journal of Philosophy, 1941](https://www.jstor.org/stable/2017978)



[Events and propositions, Chisholm R. Noûs, 1970: 15-24.](https://www.jstor.org/stable/2214288)



[Where do propositions come from, Perfetti C A, Britt M A.  Discourse comprehension: Essays in honor of Walter Kintsch, 1995](https://books.google.es/books?hl=zh-CN&lr=&id=KSxwB0xrw7UC&oi=fnd&pg=PA11&dq=propositions++&ots=4DHJiAkyUf&sig=vFrmC09r0IazZALyK9umxST5lys)

### Propositions in NLP

#### Must-read paper

[自然语言显式命题自动识别和解析方法，刘璐，中文信息学报，2021](http://124.16.136.79/CN/article/downloadArticleFile.do?attachType=PDF&id=3085)

自然语言中包含很多显式命题,正确理解这些命题是理解文本信息的关键。正确识别显式命题并解析其 中的关键成分有助于理清语言中的逻辑关系、辅助自然语言理解。该文基于百度百科数据构建了自然语言显式命 题标注数据集,并提出两个研究任务:自然语言显式命题自动识别和命题关键成分解析。其中,显式命题自动识别 任务判断一个自然语言句子是否为命题;显式命题关键成分解析任务从已获取的命题中解析出支撑该命题成立的 关键成分。

[中文篇章级句间语义关系体系及标注，张牧宇,秦兵,刘挺，中文信息学报,2014](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=205)

总结了中文篇章及语义分析的特点,提出面向中文篇章句间关系的层次化语义关 系体系,对句间关系类型进行详细描述,并在新闻语料上进行了标注。提出了一个汉语类比推理任务，构建了该任务的CA8数据集，并探讨了向量表示、上下文特征和语料库对类比推理的影响。

[中文篇章级句间语义关系识别，张牧宇,宋原,秦兵,等，中文信息学报,2013](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=1780)

对中文篇章句间关系识别任务进行初步探索,他们根据文本单元间是否存在篇章连接词将关系分为显式篇章句间关系和隐式篇章句间关系。

##### NLI

[The pascal recognising textual entailment challenge, Ido Dagan, 2005](https://scholar.google.com/scholar_url?url=https://link.springer.com/chapter/10.1007/11736790_9&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=8752976529297747714&ei=REwgYbSLI8WKy9YPtvGwiA0&scisig=AAGBfm1aKA1c65kgwAUaB8vl-aT1wpbceg)

提出了Natural Language Inference(NLI)，一种典型的需要逻辑推理的任务，其目的是确定一个假设是否可以合理地包含在一个前提中。

[A large annotated corpus for learning natural language inference，Samuel R. Bowman，2015](https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/1508.05326&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=11107072381442434916&ei=Bk0gYZCWOemSy9YPps2T4AM&scisig=AAGBfm0OdYq0b-IpWoYd6Bq7ER52jNZNGg)

引入了斯坦福自然语言推理语料库(SNLI)，这是一个新的、免费提供的标记句对集合，由人类根据图像字幕执行新的基础任务编写。它有 570K 对，比所有其他类型的资源大两个数量级。这种规模的增加允许词汇化分类器胜过一些复杂的现有蕴涵模型。

[A broad-coverage challenge corpus for sentence understanding through inference，A Williams，2017](https://arxiv.org/abs/1704.05426)

本文介绍了多流派自然语言推理 (MultiNLI) 语料库，该数据集旨在用于开发和评估用于句子理解的机器学习模型。除了作为可用于NLI任务的最大语料库之一，该语料库拥有 433k 个示例，它改进了其覆盖范围内的可用资源：它提供了来自十种不同类型的英语书面和口语的数据——这使得评估系统成为可能关于语言的几乎全部复杂性。

[GLUE: A multi-task benchmark and analysis platform for natural language understanding, Wang A,  2018](https://arxiv.org/abs/1804.07461)

引入了QNLI数据集，是从斯坦福问答数据集 v1.1 (SQuAD) 自动派生的自然语言推理数据集。SQuAD v1.1 由问题-段落对组成，其中段落中的一个句子（来自维基百科）包含相应问题的答案（由注释者编写）。通过在每个问题和相应上下文中的每个句子之间形成对，并过滤出问题和上下文句子之间词汇重叠低的对，将数据集转换为句子对分类。任务是确定上下文句子是否包含问题的答案。这个原始任务的修改版本取消了模型选择确切答案的要求，但也消除了答案总是存在于输入中并且词汇重叠是可靠提示的简化假设。QNLI 数据集是 GLEU 基准测试的一部分。

[SciTaiL: A Textual Entailment Dataset from Science Question Answering，Tushar Khot，AAAI，2018](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17368)

文章提出了一个用于文本蕴涵的新数据集和模型，源自将多项选择题的回答视为蕴涵问题。 作为向前迈出的一步，文章证明了使用一种利用语言结构的新神经模型可以将 SCITAIL 的准确率提高 5%。

##### Argument reasoning

[The argument reasoning comprehension task: Identification and reconstruction of implicit warrants，I Habernal，2018](https://arxiv.org/abs/1708.01425)

推理是自然语言论证的关键部分。要理解一个论证，必须分析它的依据，这就解释了为什么它的主张是从它的前提得出的。由于论点是高度情境化的，权证通常是预设的并且是隐含的。因此，理解不仅需要语言理解和逻辑能力，还需要常识。在本文中，文章开发了一种系统地重构权证的方法。

[Analogical reasoning on chinese morphological and semantic relations，Li S, Zhao Z, Hu R, et al. arXiv preprint arXiv:1805.06504, 2018](https://arxiv.org/abs/1805.06504)

建立一个基于新闻语料库的数据集，探讨汉语文本中句子之间关系的识别任务。根据语篇单位之间是否存在语篇连接词，将语篇关系分为显性语篇关系和隐性语篇关系。

#####  Reading comprehension  

 [RACE: Large-scale ReAding comprehension dataset from examinations，G Lai，2017](https://arxiv.org/abs/1704.04683)

文章提出了 RACE，这是一个新的数据集，用于对阅读理解任务中的方法进行基准评估。RACE收集了12至18岁中国中学生英语考试，由人类专家（英语教师）生成的近28,000篇文章和近100,000个问题组成，涵盖了精心设计的各种主题以评估学生的理解和推理能力。

[Reclor: A reading comprehension dataset requiring logical reasoning，W Yu，2020](https://arxiv.org/abs/2002.04326)

文章介绍了一个新的阅读理解数据集，需要从标准化研究生入学考试中提取的逻辑推理 (ReClor) .



#### Newer and important

[Logiqa: A challenge dataset for machine reading comprehension with logical reasoning, Jian Liu, IJCAI, 2020](https://arxiv.org/abs/2007.08124)

机器阅读是测试自然语言理解能力的一项基本任务，它在很多方面都与人类的认知密切相关。随着深度学习技术的兴起，算法模型可以在简单的 QA 上与人类的表现相媲美，因此提出了越来越具有挑战性的机器阅读数据集。尽管已经整合了证据整合和常识知识等各种挑战，但人类阅读的基本能力之一，即逻辑推理，尚未得到充分研究。文章构建了一个名为 LogiQA 的综合数据集，该数据集源自专家编写的用于测试人类逻辑推理的问题。

[Logic-Driven Context Extension and Data Augmentation for Logical Reasoning of Text，Siyuan Wang，2021](https://arxiv.org/abs/2105.03659)

文本的逻辑推理需要理解文本中的关键逻辑信息并对其进行推理。用于逻辑推理的大规模预训练模型主要关注文本的词级语义，同时努力捕捉符号逻辑。在本文中，文章通过理解文本中的逻辑符号和表达来得出答案。基于这些逻辑信息，不仅提出了上下文扩展框架，还提出了数据增强算法。文章的多模型集成系统是第一个在 ReClor 的 EASY 集和 HARD 集上超越人类表现的系统。

[Natural language inference in context– investigating contextual reasoning over long texts, Hanmeng Liu,AAAI,2021](https://arxiv.org/abs/2011.04864)

长文本上下推理，专家设计，提出ConTRoL数据集，研究长文本的NLI，并检查更复杂的上下文推理类型。

[CLUTRR: A Diagnostic Benchmark for Inductive Reasoning from Text, Koustuv Sinha, 2019](https://arxiv.org/abs/1908.06177)

CLUTRR 要求 NLU 系统推断短篇小说中人物之间的亲属关系。成功执行此任务既需要提取实体之间的关系，也需要推断控制这些关系的逻辑规则。输入是一个给定的段落和一个查询对，输出是一对之间的关系。



#### Datasets

[SciTail Dataset](https://allenai.org/data/scitail)

SciTail 数据集是根据多项选择科学考试和网络句子创建的蕴涵数据集。每个问题和正确答案选择都被转换成一个断言陈述以形成假设。

[LogiQA Dataset](https://arxiv.org/abs/2007.08124)

该数据集源自专家编写的用于测试人类逻辑推理的问题

[ReClor Dataset](https://whyu.me/reclor/)

ReClor 是从标准化研究生入学考试的逻辑推理题中提取的数据集

ConTRoL Dataset

ConTRoL 是由专家设计的用于长文本上下推理的数据集

RACE Dataset

CLUTRR Dataset

CLUTRR 是一个推断短篇小说中人物之间的亲属关系的数据集





