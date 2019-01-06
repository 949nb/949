# hello,github.

> im a new coder.

```
sha ye bu hui de na zhong!
```

- so,i will work hard!
- good good xuexi  day day up! 233333....

1. 在git上添加项目需要创建一个仓库
2. 生成地址
3. 在终端中 ` git clone ` 这个地址
4. 可以在终端用命令行修改仓库中的内容
 1. ` git add . ` 将这个文件夹下的东西保存到暂存区（` git status`查看暂存区）
 2. ` git commit -am "xxx" ` 添加到本地库（` -a ` 也可以添加到本地库，不过需要进入vim编辑器编辑备注 ` -am "xxx" ` 就可以直接在xxx中添加备注)
 3. ` git push origin master ` 推送到git远程库
  1. ` origin ` 是一个 **git地址标签** 可以用 ` git remote set-url xxx git@github.com:xxx/xxx.git `来更改标签
  2. ` master ` 是一个**分支**，` git branch -a ` 可以查看当前所有分支。 ` git branch xxx ` 可以创建xxx分支。` git merge ` 可以合并分支

- 遇到了一个问题！用同一个本地仓库来建立两个远程仓库。

 > 本来天真以为 `git remote add xxx <地址>` 加一个标签直接push上去就可以。

 其实不然，在本地仓库添加标签后，另一个远程仓库（coding）的主分支pull不下来，导致push失败。
 - **解决办法**：直接在本地仓库新建分支，将分支push到新的远程仓库～就可以了
 - 遗留问题（以后解决）：1. 如果想pull 另一个远程仓库主分支下的东西怎么办？
                         2. 合并分支的话到底是什么样的一个逻辑？现在学会的只是简单的使用，以后要了解需要深入git原理了解～
 - 以后有时间看看[深入浅出git](https://blog.coding.net/blog/git-from-the-inside-out)
 - 继续推进课程
