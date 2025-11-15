# mbtrain-ipynb

## 訓練データの用意

```sh
mkdir train_data/00_illust
mkdir train_data/01_not_illust
```

- 1ディレクトリ1クラスになる
- 2クラス分類の場合, 1クラスあたり最低250枚程度の画像があれば十分な精度がでる

## 実行

```sh
uv run jupyter lab
```

## うごかなくなったときは

```sh
rm -rf .venv
uv sync
```
