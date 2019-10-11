[![](https://img.shields.io/badge/docker-19.03.1-blue)](https://getbootstrap.com/docs/4.1/getting-started/introduction/)
[![](https://img.shields.io/badge/python-3.7-orange.svg)](https://www.python.org/downloads/release/python-370/)
[![](https://img.shields.io/badge/django-2.2-green.svg)](https://docs.djangoproject.com/en/2.1/releases/2.1/)
[![](https://img.shields.io/badge/license-MIT-000000.svg)](https://opensource.org/licenses/MIT)

**这是教你手把手部署 Docker + Django + Mysql + Ngnix + Gunicorn 的傻瓜式教程**，目的是让 Docker 菜鸟也能快速部署容器化的 Django 应用。

教程传送门：

- [GitHub版](https://github.com/stacklens/django-docker-tutorial)
- [个人博客版](https://www.dusaiphoto.com/article/detail/73)

> 注：两个版本是完全相同的。需要留言请前往个人博客。

**教程导航：**

- 前言
- Docker + Django 本地部署
- Docker + Django + Mysql 本地部署
- Docker + Django + Mysql + Ngnix + Gunicorn 本地 + 云端部署

![](https://www.dusaiphoto.com/media/image/image_source/20190928/reduce_docker_small.jpg)

## 教程特色

- 零基础、免费、中文、完整项目代码
- 基于最新的 Docker 19.03.1、Python 3.7、Django 2.1
- 博主热情的技术支持

## 教程适宜人群

- 完全没接触过 Docker，但却想迅速搭建容器化项目的
- 接触过 Docker，但是却不清楚如何用 Docker 搭建 Django 项目的

## 代码使用方法

在 Linux/Mac 系统中预先安装好 Docker、Docker-compose。

下载示例代码：

```shel
$ git clone https://github.com/stacklens/django-docker-tutorial.git
```

进入代码根目录：

```shell
$ cd django-docker-tutorial
```

然后运行容器：

```shell
$ docker-compose up
```

基于 Django + Docker + MySQL + Nginx + Gunicorn 的容器化项目就运行起来了。

你可以用浏览器访问地址 `127.0.0.1:8000` ，即可看到 Django 首页（小火箭起飞页面）。

Enjoy！

> 第一次启动容器时有可能会失败，原因是 db 容器未完全初始化造成的。遇到这种情况请尝试重启容器，问题就消失了。

## 资源列表

如果你对如何将 Django 项目部署到云端完全不了解的，强烈建议先看看**传统部署流程**，建立大致印象：

- [将 Django 项目部署到服务器](https://www.dusaiphoto.com/article/detail/71/)

如果你想重新学习 Django 开发的，可以先看博主的 Django 教程：

- [Django 搭建个人博客教程](https://www.dusaiphoto.com/article/detail/2/)

此外，本文撰写时主要参考了以下资料：

- [django-mysql-with-docker](http://www.nisanthsojan.com/django-mysql-with-docker -a-step-by-step-guide-for-local-development-part-1/)
- [Docker Documention](https://docs.docker.com/)

------

- 有疑问请在[杜赛的个人网站](http://www.dusaiphoto.com)留言，我会尽快回复。
- 或Email私信我：dusaiphoto@foxmail.com

![](https://www.dusaiphoto.com/media/image/image_source/20190930/QR.jpg)