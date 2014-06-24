Git 远程仓库
============

SVN使用一个central仓库作为开发者的交流hub，共同开发是通过传递开发者工作目录和central仓库不同的文件集来实现的。这和Git的共同协作模式不同。Git给每个开发者属于他们自己的仓库副本，拥有自己的本地历史和分支结构。通过一系列commits而不是一个文件集来分享。Git可以在不同仓库间分享完整的分支。下面的命令用于管理与其他分支的联系，通过“pushing”分支到其他仓库爱发布本地历史，通过“pulling”分支到本地仓库来查看其他人的贡献。
![Git 远程仓库](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/remote-repositories/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial-remote-repos.png)

### git remote
命令git remote可以很方便的管理远程连接。除了可以使用完整地址来fetch，pull，和push命令，也可以使用更简洁的快捷键。
[了解更多](git-remote.md)
![git remote](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/remote-repositories/pageSections/00/contentFullWidth/0/tabs/0/pageSections/0/contentColumnTwo/0/imageBinary/git-tutorial-remote.png)

### git fetch
Fetching从其他仓库下载一个分支，包含它的commits和文件。但是，它不会整合进你的本地仓库。这样就允许你在整合进项目前先分析分支更改的内容。
[了解更多](git-fetch.md)
![git fetch](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/remote-repositories/pageSections/00/contentFullWidth/0/tabs/0/pageSections/00/contentColumnTwo/0/imageBinary/git-tutorial-remote-repositories-fetch.png)

### git pull
git pull是git fetch的自动版。它从远端仓库下载一个分支，然后立即合并到当前分支。相当于SVN中的update。
[了解更多](git-pull.md)
![git pull](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/remote-repositories/pageSections/00/contentFullWidth/0/tabs/0/pageSections/01/contentColumnTwo/0/imageBinary/git-tutorial-remote-repositories-pull.png)

### git push
push和fetch相反(除一些注意事项)。它可以移动一个本地的分支到另一个仓库。可以很方便地发布贡献。和SVN的commit相似，但是它发送的是一系列的commits而不是一个更改的文件集。
[了解更多](git-push.md)
![git push](https://gp1.wac.edgecastcdn.net/8029C4/wac-small/wac/landing/git/tutorial/remote-repositories/pageSections/00/contentFullWidth/0/tabs/0/pageSections/02/contentColumnTwo/0/imageBinary/git-tutorial-remote-repositories-push.png)
