---
title: tigで"Failed to apply chunk"と言われるときの対処法
date: 2020-04-09 22:50:45
tags:
- git
- tig
- Failed
- index.lock
---

![tig: failed to apply chunk](/images/tig_failed.png)

tig を使っていて突然 `Failed to apply chunk` とか `Failed to update` とか言われるようになってしまいコミットできなくなることがあります。

このときは普通に `git commit` ができなくなっている状況です。私の場合は何らかの原因で `.git/index.lock` が作られてしまってこのエラーに陥っていました。

```sh
$ rm .git/index.lock
```

これで元どおり tig が使えるようになりました。 Good Job!
