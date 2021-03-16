# LogTree: A framework for generating system events from raw textual logs
Proceedings of ICDM, pages 491–500, December 2010
现代计算机系统会产生大量的系统日志，这些日志用来理解复杂的计算机行为。自动化的日志分析最大的挑战是从原始日志文件生成系统事件。我们首先介绍了现有技术的缺点，然后提出了Logtree，一种新的把原始日志转换为系统事件的方法。Logtree在聚类过程中利用现有日志的格式和结构信息生成系统事件。另外，提出一种索引数据结构（信息段表）能显著的提高事件生成的效率。在真实日志数据集上的实验证明了该算法的效率和效能。

# LogSig: Generating system events from raw textual logs.
Proceedings of ACM CIKM, pages 785–794, 2011
现代计算机系统会产生大量的日志，系统管理员和领域专家利用这些数据理解和优化系统行为。大部分的日志数据是无结构的文本数据。日志信息通常是相对短的文本消息但是可能含有大量的词汇，使用传统的文本聚类算法效率低效。其他相关方法有不同的限制或只在某些特定的系统日志有很好的效果。我们提出了一种消息签名算法logsig，把文本日志生成系统事件。通过搜索最具有代表新的消息签名，logsig把日志信息分类成一组事件类型。Logsig能够处理不同类型的日志数据，同时结合相关的领域知识达到很高的性能。在5个真实日志数据集的实验结果表明logsig总体性能超过其他算法。

# Mining partially periodic event patterns with unknown periods.
Data Engineering, 2001. Proceedings. 17th International Conference on, pages 205–214. IEEE, 2001
周期性行为在实际应用中很普遍。但是在某些情况下，周期是间歇性出现的，我们研究这些间歇性的模式，称为P-patterns。在p-patterns中我们同时要考虑不精确的时间信息，噪声数据等。把P-patterns的挖掘分成两个子任务：1）发现P-patterns的周期，2）挖掘序列关联，对第二个子任务使用基于层次的算法。对第一个子任务我们开发了基于卡方检测的新方法，并且在有噪声的情况下检测了该方法的性能。针对前面的子任务开发了两个算法，周期优先算法和关联优先算法。实验结果表明关联优先算法对有噪声的数据有较好的适应性，周期优先算法有更好的性能和灵活性。

# An integrated framework on mining logs files for computing system management.
Proceedings of the eleventh ACM SIGKDD international conference on Knowledge discovery in data mining, pages 776–781. ACM, 2005
系统管理的传统方法主要依赖领域专家把领域知识转换成操作规则与策略。但这是一个麻烦的，需要大量人力资源同时容易出错的过程。我们建立了一个集成框架，通过挖掘系统日志来实现自动化的管理。特别地，通过文本挖掘技术把日志消息分类为通用的事件，同时考虑日志的时间特征来提高分类的准确性，基于时间的挖掘技术来发现不同事件的关系，同时利用可视化的工具来评估和验证管理员感兴趣的时序模式。

# Discovering lag intervals for temporal dependencies
Proceedings of the 10th International Conference on Network and Service Managemen. IEEE, 2014
从序列数据中挖掘隐含时序依赖的时间延迟可以应用到多个领域，包括系统管理，股票数据分析，气候监控等领域。在时序依赖中挖掘时间延迟可以更好的理解时序数据以及预测变化趋势。传统的方法使用预定义的时间窗口来分析序列数据或使用统计技术来识别时序依赖。但是这些方法在处理波动的，有噪声的，依赖关系交替出现的数据时存在很大的问题。我们提出了一种参数模型来描述有噪声的时间延迟。提出最大期望方法来发现时间延迟。同时提出了一种近似方法在不牺牲准确性的情况下增加分析对象的可伸缩性，实验展示了该方法的效果和性能。

# Natural event summarization
Proceedings of the 20th ACM international conference on Information and knowledge management, CIKM’11, pages 765–774, Glasgow,Scotland, 2011. ACM
事件挖掘是一种理解计算机行为的有效方式。目前的研究焦点从事件挖掘转移到了事件总结。事件总结对某一方面的事件序列提供了一种易于理解的解释。我们提出了一种新的框架“自然事件总结”，可以通过柱状图来总结事件序列，并捕获事件之间的时序关系。我们的框架使用最小描述长度准则来指导这一过程，以便达到准确性和简洁性的平衡。我们使用多种方法来缩减问题空间。在人工数据和真实数据上的实验结果表明我们的方法能够生成有用的事件总结，同时具有健壮性和可扩展性。

# Meta: Multi-resolution framework for event summarization
SIAM International Conference on Data Mining, 2014
事件总结是一种从原始数据挖掘和组织事件模式的一种有效途径。他可以让管理员快速的获取事件的主要概况。由于缺少集成的总结方法，我们提出一种可扩展的框架——META，让管理员从不同的视角来有选择的抽取和总结事件。我们使用一种精心设计的数据结构来存储原始事件。在数据模型上我们定义了一种总结语言包括一系列元操作以处理元数据。我们提出了5种常见的总结任务，这些任务都可以很容易的使用总结语言表达。在人工数据和真实数据上的实验验证了改框架的有效性和性能。

# Searching similar segments over textual event sequences.
Proceedings of the 22nd ACM international conference on Conference on information & knowledge management. ACM, 2013: 329-338.
相似性搜索在符号和时序数据集中被广泛的研究。文本事件序列是一系列的事件，每个对象都是一段描述事件的消息。系统日志就是一种典型的文本事件序列，每个文本消息记录了内部系统的操作，状态，配置修改，执行错误等。事件序列的相似性段揭示了相似的系统行为，这有助于系统管理员诊断系统问题。现有的方法只专注于无序的数据。子串匹配方法能发现在序列中发现匹配的段，但是这些序列是单值而不是文本。我们提出了suffix matrix方法在文本序列数据中发现相似段。主要包括两个步骤，位置敏感哈希和后缀数组。同时支持k-相异段搜索。k-相异段指在一个查询序列中最多有k个相异的事件。通过提出的random sequence mask方法在不增加时间代价的情况下有很高的概率找到所有k-相异段。在真实日志数据集上的实验结果表明优于已存在的方法。

# Detecting large-scale system problems by mining console logs.
Proceedings of ACM SOSP, pages 117s132, 2009.
大规模数据中心的控制日志很少帮助管理员检测问题，因为其包含了大量由不同软件提供商开发的不同软件组件生成的消息。我们提出了一个通用的方法利用这些信息来自动检测系统运行时的问题。通过信息检索和源代码分析来解析控制日志并生成合成的特征，然后使用机器学习方法分析这些特征以检测问题。我们展示了以前方法不能达到的效果，并展示了如何精炼结果以更友好的方式展示给用户。通过暗黑游戏服务器和Hadoop文件系统来验证我们的方法，以很高的准确率检测了大量的真实问题。
