# Task 1: Write a GitHub intro

_这一部分的目标是让你在 GitHub 上创建一个新仓库（repository）并写一个自我介绍文件_

## 步骤如下：
1. 登录 github.com
2. 进入 GitHub 网站，用你的账号登录或注册。
3. 创建一个新仓库
4. 名字要和你的用户名相同（例如如果用户名是 zimingyu，仓库名也叫 zimingyu）。
5. 创建一个文件叫 README.md
_这是一个 Markdown 文件（.md 结尾），在里面写一个简短的自我介绍_

## 内容至少要包括：
1. 一个标题（header，用 # 开头）
2. 两个段落文字
3. 一个列表（如 bullet points）
4. 一个超链接 (例如链接到你的 LinkedIn、GitHub 页面或喜欢的网站)
   
_提示：你可以在 GitHub 上点击 “Code” 或 “Preview” 标签查看写的 Markdown 效果_

点击 “Commit Changes” 提交, 也就是保存你刚写的内容
写一个有意义的 commit message（提交说明）
_例如：add first draft of github introduction_

回到你的 GitHub 主页
你会看到刚刚提交的 README 文件，GitHub 会自动显示它作为欢迎页面

_本人链接:_
https://www.notion.so/26f1fde0e12480eea41de3caf658fa9d?v=26f1fde0e12481f08031000cda3215c5


# Task 2: Introduce and fix a typo (Git Remote Workflow)

_这一部分让你练习修改文件和再次提交更新_

回到你刚写的 README.md 文件，故意在标题或链接里加一个拼写错误（typo）
提交（commit）这次修改，并写个说明，比如 update title and links
再次编辑文件，把拼写错误修正
再提交一次，说明写成 fix typo in title
## 这样你就学会了：
1. 如何创建文件
2. 如何修改并提交更新
3. 如何写清楚的 commit message（版本说明）


# Task 3: Fixing someone else’s mistakes

_“A fork is a copy of a repository.”_
意思是：Fork（派生） 一个仓库，就是复制别人的项目到你自己的 GitHub 账户中
这样你可以自由修改，不会影响原始项目

## 步骤说明：
1. 与同学配对
找一个同学（或三人一组），互相配合完成以下练习。
2. 互相分享仓库地址
每个人先完成自己的 README.md 自我介绍（来自前面的 Task 1 & 2），然后：
打开你的 GitHub 页面（例如：https://github.com/zimingyu/zimingyu）
复制仓库网址，发给你的搭档
3. Fork 对方的仓库
进入你搭档的 GitHub 页面
点击右上角的 “Fork” 按钮
GitHub 会自动把你搭档的仓库复制到你自己的账户中（例如：https://github.com/zimingyu/partnername）
4. 修改他们的 README.md 文件
在你自己的 fork（副本）中打开 README.md 文件
找到那个拼写错误的超链接文字（typo）
编辑文件，修正这个错误。
点击 “Commit Changes”，并写一条有意义的提交信息，例如：
Fix hyperlink text
5. 创建 Pull Request（PR）
_这是 GitHub 协作的关键步骤：_
回到你 fork 的仓库首页。
点击 “Contribute” → “Open Pull Request”
编辑标题和描述：
标题（title）写得更具体，比如：Fix typo in hyperlink of README
描述（description）写上为什么需要修改。
例如：“Fixed hyperlink text to correctly display my LinkedIn link.”
点击 “Create Pull Request”。

_解释一下 “Pull Request”_
名字有点奇怪，但意思是：
“我已经在我的副本里修改好了，能不能请你把这些改动拉（pull）到你的原始项目里？”

6. 你的搭档来审查（review）PR
你的搭档会收到通知，看到你发的 Pull Request
他们可以：
Merge（合并）：接受你的修改；
Edit（编辑）：在合并前再做些改动；
Close（拒绝）：如果不想采纳你的修改。

## 关键概念总结
概念	含义
Commit（提交）	每次保存修改，相当于一个“存档点”
Commit message（提交信息）	简短说明本次修改做了什么、为什么做
Diff（差异）	展示自上次提交以来，代码中发生的具体改动（新增、删除等）
Pull Request（拉取请求）	一个请求，要求原作者将你的改动合并进原项目

### 举个具体例子
假设你和同学 Alice 配对：
你 fork 了她的仓库 alice/alice → 复制成 zimingyu/alice
你修正了她 README.md 里的拼写错误
你提交（commit）写上 “Fix typo in hyperlink”
然后你创建了一个 Pull Request，标题写：
Fix typo in hyperlink of README
描述成：
Corrected the hyperlink text for LinkedIn profile.
Alice 收到通知后，看到你的 PR，可以选择 Merge.

