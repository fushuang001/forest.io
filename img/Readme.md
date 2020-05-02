图床，目前主要用来做 typora 笔记上传 image 的工具。

不是很信任`iPic` 微博匿名上传，怕有一天微博把 image 清理了；GitHub 相对还容易保存一些，至于访问速度什么的，VPN 用户无感。


[参考设置-1](https://developpaper.com/typora-picgo-github-to-realize-the-effect-of-mds-own-drawing-bed/)

[Note] 由于 MBP 推荐使用picgo -core，并不是 picgo，所以设置上有点问题

`GitHub 要使用 public 的仓库。若使用 private 仓库，是可以上传，但是 image link 里面有一个临时 token，10 分钟左右 token 就会失效，无法再访问。`

[参考设置-2](https://zhuanlan.zhihu.com/p/114175770)

[Note] 上一个 link 出现的问题，就是 port 从 33667 直接变成 336671，有问题；看这个帖子，是要先 **退出** picgo，让 typora 自己打开即可。image 上传之后，picgo 会自己退出；不要操作太频繁，比如在 picgo 自动退出之前，再次 upload 新的 image，仍然会导致port 33667 - 336671 的问题。

[参考设置-3](https://support.typora.io/Upload-Image/#upload-all-local-images)

官方


---

`/Applications/PicGo.app/Contents/MacOS/PicGo upload`

![MBP](https://github.com/fushuang001/Workday-Focus/blob/master/images/typora-picgo.png)
