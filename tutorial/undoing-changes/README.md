Undoing Git Changes
===================

此章节讲解如何处理项目旧的版本内容。首先，先介绍如何浏览旧的commits，然后解释reverting已发布的项目历史中的commits和resetting本地未发布的更改之间的区别。
![Undoing Git Changes](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/undoing-changes/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial_undoing-changes.png)

#### 浏览旧的 Commits
git checkout

命令git checkout是一个多用途的命令，在这个教程中将会被多次提及。在此章节中，我们将利用它来查看项目之前的版本内容。
[了解更多](git-checkout.md)
![git checkout](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/undoing-changes/pageSections/00/contentFullWidth/0/tabs/0/pageSections/0/contentColumnTwo/0/imageBinary/git-training-undoing-changes.png)

#### 撤销公开的更改(译注: 公开就是已经committed的意思)
git revert

命令git revert撤销一个committed snapshot。当你发现一个错误的commit，reverting是最保险和方便的方法来完全去除它。
[了解更多](git-revert.md)
![git revert](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/undoing-changes/pageSections/00/contentFullWidth/0/tabs/0/pageSections/00/contentColumnTwo/0/imageBinary/git-tutorial_changes-revert.png)

#### 撤销本地的更改
git reset

命令git reset撤销工作目录对文件的更改。Resetting可以帮你清除尚未发布到公共仓库的更改内容。
[了解更多](git-reset.md)
![git reset](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/undoing-changes/pageSections/00/contentFullWidth/0/tabs/0/pageSections/01/contentColumnTwo/0/imageBinary/git-tutorial-changes-reset.png)

#### git clean
命令git clean用以从工作目录中删除untracked文件。逻辑上有点像git reset，但git reset只用于操作tracked文件。
[了解更多](git-clean.md)
![git clean](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/undoing-changes/pageSections/00/contentFullWidth/0/tabs/0/pageSections/02/contentColumnTwo/0/imageBinary/git-tutorial-changes-clean.png)
