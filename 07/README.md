# 07 JavaScrpit-工程化

* [07-01](https://github.com/TYRMars/JSLearn/tree/master/07#07-01) `Git常用命令`
* [07-02](https://github.com/TYRMars/JSLearn/tree/master/07#07-02) `上线回滚-上线回滚流程`


## 07-01
### Git常用命令

* `git init`git初始化
* `git add .`文件新增
* `git checkout XXX`出错还原
* `git commit -m "XXX"`commit提交到本地仓库 后面为注释
* `git push origin master` 代码上传
* `git pull origin master` 代码下载

##### 多人开发

* `git branch`看当前分支
* `git checkout -b xxx/git checkout xxx`创建一个分支/切换分支
* `git merge xxx`分支更改的东西提交到master或者分支

## 07-02
### 上线回滚-上线回滚流程

* 上线和回滚的基本流程
* linux基本命令

#### 上线回滚流程

* 重要的开发环节

#### 上线流程要点

* 将测试完的代码提交到git版本库的master分支
* 将当前服务器的代码全部打包并记录版本号，备份
* 将master分支的代码提交覆盖到线上服务器，生成新的版本号

#### 回滚流程要点

* 将当前服务器的代码打包并记录版本号，备份
* 将备份的上一个版本号解压，覆盖到线上服务器，并生成新的版本号

#### Linux基本命令

* 服务器使用Linux居多，server版，只有命令行
* 测试环境要匹配线上环境，因此也是Linux
* 经常需要登陆测试机来自己配置、获取数据
