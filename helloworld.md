---
title: 'Hello World!'
author: fdxx
keywords: 'keywords1, keywords2'
description: 'This is a markdown example website.'
---

# Hello World

# 一级标题
## 二级标题
### 三级标题
#### 四级标题

## 段落
**Markdown**是一种轻量级标记语言，排版语法简洁，让人们更多地关注内容本身而非排版。它使用易读易写的纯文本格式编写文档，可与HTML混编，可导出 HTML、PDF 以及本身的 .md 格式的文件。因简洁、高效、易读、易写，`Markdown`被大量使用，如[Github](https://github.com/)、Wikipedia、简书等。

## 强调

**加粗**
*斜体*
<u>下划线</u>
~~删除线~~
[超链接](https://github.com)

## 引用
> Markdown是一种轻量级标记语言，排版语法简洁，让人们更多地关注内容本身而非排版。它使用易读易写的纯文本格式编写文档，可与HTML混编，可导出 HTML、PDF 以及本身的 .md 格式的文件。因简洁、高效、易读、易写，Markdown被大量使用，如Github、Wikipedia、简书等。

## 列表

### 有序列表
1. 有序列表有序列表有序列表
2. 有序列表有序列表有序列表有序列表
3. 有序列表有序列表有序列表有序列表
  
### 无序列表
- 无序列表无序列表无序列表
- 无序列表无序列表无序列表
- 无序列表无序列表无序列表无序列表

### 任务列表
- [ ] 任务列表
- [ ] 任务列表任务列表
- [x] 任务列表任务列表

## 表格
| 标题 | 标题 | 标题 |
| :---: | :---: | :---: |
| 内容 | 内容 |  内容 |
| 内容 | 内容 |  内容 |

## 代码块

```c++
#include <iostream>

int main(int argc, char *argv[]) {

  /* An annoying "Hello World" example */
  for (auto i = 0; i < 0xFFFF; i++)
    cout << "Hello, World!" << endl;

  char c = '\n';
  unordered_map <string, vector<string> > m;
  m["key"] = "\\\\"; // this is an error

  return -2e3 + 12l;
}
```

```go
package main

import "fmt"

func main() {
    ch := make(chan float64)
    ch <- 1.0e10    // magic number
    x, ok := <- ch
    defer fmt.Println(`exitting now\`)
    go println(len("hello world!"))
    return
}
```

```bash
#!/bin/bash

###### CONFIG
ACCEPTED_HOSTS="/root/.hag_accepted.conf"
BE_VERBOSE=false

if [ "$UID" -ne 0 ]
then
 echo "Superuser rights required"
 exit 2
fi

genApacheConf(){
 echo -e "# Host ${HOME_DIR}$1/$2 :"
}

echo '"quoted"' | tr -d \" > text.txt
```

```json
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```


## 折叠快
<details>
<summary>点击展开</summary>
隐藏文字隐藏文字隐藏文字。隐藏文字隐藏文字隐藏文字。隐藏文字隐藏文字隐藏文字。隐藏文字隐藏文字隐藏文字。隐藏文字隐藏文字隐藏文字。
</details>

## 表情
😂🤣😡📱🇨🇳😍

## 警报
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

## 图片
![github](https://myoctocat.com/assets/images/base-octocat.svg)
