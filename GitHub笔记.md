
##仓库github基本概念##
**1.仓库(Respository) ：**仓库用来存放项目代码，每个项目对应一个仓库，多个项目对应对个仓库。

**2.收藏(Star) ：**收藏项目，方便下次查看。

**3.复制克隆项目(Fork) ：**分叉—你开源了一个项目，别人想在你这个项目基础上做些改进，然后应用到自己的项目中，这时他就可以fork你的项目（打开项目主页点击右上角fork按钮即可），然后主页上就多了一个项目（基于你的项目），可以任意进行操作了。

**4. 发起请求(Pull Request) ：**基于Fork,别人Fork你的项目代码之后，在此基础上做了修改，觉得不错的话，可以Pull Request(简称 PR),原有项目创建人，也就是你，接收到请求之后，可以review他的代码，经测试觉得不错的话，可以接受他的PR,这样他做的改进项目中就会有了。

**5.关注(Watch) ：**关注项目，当关注的项目更新后能及时得到通知！

**6.事务卡片(Issue) ：**
发现代码BUG,目前没有成型代码，需要讨论时用。解决后可以Close掉。

**7.GitHub的官方网址 ：**[https://github.com/](https://github.com/)

**8.Git客户端的下载地址 ：**[https://www.git-scm.com/](https://www.git-scm.com/)

**9.Git和SVN的区别 :**
Git是分布式版本控制系统，SVN是集中式版本控制系统

**Git工作流程 :**

- 在工作目录中修改某些文件
- 对修改后的文件进行快照，然后保存到暂存区域
- 提交更新，将保存在暂存区域的文件快照永久转储到Git目录中


**10.Git工作区域 ：**

- 工作区(Working Directory) :添加、编辑、修改文件等动作。
- 暂存区 ：暂存已经修改的文件最后统一提交到git仓库中。
- Git Repository(Git 本地仓库) ：最终确定的文件保存到仓库，成为一个新的版本，并且对他人可见。

**11.GIT合并的两种方法以及区别 :**
Git代码合并有两种：Git Merge 和 Git ReBase

Git Merge：这种合并方式是将两个分支的历史合并到一起，现在的分支不会被更改，它会比对双方不同的文件缓存下来，生成一个commit，去push。

Git ReBase：这种合并方法通常被称为“衍合”。他是提交修改历史，比对双方的commit，然后找出不同的去缓存，然后去push，修改commit历史。

**12.查看文件的提交历史和分支的提交历史**

使用git log查看文件提交历史 :
Git log filename

使用git log查看分支提交历史 :
Git log branch file


**13.git提交代码时候写错commit信息后，重新设置commit信息 :**

通过Git commit --amend 来对本次commit进行修改

**14.Git常用命令 ：**

- git status(查看当前的工作区)
- git add XXX.zip(将文件提交到暂存区)
- git commit -m"提交描述"（将文件提交到git仓库）
- git config --global user.name '326036498'(设置用户名)
- git config --global user.name '326036498@qq.com'(设置用户名邮箱)
- git init(初始化仓库,会生成一个.git的文件)
- rm XXX.zip(删除本地文件)
- git rm XXX.zip(从git中删除文件)
- git commit -m"提交描述"(提交删除操作)
- git add (将文件添加至暂存区)
- git diff(查看仓库与上次修改的内容)
- git clone(克隆代码)
- git bransh(查看当前分支)
- git checkout(切换当前分支)