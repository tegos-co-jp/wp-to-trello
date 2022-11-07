# wp-to-trello

## SVNリポジトリ

https://plugins.svn.wordpress.org/wp-to-trello


## 公式
https://developer.wordpress.org/plugins/wordpress-org/how-to-use-subversion/#overview


### 通常の開発・リリース

```ｓｖｎ:通常の開発・リリース
svn update assets/*
svn update trunk/*
svn commit -m "コミットメッセージ（任意）"
svn cp trunk tags/1.0.2
svn ci -m "tag version 1.0.2"
```

### ｓｖｎ:動作テストのみでリリースしたい場合 
* tagsの最新バージョンに移動
```ｓｖｎ:動作テストのみでリリースしたい場合
svn update readme.txt
svn commit -m "コミットメッセージ（任意）"
```
