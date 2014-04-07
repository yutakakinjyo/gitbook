# SUMMARY.md

- 目次と構成を定義できる
- リストの Markdown で表現する
- リンク先を記述しないことでpending状態を表す
- 階層は二段階目まで有効
- それ以上深くすると目次に現れなくなる
- pending が現れると gitbook 表示の際にnextボタンである矢印が途切れる
- ので、順序良くpendingを解除しないといけない
- 目次の項目では英語が大文字になってしまう!＞＜

```
# Summary

Gitbook の概要

- [ファイル構成](chapter1/Structure.md)
  - [README.md](chapter1/README.md)
  - [SAMMARY](chapter1/SUMMARY.md)
  - [pending]()
    - [見えない](chapter1/SUMMARY.md)
```
