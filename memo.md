## はじめにすること

1. `git branch`で現在のブランチを確認
2. `git status`で変更がないか確認
3. `git pull origin master`で最新に
4. 履歴を残したくない場合は`git pull --rebase origin master`で最新に

> git config --global pull.rebase true
> git config branch.master.rebase true

## GitHub とのやり取り

- git remote

リモートリポジトリを確認

- git remote -v

リモートリポジトリの URL を確認

- git remote show <リモート名>

リモートリポジトリを詳しく

- git remote rename <旧リモート名> <新リモート名>
