# 如何应对记忆难点（Leech）

原文：[Dealing with Leeches - Control-Alt-Backspace (controlaltbackspace.org)](https://controlaltbackspace.org/leech/)

间隔重复的一个基本原则是[区分简单的卡片和困难的卡片](https://controlaltbackspace.org/memory/spaced-repetition/#separating-easy-things-from-hard-things)。我们可以降低对简单知识点的复习频率，同时增加对困难知识点的复习次数。这真的非常有效。

遗憾的是，有些学习卡片不仅难，而且难到了**极点**。如果不采取特殊措施，我们可能会反复忘记并重新学习这些卡片，导致它们占用大量学习时间却收效甚微。间隔重复学习社区将这类极难掌握的卡片形象地称为 **leech**，因为它们就像**水蛭**一样，不断吸走你宝贵的学习时间。

Anki 会在检测到你已经学习并遗忘同一张卡片八次时（这个阈值可以调整），将其标记为记忆难点（leech）。随后，Anki 会提醒你发现了一张记忆难点，并自动将其暂停，使其不再出现在复习中，直到你采取进一步行动。此时，如何处理这张卡片就需要你自己来决定了。

在这次深入探讨记忆难点（这让人联想到[《神奇校车》](https://en.wikipedia.org/wiki/The_Magic_School_Bus)系列的奇妙冒险！）的过程中，我们将首先讨论如何预防这些记忆难点产生，之后探索当它们悄然出现时的应对策略，最后我们会简要回顾如何在 Anki 中识别这些记忆难点并采取相应措施。

## 预防记忆难点

应对记忆难点的最佳策略是防患未然。当你第八次忘记一张复习卡片时，你可能已经反复复习了几十次，这意味着你在这张卡片上已经浪费了大量时间。要避免这种情况，可以采取以下措施：制作[精确的](https://controlaltbackspace.org/memory/designing-precise-cards)卡片，遵循二十条记忆规则（详情请参阅前文链接），并在发现卡片存在精确性问题时立即修改。这些做法通常能有效预防潜在的记忆难点成为长期问题。

在 Anki 复习过程中，遇到暂时无法解决的问题卡片时，最好采取「标记并暂停」的策略，而不是强行继续。这样可以避免浪费宝贵的复习时间，留待日后有充足时间再来修复。AnkiMobile 用户可以将「标记并暂停」功能设置为向下滑动手势，以提高操作效率。桌面版用户则可以在复习时按 `*@` 组合键（发音为「splat-at」，这个小技巧可能有助于记忆）来实现同样的效果。当你准备好修复这些问题卡片时，只需在卡片浏览器中搜索 `tag:marked` 即可轻松找到它们。

**值得研究的领域**：我认为 Anki 的记忆难点检测算法还有改进空间。这种改进可能有助于减少那些尚未被系统识别出的记忆难点对学习时间的负面影响。一个可能的简单改进方法是将触发阈值从目前的八次遗忘调低。然而，由于我个人并未在这方面进行过实际实验，因此在这里我不会给出任何具体的建议或推荐。

## 六步决策框架

接下来，让我们来探讨如何处理已经被识别出的记忆难点。首要任务是找出你总是忘记答案的根本原因。一旦你明白了问题所在，就可以采取以下几种广泛的策略：重新表述问题，使其更易理解；补充必要的背景知识；删除不重要的问题；降低那些不需要立即掌握的问题的优先级；或者编写助记来辅助记忆。

为了更有效地处理记忆难点，这里有一系列排好顺序的问题供你思考。你不必严格遵循这份清单，但在你形成处理记忆难点的直觉之前，不妨将这份问题清单放在手边以供参考。

### 概要

首先，我会对这些问题进行一个整体概述，然后我们再深入探讨每个问题的细节。

1. 我经常忘记这张卡片是否有明显的原因？

   - 例如，问题表述不够清晰，或者违反了[最小信息原则](https://controlaltbackspace.org/memory/designing-precise-cards/#questions-should-ask-exactly-one-thing)。

   - **如果确实如此**：修改卡片内容，然后重新复习。有时可能还需要增加一两张新卡片。

2. 我能否通过添加额外的卡片来强化记忆这个问题？

   - 你可能缺乏重要的背景知识，或者遇到了记忆干扰。这时可以通过学习一两个相关的具体问题来解决这个问题。

   - **如果确实如此**：为补充背景知识添加一两张新卡片，然后重新复习原卡片。

3. 这张卡片是否真正考察了我想掌握的知识点？

   - 可能你把问题表述得难以记忆，而且并不完全符合你的学习目标。

   - **如果确实如此**：通过添加新卡片或修改现有卡片，使其更贴合你的学习需求，然后重新复习。

4. 这张卡片是否不那么重要？

   - 如果卡片本身没有明显问题，可以考虑是否可以直接删除，为学习更容易的内容腾出时间。虽然一些关键内容不适合删除，但大多数内容都可以。

   - **如果确实如此**：果断删除，不要犹豫。

5. 我是否可以暂缓学习这张卡片？

   - 如果这张卡片的优先级并不是那么高，而你有其他更重要的内容需要学习，可以考虑先专注于那些重要内容，之后再决定如何处理这张卡片。

   - **如果确实如此**：暂停学习这张卡片，保持对其内容的无知状态，直到有时间找到更好的学习方法。

6. 我能否为这张卡片编一个助记？

   - 如果这张卡片很重要，本身没有问题，你又急需掌握其内容，但总是记不住，那就花点心思设计一个好的记忆技巧。同时，你可能还需要添加其他卡片来帮助记忆这个助记。

   - **如果确实如此**：编一个助记，添加一张卡片来帮助学习这个助记（或者至少在原卡片背面写下这个方法，以防遗忘），然后重新复习原卡片。

如果你已经认真尝试了所有这些方法，却仍然无法有效掌握，你可以考虑将这张卡片重新放回复习，即使它已经被标记为「记忆难点」。但要注意，如果你这么做，很可能会继续遗忘这张卡片。这些卡片之所以被标记为「记忆难点」，是因为除非你改变学习策略，否则很难真正掌握它们。在 Anki 中，如果你再次遗忘这张卡片 4 次，它会再次被标记为「记忆难点」。

### 我经常忘记这张卡片是否有明显的原因？ 

通常，你很清楚为什么总是记不住一个「记忆难点」问题的答案，只是一直没有抽出时间去解决它。有时当「记忆难点」的提示出现时，你可能会有一丝恍然大悟：「啊，我一直不喜欢这个问题。」其他时候，尤其是对于初学者来说，问题可能不那么明显，但稍加思考就能发现问题的症结所在。可能是问题表述不清晰，或者因为措辞不当容易与其他问题混淆，又或者它没有遵循最小信息原则。也可能是你对卡片上使用的某些术语或概念不太理解。

**解决方法**：确保卡片是[精确的](https://controlaltbackspace.org/memory/designing-precise-cards)，并且你完全理解它。如果有需要，可以添加新卡片来完善你的理解。

### 我能否通过添加额外的卡片来强化记忆这个问题？

这种方法可以解决不同的问题：

- 如果你对某个主题缺乏足够的背景知识，很可能会影响你理解和回答相关问题（请谨记学习的[规则 #1](https://super-memory.com/articles/20rules.htm)：**不理解就不要学习！**）。遇到这种情况时，不妨进行一些补充研究，增加一些辅助性的学习卡片。这样不仅可以帮助你全面理解主题，还能将你的卡片从记忆难点中拯救出来。

- 记忆难点通常出现在你无法清楚区分两个相似词语或概念的时候（学术上称之为**记忆干扰**）。你可能经常混淆它们的答案，导致两者都成为记忆难点。但是，如果你添加一张新卡片专门用于区分这两个概念，神奇的是，这三张卡片可能突然都变得易于掌握。这个方法听起来有些不可思议，但确实屡试不爽。（不过在采用这个方法之前，请先确认问题不是由于卡片设计不当或问题表述[不精确](https://controlaltbackspace.org/memory/designing-precise-cards)造成的。如果是这种情况，应该先改进问题本身，而不是试图用额外的卡片来弥补缺陷。）

- 有时，你可以从一个复杂的问题中提取出一部分，制作成一张新的问题卡片。这张新卡片不仅本身有学习价值，还能帮助你更好地记忆原来的记忆难点。举个例子，我曾经总是记不住德语单词「halbkugelig」（意为「半球形的」）。经过 31 次复习和 8 次遗忘后，我才意识到问题在于我不能立即想起「Kugel」表示「球体」或「球」（虽然稍加思考就能推断出来）。一旦我在另一张卡片上专门学习了这个词，原本的难题就迎刃而解了。

**解决方法**：首先确定你在理解问题时遇到的具体困难，然后深入学习相关内容，最后编写卡片来巩固所学知识。

### 这张卡片是否真正考察了我想掌握的知识点？

你可能采用了一种更难回答的设问方式（例如，[使用枚举](https://controlaltbackspace.org/memory/designing-precise-cards/#questions-should-not-ask-you-to-enumerate-things)）。不妨尝试用一种更简单的方式重新设计问题，这种新的问题形式可能同样有效，甚至更好地精确测试[你真正想掌握的知识点](https://controlaltbackspace.org/memory/designing-precise-cards/#the-importance-of-asking-the-right-questions)。

**解决方法**：适当修改卡片内容并重新加入复习，或者根据需要创建新卡片并删除旧卡片。

### 这张卡片是否不那么重要？

如果这张卡片本身没有明显问题，只是**难以**记忆，不妨考虑是否可以放弃它，将宝贵的学习时间用于其他更容易掌握的内容。通常，反复强记那些始终难以记住的内容并不是明智之举。

起初，很多人会觉得简单地删除难以掌握的学习内容是一种奇怪甚至荒谬的做法。某种程度上，这可能让人感觉像是一遇到困难就不光彩地「放弃」了。但我认为，这主要是因为我们的系统学习经验通常来自学校教育，在那里我们往往会根据对特定指定内容的掌握程度被评分。因此，我们会觉得既然已经为某些内容制作了复习卡片，就应该确保完全掌握这些内容。

然而，一旦离开学校，情况往往大不相同——事实上，即使在为考试学习时，情况也常常如此。学习的主要目标通常是数量：你希望在愿意且能够投入的学习时间内，掌握尽可能多的有用信息。这意味着，如果某个知识点占用了过多的时间，而删除它可以让你学习到其他几个有用的信息点。如果这张卡片不是特别重要，这可能是一个明智的取舍。

让我们来看看具体数据。根据 SuperMemo 网站的[理论文章](https://super-memory.com/articles/theory.htm)，如果我们去掉学习材料中最困难的 10%，学习效率可能会提升高达 **300%**（关于这一数据的详细说明，请参见本节末尾的注解）。请仔细思考这个数字的含义——仅仅通过放弃最难掌握的十分之一内容，你就能在同样的时间里学习**三倍的知识量**。更重要的是，去除最难啃的「硬骨头」还能让学习过程变得更加轻松愉快，有助于保持学习动力。因此，除非那些最困难的内容确实至关重要，否则实在没有理由将它们保留在学习计划中。

所以，如果你发现某个知识点难以理解或记忆，除非它真的很重要，否则你应该认真考虑将其删除。通常情况下，一个知识点变得至关重要主要有两种可能：

- 这个具体的信息本身就很重要（比如你确定考试会考到这一点，或者它是理解其他重要知识的基础）。你可以问自己这样一个问题：「如果将来我因为删除了这个知识点而无法记起这个信息，我会不会后悔自己当初做了个愚蠢的决定？」如果答案是肯定的，那么这就是一张重要的卡片。

- 这条信息是你想要掌握的某个更大知识体系中不可或缺的一部分（例如，一首你想要背诵的诗中的某一行）。

对于那些至关重要的卡片，你需要持续保留并复习。我个人喜欢给这类笔记打上「重要」的标签——这样，将来在查看记忆难点或其他棘手的卡片时，我就能知道在批量删除时应该将这张卡片排除在外。

**理论补充说明**：此前我们提到的 300% 增幅数据来自一篇探讨「通用」间隔重复算法的理论文章。然而，该文章的假设似乎主要针对 SM-11 算法，而非 Anki 所采用的算法。由于我对 SM-11 算法的了解有限，无法确定这些假设是否完全适用于 Anki。（如果有读者在这方面的数学知识比我更为深入，欢迎不吝赐教。在间隔重复领域，尤其是对于我不常使用的算法，我更倾向于实践而非理论研究。）因此，我们不应轻易假定这个数字可以直接应用于 Anki。更何况，这只是一个统计估计值，并非适用于所有情况的精确数据。撇开具体数字不谈，有一点在逻辑上是无可争议的：在任何有效的间隔重复算法中，删除最困难的学习材料，同时增加更多难度适中的材料，都能让学习者掌握更多内容。这是因为最难的材料往往需要更频繁的重复，因此会占用更多的复习时间。（除非你认为更难的材料虽然需要更频繁地复习，却能在更短时间内掌握——这显然是不合理的！）任何有一定使用经验的间隔重复系统用户，只要回顾一下自己在复习过的最难卡片和普通卡片时所花费的时间，就能验证这一点。

### 我是否可以暂缓学习这张卡片？

如果修改卡片内容似乎无法帮助你更好地记忆，而你又不想直接删除它，那么将其暂停，稍后再回来处理可能是个明智之选。这种方法在你需要在紧迫的期限前学习大量信息时特别有用。举个例子，假设你需要在三个月内为一场专业认证考试准备 2,000 个知识点。你可能无法准确预估这三个月里的工作量和可用于学习的时间。在这种情况下，如果遇到记忆难点，将它们暂时搁置一旁是明智之举，这样你就能尽可能快速地消化其他材料。如果你顺利学完了所有其他内容还有剩余时间，那么你可以重新看看这些记忆难点，决定是重新学习、改进表述，还是直接删除并接受在考试中可能遗漏这些问题的事实。即使你没能学完全部内容，你也会比花时间纠结于记忆难点学到更多知识，在考试中可能会取得更好的成绩。

### 我能否为这张卡片编一个助记？

如果你已经尝试了各种方法来改进记忆卡片，但仍然无法记住其内容，而且因为某些原因无法暂时或永久地搁置这张卡片，那么是时候考虑开发一种人为的记忆辅助工具了。实际上，几乎所有的内容都可以应用某种助记技巧，所以如果你还不知道如何使用这些技巧，现在正是学习一些有效助记方法的好时机！本系列后续还会介绍更多相关内容，不过在此期间，你也可以在网上找到大量有用的资源。

我个人比较喜欢的做法是创建两张相关的记忆卡片：一张专门用于记忆助记法本身，另一张则在正面解释助记法，并要求根据这个助记法给出答案。让我举个具体的例子来说明。假设你想用「I Don't Pee Like My Aunt Leona」（我不像我的利奥娜阿姨那样小便）这个首字母缩写来记忆[音乐调式](https://en.wikipedia.org/wiki/Mode_(music))的顺序。（这是我高中管弦乐队指挥教给我们的助记法，听过一次之后我就再也没忘记！为了避免你的想象力过于丰富，我得补充说明一下，显然利奥娜阿姨是装有永久性导尿管的。）第一张卡片的正面可以写：「我用来记忆音乐调式顺序的助记法是什么？」背面则是那个助记短语。第二张卡片的正面可以这样写：「根据助记法『I Don't Pee Like My Aunt Leona』，请按顺序列出音乐调式。」背面则是答案：「Ionian（爱奥尼亚） – Dorian（多利亚） – Phrygian（弗里几亚） – Lydian（利底亚） – Mixolydian（混合利底亚） – Aeolian（爱奥利亚） – Locrian（洛克利亚）」。

这种方法使你能够分别测试对助记法的回忆能力和**应用**能力。这不仅更符合最小信息原则，提高了学习安排的效率，而且当你的助记法效果不佳、持续遗忘时，你能更准确地找出问题所在。此外，这种方法还引入了一定程度的冗余——在回忆助记法时，你可能会激活部分用于回答问题的记忆痕迹；而在回答问题时，又会激活部分用于助记法的记忆痕迹。这就为你已知困难的卡片提供了额外的被动复习机会。

实际上，如果你能很好地运用前五个步骤，你很少需要用到这种方法。不过，这并不意味着你不能或不应该有意识地运用助记法来帮助记忆那些尚未成为记忆难点的卡片，只是你很少会被逼到非用不可的地步。

## 在 Anki 中应对记忆难点

现在，让我为你介绍一些管理 Anki 中记忆难点的实用技巧。首先，你需要定期检查这些卡片并决定如何处理它们。你可以在 Anki 的浏览器中搜索「tag:leech」（或点击侧边栏的「leech」标签）来找出这些记忆难点。我个人建议每一到两周进行一次这样的检查。不过不用担心，即使你检查的频率不那么高，也不会影响你的学习效率。因为 Anki 一旦识别出记忆难点就会自动暂停它们，你只是可能会在这些特定卡片上暂时失去一些知识而已。

当你找到这些记忆难点并决定如何处理后，以下是具体的操作方法。

**注意**：对于以下列出的键盘快捷键，Mac 用户请将 Ctrl 替换为 Command。

- **删除**：如果你决定删除一张难度过大的卡片，只需按 **Ctrl+Delete** 或右击选择「删除」即可。

- **编辑卡片**：你可以直接在浏览器底部的编辑区修改卡片内容。

- **添加卡片**：如果你想在浏览器中添加新卡片，按 **Ctrl+E** 或从菜单中选择「笔记 > 添加笔记」。

- **重新安排复习**：按 **Ctrl+Alt+R** 或右击选择「重新安排」，然后按 Enter 选择默认选项「放在新卡片队列末尾」。这样，这张卡片就会被重新安排学习，就像一张全新的卡片。不过，如果你查看它的卡片信息（**Ctrl+Shift+I**），你还是能看到它之前的学习记录。

有些人会选择直接取消暂停（使用 **Ctrl-J** 快捷键，或右键点击选择「取消暂停」——说实话，我也不明白为什么用「J」而不是尚未被占用的 Ctrl-S）。但我个人更倾向于给卡片一个全新的开始，将其难度重置为 250%。这是因为我们希望卡片已经因改进变得更容易记忆，所以重新安排其复习计划是合理的。当然，如果你认为自己对卡片的改动不足以证明有必要重置其进度——比如你只是想出了一个助记法，而没有实质性地改变卡片内容——那么你可能会更倾向于仅仅取消暂停。

在清理完那些记忆难点后，别忘了移除它们的「leech」标签，以免日后重复修改这些已经改进过的卡片！完成这项工作最便捷的方式是：先逐一浏览所有这类卡片，然后全选它们，接着按下 **Ctrl-Shift-D** 快捷键或右键选择「移除标签」，在弹出的对话框中输入「leech」，最后点击确定即可。

**请注意**：我在上文中描述的删除、编辑、添加和调整「卡片」标签的操作，实际上是在对**笔记**（note）而非卡片（card）进行操作。对于刚开始使用 Anki 的用户来说，这个区别可能不那么重要。但如果你开始使用更复杂的笔记模板来生成多张卡片，那么你就需要意识到这些操作可能会同时影响多张卡片。要深入理解卡片、笔记和笔记模板之间的关系，建议你查阅 Anki 手册中的[关键概念](https://docs.ankiweb.net/#/getting-started?id=key-concepts)部分。