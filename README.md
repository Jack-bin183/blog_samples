＃博客样本[！[构建状态]（https://travis-ci.org/kunny/blog_samples.svg?branch=master）]（https://travis-ci.org/kunny/blog_samples）


在博客[Kerney's Android Story]（http://androidhuman.com）上发布的帖子中提供了一个示例。

##如何下载示例项目？
###使用git下载整个存储库

您可以使用`Github`应用程序或在终端中使用以下命令来下载整个存储库。

    $ git clone https://github.com/kunny/blog_samples


###个人项目下载

[Python脚本]（https://raw.githubusercontent.com/kunny/blog_samples/master/Android/get_project.py）允许您仅选择和下载一些项目。使用该脚本必须预先安装的组件如下：

-Python 2.7.5或更高版本

####搜索可下载的项目

运行`python get_project.py`将显示可下载的项目信息以及如何使用脚本。

$ python get_project.py

用法：python get_project.py [projectName ...]
例：
$ python get_project.py HelloWorld //下载一个项目
$ python get_project.py HelloWorld StudioTesting //下载多个项目

可用项目：

名称发布网址
-------------------------------------------------- ---------
HelloWorld无
NavigationDrawerExample_Studio http://androidhuman.com/524
AndroidStudioLibApp http://androidhuman.com/530
StudioTesting http://androidhuman.com/536
SigningWithStudio http://androidhuman.com/544
BasicFragments http://androidhuman.com/546
BasicFragments_withActionItem http://androidhuman.com/547
BasicFragments_PersistState http://androidhuman.com/549

####项目下载

您可以同时下载一个或多个项目。要下载一个项目，请如下输入项目名称作为参数。

    $ python get_project.py HelloWorld

如果要同时下载多个项目，只需在参数中输入项目名称。
以下是下载“ HelloWorld”示例和“ BasicFragments”示例的示例。

    $ python get_project.py HelloWorld BasicFragments
