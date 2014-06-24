Git 重写历史
============

Git一个重要的任务是确保你从不丢失committed的更改。但是，它同时赋予你开发工作的完全控制权。其中就包括完全控制项目历史内容。但这也可能导致丢失commits的潜在可能。Git提供重写历史的命令但也提醒使用这些命令可能导致丢失内容。

此章节讨论了覆盖committed snapshots的方法以及如何避险失误。
![Git 重写历史](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/rewriting-git-history/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial_rewriting-history.png)

### git commit --amend
--amend告诉git commit修改最近的commit。这个命令用在当你忘了stage一个文件或者commit message遗漏了一些重要信息等情况。
[了解更多](git-commit.md)
![git commit --amend](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/rewriting-git-history/pageSections/00/contentFullWidth/0/tabs/0/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial-commit-amend.png)

### git rebase
Rebasing可以移动分支，用于避免不需要的merge commits。形成的线性历史通常更容易阅读和浏览。
[了解更多](git-rebase.md)
![git rebase](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/rewriting-git-history/pageSections/00/contentFullWidth/0/tabs/0/pageSections/00/contentColumnTwo/0/imageBinary/git-tutorial_history-rebase.png)

### git rebase -i
-i用于开始一个互动的rebasing session。除了普通的rebase优点，你可以在这个过程中新增，编辑或者删除commits。
[了解更多](git-rebase-i.md)
![git rebase -i](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/rewriting-git-history/pageSections/00/contentFullWidth/0/tabs/0/pageSections/01/contentColumnTwo/0/imageBinary/git-tutorial_history-rebase-i.png)

### git reflog
Git使用reflog机制追踪分支的更新。这允许你回到任意变更之前即使没有任何分支或者标签索引。
[了解更多](git-reflog.md)
