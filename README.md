hexo + netlyfi でブログ

- ソースコード管理: https://github.com/chypot/blog_netlify
- ビルド・デプロイ・ホスティング: https://app.netlify.com/teams/chypot/sites
- 公開先: https://chypot.netlify.com/

## 環境設定

```console
sudo npm install hexo-cli -g
```

```console
git clone https://github.com/chypot/blog_netlify.git
cd blog_netlify/
git config user.name "CONTINUUM, Hypot"
git config user.email "chypot@smoug.net"
```

## 記事を新規投稿する

### 記事をすぐ書いて公開するとき

```console
hexo new post <記事タイトル>
```

### とりあえず下書き

```console
hexo new post <記事タイトル>
```

### ドラフトを公開する

```console
hexo publish <記事タイトル>
```

### 手元で確認

```console
hexo server
```

### Deploy

```console
git commit .
git push origin master
```

## スポンサー情報

TODO