# Cartridge

Function as a Service

---

## このリポジトリを使ってGitHubに草を生やす手順

1. このリポジトリを持ってくる (`git clone ~`)
2. Issueを立てる
3. ブランチを切る (`git checkout -b [issue number]-explain_the_branch`)
4. コードを書く :memo:
5. git add & commit
6. 完成まで4,5を繰り返す
7. 最新の`master`ブランチを適用する
  - `git checkout master`
  - `git pull`
  - `git checkout [your branch]`
  - `git merge master`
8. **6.** でコンフリクトしたら修正
9. Push & Pull Request! :tada:

