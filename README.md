

> 中文版图解Git教程, 不介意英文的直接看[原版](https://www.atlassian.com/git)

> 如果觉得不错，请[点击Star一下](https://github.com/MTimer/Git-Sucks)

>  还没完成

图解Git
=======

译者注：
 1. 不完全按照原版翻译，其他借鉴的Git教程有[Pro Git book](http://git-scm.com/book/zh/), [Git Community Book 中文版](http://gitbook.liuhui998.com/index.html), [Git for everyone](http://anotheruiguy.gitbooks.io/gitforeveryone/), [Git教程](http://www.liaoxuefeng.com/), 这些教程建议读完『图解Git后』再看，能省些时间。
 2. 为何选择此英文原版？ 原著的英文单词浅显易懂，也是必须要掌握的，全程配以图示和案例以及介绍如何从SVN迁移到Git，绝对是Git入门绝佳教程。也因此本中文教程不翻译关键英文单词，保持原汁原味。
 3. 你将遇到的英文单词[解释](intro/git-trans.md)。
 4. 为什么叫 Git Sucks? Git很棒，可是需要花时间去学，Sucks!
 5. 遇到麻烦？简版救急[点此](sos/README.md)，『图解Git』完整版 [在线阅读](http://MTimer.github.io/Git-Sucks)，顺便做了英文版 [Make the Switch to Git](http://MTimer.github.io/Make-the-Switch-to-Git)。

![从SVN转到Git](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/pageSections/0/contentColumnTwo/0/imageBinary/git_home.png)


* [Git 介绍](intro/README.md)
   * [2.0新功能](intro/git-2.0.md)
   * [安装](intro/git-install.md)
   * [英文解释](intro/git-trans.md)
* [Git 基础教程](tutorial/README.md)
   * [Git 基本命令⇩](tutorial/git-basics/README.md)
     * [git init](tutorial/git-basics/git-init.md)
     * [git clone](tutorial/git-basics/git-clone.md)
     * [git config](tutorial/git-basics/git-config.md)
     * [git add](tutorial/git-basics/git-add.md)
     * [git commit](tutorial/git-basics/git-commit.md)
     * [git status](tutorial/git-basics/git-status.md)
     * [git log](tutorial/git-basics/git-log.md)
   * [Git 撤销更改⇩](tutorial/undoing-changes/README.md)
     * [git checkout](tutorial/undoing-changes/git-checkout.md)
     * [git revert](tutorial/undoing-changes/git-revert.md)
     * [git reset](tutorial/undoing-changes/git-reset.md)
     * [git clean](tutorial/undoing-changes/git-clean.md)
   * [Git 分支⇩](tutorial/git-branches/README.md)
     * [git branch](tutorial/git-branches/git-branch.md)
     * [git checkout](tutorial/git-branches/git-checkout.md)
     * [git merge](tutorial/git-branches/git-merge.md)
   * [Git 重写历史⇩](tutorial/rewriting-git-history/README.md)
     * [git commit --amend](tutorial/rewriting-git-history/git-commit-amend.md)
     * [git rebase](tutorial/rewriting-git-history/git-rebase.md)
     * [git rebase -i](tutorial/rewriting-git-history/git-rebase-i.md)
     * [git reflog](tutorial/rewriting-git-history/git-reflog.md)
   * [Git 远程仓库⇩](tutorial/remote-repositories/README.md)
     * [git remote](tutorial/remote-repositories/git-remote.md)
     * [git fetch](tutorial/remote-repositories/git-fetch.md)
     * [git pull](tutorial/remote-repositories/git-pull.md)
     * [git push](tutorial/remote-repositories/git-push.md)
* [Git 工作流](workflows/README.md)
   * [Centralized Workflow](workflows/workflow-centralized.md)
   * [Feature Branch Workflow](workflows/workflow-feature-branch.md)
   * [Gitflow Workflow](workflows/workflow-gitflow.md)
   * [Forking Workflow](workflows/workflow-forking.md)
   * [Pull Requests](workflows/pull-request.md)
* [迁移到 Git](migration/README.md)
   * [准备](migration/migration-prepare.md)
   * [转换](migration/migration-convert.md)
   * [同步](migration/migration-synchronize.md)
   * [共享](migration/migration-share.md)
   * [迁移](migration/migration-migrate.md)
* [Git 进阶教程](resources/README.md)
* [Git 救急](sos/README.md)


Git 基础教程
* 主要面向有SVN使用经验的Git新手，此基础教程详尽介绍了重要的Git命令，足以应付日常工作。
基础教程包括Git相关命令介绍，以及命令的详细阐述和实例。

[了解更多](tutorial/README.md)

Git 工作流 (注：文中称 Git Workflows)

* 介绍常见的Git工作流，提供图解和相应的实例。不管你是要管理centralized workflow还是尝试其他新流程，此教程都可以帮到你。
* 搞清楚在你当前工作流程下如何使用Git。
* 理解常见的Git工作流如何帮到你的团队。
* 通过特定场景和实例学习进步。

[了解更多](workflows/README.md)
