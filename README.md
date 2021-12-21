# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
リモートリポジトリ：ネット上に配置して複数人で共有するためのリポジトリ(個人開発用にも使えます)
ローカルリポジトリ：開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ

## プッシュとマージの違いは何でしょうか？
プッシュはブランチの変更内容リモートブランチに反映させる。
マージは他ブランチの変更内容を他のブランチに反映させる。

## コミットとプッシュの違い
コミットは変更内容をローカルリポジトリのGitに保存していく。プッシュはその変更内容をリモートリポジトリに反映させる。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
一目で変更内容が分かるようにメッセージを残す。また、各チームやプロジェクトでのルールに従って、その決まりに準拠したメッセージにする。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
ローカルでマージするとmasterブランチにその変更履歴を取り込んで変更を反映させる。
プルリクエストはリモートリポジトリ上でマージを行う。
リモートリポジトリとローカルリポジトリは自動で同期はされない。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
先にマージされた変更内容を取り込み、後にマージしようとしている変更内容を取り込む。最後にどちらの変更内容も取り込む。この３通りで変更を取り込む。