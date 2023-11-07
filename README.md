# strii-infra
本リポジトリstrii-infraはstriiプロジェクトのベースリポジトリであり、本リポジトリではdockerを使ったinfraを扱い、別のgithubリポジトリとして、フロントエンドをstrii-frontend、バックエンドをstrii-backendという別のリポジトリで管理し、infra,frontend,backendの3つのリポジトリで構成される。

striiプロジェクトを第三者がローカルで確認したい場合はstrii-infraリポジトリをローカルにpullした後、下記手順でstrii-frontend, strii-backendをsrcディレクトリ下にgit pullして確認すること。

Some basic Git commands are:
```
git status
git add
git commit
```
