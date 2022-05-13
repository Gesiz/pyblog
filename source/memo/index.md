---
title: 备忘
date: 2022-05-02 23:39:18
tags: 备忘
categories: 
- [备忘]
---

这里将会记录一些经常用到但偶尔会忘记的事情
<!--more-->

## 常用的 hexo 指令

```bash
$ hexo new page --path=xxx/xxx/xxx "xxx"
$ hexo g
$ hexo s
```

## 常用的 tmux 指令

```bash
$ tmux new -s <session-name>
$ tmux attach -t <session-name>
$ tmux list-session
$ tmux kill-session -t <session-name>
$ tmux switch -t <session-name>
$ tmux rename-session -t <session-name> <new-name>
```

快捷键

```bash
Ctrl+b d：分离当前会话。
Ctrl+b s：列出所有会话。
Ctrl+b $：重命名当前会话。
```

## CPU & IO

```
iostat -x
top
```

