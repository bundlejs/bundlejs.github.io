---
title: 开篇
date: 2020-08-06
cover: https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1596686823844&di=00ff84c9e49c759c7bf6f94c30da3443&imgtype=0&src=http%3A%2F%2Fa2.att.hudong.com%2F86%2F10%2F01300000184180121920108394217.jpg
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` javascript
selectType (item) {
    this.showTypeActionSheet = false
        if (this.type !== item.name) {
            this.type = item.name
            this.currentPage = 0
            this.reportList = []
            this.loading = true
            this.finished = false
            if (this.loading) {
                this.getReportList()
            }
        }
    localStorage.setItem('myReportType', item.name)
},
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` css
#document {
  height: 100vh;
  display: flex;
  flex-direction: column;
  background: #202020;
  font-family: microsoft yahei, wenquanyi micro hei, sans-serif !important;
}

nav,
footer {
  background: #494949;
  display: flex;
  justify-content: center;
}

main {
  color: #bdbdbd;
  flex: auto;
}

footer {
  flex-shrink: 0;
}

* {
  margin: 0;
}

h1,
p {
  padding: 15px;
}

nav > h1 {
  color: #82fcfd;
  text-shadow: 1px 1px 4px #00000080;
}

footer > h1 {
  color: #82fcfd;
  text-shadow: 1px 1px 4px #00000080;
}
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
