# How to write mkdocs

For full documentation visit [mkdocs.org](https://mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## 警告文

!!! Note
    これはノートです。

??? Tip
    ヒントです。

!!! Warning
    これは警告です

??? Danger
    これは危険です。

!!! Success
    これは成功です。

??? Failure
    これは失敗です。

!!! Bug
    これはバグです。

??? summary
    これは概要です。

## FontAwesome
:fa-external-link: [MkDocs](http://www.mkdocs.org/)

## 定義
定義語
:    ここに説明を書きます

## KeyBoardのわかりやすい書き方
++ctrl+alt+delete++

## Code Block
```
package main

import "fmt"

func main() {
  fmt.Println("Hello World")
}

```

## Magic Link
<https://google.com>

## Mark
==mark me==
==smart==mark==

## TaskList
Task List

- [X] item 1
    * [X] item A
    * [ ] item B
        more text
        + [x] item a
        + [ ] item b
        + [x] item c
    * [X] item C
- [ ] item 2
- [ ] item 3
