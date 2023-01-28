
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=sngxpro)](https://github.com/anuraghazra/github-readme-stats)


Run

^_^

### AutoSyncScript项目介绍
```
此项目用于定时拉取github上各作者的脚本备份。

使用github action的用户，请善用本项目拉取原作者的脚本到自己这里，

然后引用自己仓库的脚本地址运行ac，

不要给原作者添麻烦！
```

## 使用说明
```
1、直接fork本项目到你自己的仓库。

2、点击自己的github设置--settings（右上角头像小三角点开下拉菜单就看到了）

3、点击developer setings

4、点击Personal access tokens

5、点击generate new token

6、note随便起个好记的名字，给“repo”和“workflow”打勾

7、拉倒页面最下，点generate token

8、复制得到的token

9、回到fork得到的仓库，点仓库名字下面一行按钮中的“settings”

10、点击secrets---再点击new repository secrets

11、上面填写 PAT 三个字母

12、下面粘贴复制得到的token

13、保存即可

14、点击仓库名字下面一行按钮中的action

15、点击右上角的star，添加一颗星星

16、手动运行一次这个页面的各个sync项目。方法是点击一个项目，然后点击run workflow。

17、回到fork到的仓库的首页，编辑README.md文件，删掉开头的^_^，再保存一次。

18、完事了

19、自动同步我的Autosync项目的方法：


在github安装pull，会自动帮你检测上游仓库，并帮助你更新代码

地址在这: https://github.com/apps/pull

配置后，fork走的仓库也会跟着我的更新而更新代码，然后再自动拉取新增的仓库，属于无限套娃

```

看不懂的可参考一下下面文章。

1、本项目图文教程

https://mp.weixin.qq.com/s/gOA8PSwLfhp9bLLnBkJf-Q

2、拉取项目原理举例

https://mp.weixin.qq.com/s/fcI4vQHD8TNajvTML9g3AA
