# MkDocs

[MkDocs](https://www.mkdocs.org/)可以快速的把markdown文件构建成静态网站

## 快速开始

以centos7系统为例，快速展示一些MkDocs的用法

#### 安装pip
```bash
$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
$ python get-pip.py
$ pip --version
pip 18.1 from /usr/lib/python2.7/site-packages/pip (python 2.7)
```
#### 安装MkDocs
```bash
$ pip install mkdocs
$ mkdocs --version
mkdocs, version 1.0.4 from /usr/lib/python2.7/site-packages/mkdocs (Python 2.7)
```
#### 创建文档项目
```bash
$ mkdocs new my-project
$ cd my-project
$ tree
.
├── docs
│   └── index.md
└── mkdocs.yml

1 directory, 2 files
```
#### 启动服务
```bash
$ mkdocs serve
$ mkdocs serve --dev-addr 0.0.0.0:8080
INFO    -  Building documentation... 
INFO    -  Cleaning site directory 
[I 181106 19:47:51 server:292] Serving on http://0.0.0.0:8080
[I 181106 19:47:51 handlers:59] Start watching changes
[I 181106 19:47:51 handlers:61] Start detecting changes
```
