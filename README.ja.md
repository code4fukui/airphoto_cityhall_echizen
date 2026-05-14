# airphoto_cityhall_echizen

このプロジェクトは、ドローンを使用して越前市役所の空撮画像を取得するためのツールを提供します。

## 機能
- ドローンの自動飛行経路計画
- 複数のカメラアングルと高度をサポート
- 市役所および周辺地域の高解像度空撮画像を出力

## 要件
- DJI Phantom 4 Pro ドローン
- Python 3.x
- OpenCVライブラリ

## 使用方法
1. 必要なPythonの依存関係をインストールします:
   ```
   pip install -r requirements.txt
   ```
2. `config.py`ファイルで飛行計画のパラメータを設定します。
3. `main.py`スクリプトを実行して、自動撮影ミッションを実行します。

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
