项目使用说明
===============================

目前在GitHub找不到vendor核心模块的仓库了,之前还可以,直接fork核心模块的仓库,每次只需要简单的执行指令
```
git pull
```
就可以保持框架代码是最新的,也不需要人为修改框架源码。当然,在几家公司工作后,看到的都是前辈们把核心框架修改的面目全非,带来的直接后果,也是最致命的伤害是,框架再也无法进行升级了。

项目结构
-------------------
切换到工作目录后,首先checkout最外层目录zoulu
```
git clone https://github.com/zhgxun/zoulu.git
```
然后进入到该目录中
```
cd zoulu
```
依次checkout如下目录,没有顺序依赖

backend
```
git clone https://github.com/zhgxun/backend.git
```

common
```
git clone https://github.com/zhgxun/common.git
```

frontend
```
git clone https://github.com/zhgxun/frontend.git
```

console
```
git clone https://github.com/zhgxun/console.git
```

代码提交时,只能提交对应的目录,即是每次进入对应的目录后执行:
```
git pull;git add --all;git commit -m 'fix issue';git push;
```

回到最外层目录zoulu中,需要在执行一次提交
```
git pull;git add --all;git commit -m 'fix issue';git push;
```