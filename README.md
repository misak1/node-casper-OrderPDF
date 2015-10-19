### brewのインストール
```
# ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### phantomjsのインストール
```
# brew install phantomjs
# phantomjs -v
1.9.8
```

### casperjsのインストール
```
# brew install casperjs --devel
# casperjs --version
1.1.0-beta3
```

### 実行方法
```
# git clone <このリポジトリURL>
# npm install

backgroundでサーバーを立ち上げる
# npm start

backgroundでサーバーを立ち上がっている状態で
# casperjs main.js <対象のURL>
例) casperjs main.js http://yahoo.co.jp
```

ブラウザアクセス  
http://localhost:8877/writetest2.html

デモ画像
![デモ画像](screenshots/demo.png?raw=true "デモ画像")

### メモ
- screenshots/yyyymmdd-hhmmss のディレクトリにスクリーンショットが作成される。
- htdocsでpdfにする元のhtmlを配置しブラウザからアクセスする。
- 最終成果物はPDF
