# README.md

 デフォルトで、 INTRODUCTION に利用される説明文を書くところ。
 GitHub Flovar Markdown を書くとそれがそのまま表示される。

    # Gitbookの使い方をGitbook で説明する

    [Gitbook](http://www.gitbook.io/) とは

    > Build beautiful programming books and exercises usingGitHub/Git Markdown.

    プログラミングの教本と演習を綺麗にかけるよ。
    GitHub/Git の Markdown でね！( ･`ω･´)

    ## install

    ```
    $ brew install npm
    $ npm install gitbook -g
    ```

    ## build or serve

    ```
    $ gitbook build or gitbook serve
    ```

    Markdown で記述した内容を build または serve できる

    - build で `_build` という Web page のセットが生成される。
    - serve で デフォルトでは localhost で server が起動する
