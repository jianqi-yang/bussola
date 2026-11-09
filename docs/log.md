# Bussola Project Log / 项目日志

## Week 1 / 第 1 周（2026-11-09 – 11-15, started early on 11-05）

### English

**Goals:** Set up the development environment; create the GitHub repository and write the README; learn basic Git (commit, push, branch, pull request); write three small Python programs as a self-test

**Done:**
- Installed WSL 2 + Debian 13 on Windows 11, and set up Python 3.13, Git and VS Code
- Created a GitHub account with two-factor authentication; Git uses the GitHub no-reply email
- Generated an SSH key (ed25519, protected by a passphrase) and added it to GitHub
- Created the public repository bussola, wrote the README, and made and pushed two commits
- Learned git clone, status, add, commit, push and log; started learning branches

**Still to do this week:**
- Python self-test: read and write a text file, analyze a CSV file, call a public API

**Problems and solutions:**
- Confused the SSH passphrase, the GitHub password and the Debian password → compared them side by side: the passphrase unlocks the SSH private key
- Did not understand what "the privacy email works" means → saw the email recorded in each commit with git config user.email and git log
- Could not understand the English output in the terminal → asked Claude to translate it line by line

**What I learned:**
- Git records the history of changes in a folder; files must be added to the staging area before a commit
- SSH proves identity with a key pair: the public key goes to GitHub, the private key never leaves my computer
- A branch lets me make changes without affecting main; when the changes are ready, they are merged through a pull request

**Next week:**
- Talk to at least 10 students about their experience with paperwork in Italy and collect 30 real questions (including: which step of the residence permit application was the hardest)
- List the official sources and start building questions.csv

**Time spent:** 4 hours

### 中文

**本周目标：** 搭好开发环境；建 GitHub 仓库并写 README；学会 Git 基本操作（commit、push、branch、pull request）；用 Python 写三个小程序自测

**完成了：**
- 在 Windows 11 上装好 WSL 2 + Debian 13，配好 Python 3.13、Git 和 VS Code
- 注册 GitHub，开启双重验证，Git 使用 GitHub 隐私邮箱
- 生成 SSH 钥匙（ed25519，设了 passphrase）并添加到 GitHub
- 新建公开仓库 bussola，写好 README，完成两次提交并推送
- 学会 git clone、status、add、commit、push、log，开始学分支

**本周还要做：**
- Python 自测三个小程序：读写文本文件、统计 CSV、调用公开 API

**遇到的问题和解决办法：**
- 分不清 passphrase、GitHub 密码和 Debian 密码 → 列表对比后理清了：passphrase 是用来解锁 SSH 私钥的
- 不明白"隐私邮箱生效"是什么意思 → 用 git config user.email 和 git log 亲眼看到了提交里记录的邮箱
- 终端里的英文输出看不懂 → 请 Claude 逐行翻译

**学到的东西：**
- Git 记录的是文件夹的修改历史；commit 之前要先 add 到暂存区
- SSH 用一对钥匙证明身份：公钥交给 GitHub，私钥只留在自己电脑里
- 分支可以在不影响 main 的情况下修改，改好后通过 pull request 合并

**下周计划：**
- 找至少 10 位同学聊聊办手续的经历，收集 30 个真实问题（顺便问：办居留时最卡在哪一步）
- 整理官方来源清单，开始做 questions.csv

**投入时间：** 4 小时