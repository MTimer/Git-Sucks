Git 基本命令
============

Git基本命令章节介绍了最重要的Git命令。首先，*新建一个仓库* 小节阐述了你要新建一个版本控制项目所需的工具。然后，剩余部分介绍了日常必备的Git命令。

读完此章节，你应当可以新建一个Git仓库，记录你项目的snapshots用以保存，并且浏览项目历史。
![Git基本命令](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial_basics.png)

概述
----

#### 新建一个仓库
git init

命令git init生成一个新的Git仓库，如果你想要将一个项目用于版本控制，这是你第一个需要学习的命令。
[了解更多](git-init.md)
![git init](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial-basics-init.png)

#### git 克隆
git clone

命令git clone生成一个现有的Git仓库副本。克隆命令是开发者们从central仓库获取一个工作副本最常用的命令。
[了解更多](git-clone.md)
![git clone](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/00/contentColumnTwo/0/imageBinary/git-tutorial-basics-clone.png)

#### git 设置
git config

命令git config命令可以方便的设置Git环境。你通常需要在开发机上安装完Git后立即执行此命令。
[了解更多](git-config.md)
![git config](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/01/contentColumnTwo/0/imageBinary/git-tutorial-basics-config.png)

#### 记录 Snapshots
git add

命令git add将更改从工作目录添加到staging area。这样你就在执行commit到正式的历史之前准备了一个snapshot。
[了解更多](git-add.md)
![git add](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/02/contentColumnTwo/0/imageBinary/git-tutorial-basics-add.png)

#### git 贡献
git commit

命令git commit将staged snapshot贡献到项目历史中。此命令和git add构成了所有Git用户的基本工作流。
[了解更多](git-commit.md)
![git commit](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/03/contentColumnTwo/0/imageBinary/git-tutorial-basics-commit.png)

#### 检查 Git 仓库
git status

命令git status显示了工作目录和staged snapshot状态。你可以将此命令和git add，git commit配合使用来查看到底下次snapshot将会包括哪些文件。
[了解更多](git-status.md)
![git status](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/05/contentColumnTwo/0/imageBinary/git-tutorial-basics-status.png)

#### git 记录
git log

命令git log供你查看项目之前的版本内容。它提供多种格式显示committed snapshots。
[了解更多](git-log.md)
![git log](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/git-basics/pageSections/00/contentFullWidth/0/tabs/0/pageSections/06/contentColumnTwo/0/imageBinary/git-tutorial-basics-log.png)
