---
name: blog-skill
description: >-
  Researches recent (default: past month) papers, company/personal blogs, and
  social leads; plans a Chinese blog outline; then writes the full post in a
  clear, detailed scholarly register. Use when the user asks for /blog-skill,
  a research blog, 调研写作, insight 整合, or a Chinese technical/industry blog
  from recent sources. Runs research → outline → draft continuously without
  pausing between phases. One heading style per post.
disable-model-invocation: true
---

# Blog Skill / 调研型中文 Blog

## When to use / 适用时机

**EN:** Use this skill to research recent sources (default window: the past month), synthesize insights with citations, plan a Chinese blog title and outline, then write the full post. Trigger on: research blog, 调研写作, insight 整合, 近一个月文献/博客调研, Chinese technical or industry blog from recent sources.

**中文：** 用于「近一个月（可覆盖）文献与行业文字调研 → 规划标题与章节 → 撰写中文 blog」。触发词见上。

## Workflow / 工作流

**EN:** Run continuously in order: (1) Research → (2) Planning → (3) Writing. Do **not** pause between phases for confirmation unless the user explicitly asks to stop after a phase.

**中文：** 按顺序连续执行：调研 → 规划 → 撰写。阶段之间**不停顿、不等待确认**；仅当用户显式要求分步时才停。

## 1. 调研

进行广泛的调研，着眼于距离当前一个月以内的文章，包括但不限于：

- 高质量论文（需要核验，核验方式为观察该论文作者或作者组织是否为该行业大牛）
- 该行业巨头的公司的博客，以及博客下的引文或文中提到的文章（如有）
- 该行业高质量的个人博客，以及博客下的引文或文中提到的文章（如有）
- 该行业巨头以及高质量个人的社交媒体（如 X、小红书、知乎）帖子，如果为推荐其他文章的帖子，可以进而调研被推荐的文章

调研后获取其中有价值的 insight ，整合大家的思想。如果大家对于部分内容的定义或理解不同或矛盾，可以从中选择你认为最有价值的观点，或是客观保留所有观点。注意要保留出处。如果有出彩的图片素材，亦可以保留。

尤其对于高质量博客，可以学习其写作风格。

## 2. 规划

随后需要开始进行写作规划，将要写的 blog 标题拟好，并确立其结构，分出不同的部分、章节。

每个章节名可以在两种风格当中选择：清晰简洁或引人入胜。只允许使用短语或词语，不允许使用句子，尤其绝对不允许使用问句。

对于清晰简洁的章节标题风格，可以取“摘要”“方法”这类传统论文式标题，也可以是“Anthropic 的巧思”“机器学习与深度学习”这类更加具有暗示性的，能够引发想象的标题。”清晰简洁“限制语言风格，不限制其具体格式。

对于引人入胜的章节标题风格，可以取”Altman 与 Dario 的赌约“”进驻火星“”蝴蝶效应与厄尔尼诺事件“这类具有适当的隐喻、夸张、故事化，更有画面感的标题。”引人入胜“限制其语言风格，同样不限制具体格式。

同一篇 blog 全文只允许选用一种章节标题风格（但不要求句法同构，即不一定要是同一个格式的短语），不得混用。若文章主题为较为严肃的科学综述、工程分项，或研究型文章，请一定选择清晰简洁的风格；对于非严肃的文章，如浅显的科普、生活经验分享等等，可以选择引人入胜式的标题，也可以选择清晰简洁的标题。

选定风格后，再拟章节名。

标题之间必须存在清晰的逻辑关系，能反映出行文思路。

## 3. 撰写

接着按照拟定好的结构开始撰写中文 blog 的正文具体内容，注意语言风格必须清晰而详实：

- ”详实”是指需要涵盖尽量多的内容，不允许为了迎合用户而简化内容，导致文章传达的信息过少，其中的知识不足以满足受众的需求。但是注意，不要为了追求详实而将错误的、空泛的内容加入文章中，对于没有价值的观点，直接丢弃即可。宁可不写某支线，也不注水；信息不足时删减范围，不得用空泛表述撑篇幅。另外，对于调研到有不同定义或是理解的内容，若同时存在几个主流观点，可以分别陈述；若主流观点存在时间上的演进，可以按照时间线陈述；若显然有一个观点的受众多于其他所有观点，即只存在一个主流，则只陈述该观点。
- “清晰”是指需要保证讲解和阐述清晰易懂，总体语言风格需要接近“在与同行进行由浅入深的交流的学者”。语言尽量简洁而易懂，可以通过专业术语提高简洁程度，但需要在专业术语旁给出解释或注释。不允许说非主流的简称或是黑话，例如抖头西（抖音、头条、西瓜视频），但鼓励一些主流的简称方式，如“AI4Science”中的 4 指代 for。对于已经详细写过的内容，在后续的撰写过程中，不允许大段地重复阐述，如果需要再次提及，尽量用清晰而又较短的方式（如，先前我们在 xxx 位置提到过，xxxxxxx），这一点需要尤其注意，防止重复讲解相同的内容。

需要注意以下问题：

- 不要过度使用不恰当的比喻——对于可以直接用清晰的语言解释清楚的概念或内容，不要硬凑比喻，否则受众的注意力会被绕开。但是注意，对于难以解释清楚的地方，可以适当使用比喻，但比喻要尽量简洁易懂，并且仅用于解释该部分内容，不允许蔓延到其他部分或全文。
- 避免 AI 味儿——尽量避免使用例如“不是……而是……”的这类 AI 常用句式
- 不要使用过度幼态化的语言——禁止把受众当成傻子。不要使用过度像“面向儿童发言”或是“向小学生讲解内容”的讲话方式。
- 关于受众——博客的受众是“具有一定专业知识的同行”。注意，这里的同行可能是对该领域十分熟悉的同行，也可能是只在该领域所从属的大领域有学习，却没有接触过该领域的人。
- 不要包含不必要的开场——不要擅自增加“今天我们向大家讲解的主题是……”一类的客串式开场，也不要“大家好”之类的客套，尽量使用与论文的 abstract 或是 introduction 风格一致的开场，直接平铺。不过，如果这是在一次与用户的多轮交互中，并且你理解了用户“为何要写这篇 blog”以及“用户在与这篇 blog 的主题相关的方向做了什么工作”，可以适当融入进来。
- 不要擅自使用扩展内容——这里的扩展内容是指用户的个人信息、交互记录、资料库等等，若用户没有特殊要求，请不要将这些内容写进 blog 或是在 blog 中暗示。
- 尽量少使用破折号和冒号——对于解释性内容，尽量少地使用破折号和冒号，而是使用连贯的语言文字来解释，由此防止语言割裂。

## Phase continuity / 阶段衔接

**EN:** Research, planning, and writing run as one continuous pass. Do not stop after the outline to ask for approval unless the user explicitly requests a pause.

**中文：** 调研、规划、撰写一次连续做完。不要在大纲后停下来征求确认，除非用户显式要求暂停。

## Checklist

- [ ] 默认时间窗：近一个月（用户可覆盖）
- [ ] 洞察带出处；图片素材可保留
- [ ] 全文仅一种章节标题风格
- [ ] 章节名为短语/词语；禁句子；禁问句
- [ ] 宁可不写支线，也不注水
- [ ] 术语首次解释；禁非主流黑话；已述内容短回指
- [ ] 比喻克制；禁幼态；禁客套开场
- [ ] 不擅自写入用户个人信息/交互记录/资料库
- [ ] 阶段连续，无确认闸门
