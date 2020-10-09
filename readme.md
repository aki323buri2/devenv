# devenv

`node.js`と`Python`の環境構築（Windows）

`.zip`フォルダにあるアーカイブを`.vendor`フォルダ内で解凍

`vscode.bat`をダブルクリックで`VsCode`起動


#### `yarn`のインストール
```bash
npm -g i yarn 
```

#### `pip`、`pipenv`のインストール
```bash
python .zip/get-pip.py

pip install pipenv
```
> `get-pip.py`の取得元は[ここ](https://bootstrap.pypa.io/get-pip.py)

#### プロジェクト作成
```bash
mkdir [プロジェクトフォルダ]

code [プロジェクトフォルダ]

```

これで新しい`VsCode`ウィンドウが立ち上がる
```bash
# 新しいVsCodeウィンドウのコンソールで：
npx create-react-app .
# とか
yarn init -y
# とか
```

