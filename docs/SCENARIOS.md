# Reality RPG — 使用情景演示

> 这一页更侧重展示：如果 Reality RPG 真的工作起来，实际会是什么体验。

[← 返回 README](../README.md)

---

## 场景 1｜截止日前的任务推进，不再只是“别忘了做”

### 传统体验

你知道：

- 周五 17:00 前要交资料
- 还差一个文件
- 对方回复慢

但你未必知道：

- 现在先做什么最值钱
- 是不是应该直接交
- 风险到底有多高
- 等一天会不会明显变差

### Reality RPG 体验

系统会把这件事显示成：

```text
Quest
Submit required document before Friday 17:00

Priority      Q1 // CRITICAL
Difficulty    B+
Danger        IV
Status        waiting one missing file
```

然后进入 Oracle：

```text
Option A  立刻提交           58%
Option B  先追缺失文件       74%
Option C  争取延期           61%
```

并继续告诉你：

```text
如果今天拿到缺失文件 → 84%
如果 24h 内仍无回复     → 51%
```

重点不是“看起来很酷”。

重点是：

> 它把“我好像应该做点什么”，变成“我知道下一步最值得做什么”。

---

## 场景 2｜健身目标不再只是拍照和记感觉

### 传统体验

你知道自己最近有训练，也知道自己想要更清晰的线条、更明显的维度。

但现实里很容易出现：

- 今天练了什么记不清
- 最近到底有没有进步说不准
- 某个动作是不是到里程碑了没概念
- 只是很忙，不一定真的变强

### Reality RPG 体验

Dashboard 会把这些东西组织成：

- **Physical Profile**：体重、体脂、肌肉量、围度、训练表现
- **Skill Tree**：训练知识、动作技术、编程能力、营养理解
- **Achievement**：卧推 60kg、标准引体向上 x8、硬拉 120kg 等
- **Timeline**：什么时候第一次达成、什么时候刷新 PR

例如：

```text
Body Fat        15.8%
Bench PR        60kg
Pull-ups        8
Achievement     Bench Press 60kg unlocked
```

你感受到的不是“多了一个打卡软件”，而是：

> 成长第一次开始留下可回看的结构化记录。

---

## 场景 3｜People Network 会让关系和依赖更清楚

### 传统体验

现实中的很多阻塞，其实不是任务难，而是：

- 卡在人
- 卡在某个机构
- 卡在一个迟迟不回复的关键联系人

通常这件事不会被工具明确标出来。

### Reality RPG 体验

People / Network 会把人物放进现实角色里：

- Friend
- Adviser
- Supplier
- Counterparty
- Stakeholder
- Team Member

并显示：

- 最近互动时间
- 当前关系趋势
- 该人物正在阻塞多少任务
- 是否出现 Single Point of Failure

例如：

```text
Counterparty X
Open Threads        3
Blocking Quests     3
Trust Trend         Stable
Alert               Single Point of Failure
```

这样你会更早发现：

> 问题不是任务很多，而是过度依赖同一个关键人物。

---

## 场景 4｜语音交互不会像聊天机器人一直解释自己

### 传统体验

很多 AI 在后台开始干活时会说一长段：

> “让我来帮助您处理这个请求，我会把它交给后台智能体，它将执行互联网搜索……”

这听上去很“AI”，但实际很吵，也不自然。

### Cyrus / Reality RPG 体验

默认是：

1. 简短承接
2. 真开始访问时，必要时简短播报
3. 其余时间静默执行
4. 有结果再回报

例如：

```text
先生：查一下这家公司值不值得关注。

Cyrus：好的，先生。

System：正在访问互联网。

……静默执行……

Cyrus：查到了，先生。这家公司对当前项目有中等相关性。
如果您愿意，我可以继续比较它与另外两家。
```

这套体验背后，是两层语言同时工作：

- **System Language**：状态与 telemetry
- **Operational Voice**：Cyrus 面向用户的执行语气

所以用户体验上会更像：

> 一个安静、干练、知道什么时候该说话的私人 AI 助理。

---

## 场景 5｜长期来看，它更像一套 Personal Operating System

把这些场景拼起来，你会发现 Reality RPG 的目标其实不是“任务游戏化”。

它最终想形成的是：

- **State Model**：我现在是什么状态
- **Quest System**：我在推进什么
- **Quantification Engine**：我该如何比较、推断、更新判断
- **People Network**：我的人、资源和依赖结构
- **Timeline / Achievements**：我长期以来到底完成了什么
- **Cyrus Voice + Runtime**：一个可以自然交互的 frontstage

如果这些都跑通，用户看到的就不只是一个好看的 Dashboard。

而是一种新的感觉：

> **现实世界第一次像一个可读、可推演、可管理的系统。**
