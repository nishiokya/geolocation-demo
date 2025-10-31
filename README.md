# 🌍 Geolocation API Demo

ブラウザのGeolocation APIを使用した、位置情報取得のチュートリアルデモです。

## 📚 チュートリアル

このリポジトリには5つのチュートリアルが含まれています：

### 1. 位置情報の取得 (getCurrentPosition)
**ファイル:** `getlocation.html`

現在の位置情報を一度だけ取得する基本的な使い方を学べます。

**特徴:**
- `navigator.geolocation.getCurrentPosition()` の使用方法
- `position.toJSON()` メソッドでシンプルにデータを取得
- エラーハンドリングの実装
- 実行可能なサンプルコード付き

**[デモを見る](./getlocation.html)**

---

### 2. 位置情報の監視 (watchPosition)
**ファイル:** `watchlocation.html`

位置情報の変化をリアルタイムで監視する方法を学べます。

**特徴:**
- `navigator.geolocation.watchPosition()` の使用方法
- `navigator.geolocation.clearWatch()` で監視を停止
- リアルタイムで位置情報を更新
- 更新回数とタイムスタンプの表示
- 実行可能なサンプルコード付き

**[デモを見る](./watchlocation.html)**

---

### 3. エラーハンドリング (GeolocationPositionError)
**ファイル:** `error-handling.html`

Geolocation APIのエラー処理について詳しく学べます。

**特徴:**
- `GeolocationPositionError` の詳細解説
- 3種類のエラーコード（PERMISSION_DENIED, POSITION_UNAVAILABLE, TIMEOUT）
- 各エラーの原因と対処法
- エラーケースのシミュレーション機能
- 実践的なエラーハンドリングのサンプルコード

**[デモを見る](./error-handling.html)**

---

### 4. キャッシュ制御 (maximumAge)
**ファイル:** `cache-control.html`

`maximumAge`オプションを使用したキャッシュ制御について学べます。

**特徴:**
- `maximumAge`オプションの詳細解説
- キャッシュの動作パターン比較表
- パフォーマンス最適化とバッテリー消費削減
- インタラクティブなキャッシュ動作デモ
- 新規取得とキャッシュ使用の統計表示
- 実践的な使用例のサンプルコード

**[デモを見る](./cache-control.html)**

---

### 5. タイムアウト制御 (timeout)
**ファイル:** `timeout-control.html`

`timeout`オプションを使用したタイムアウト制御について学べます。

**特徴:**
- `timeout`オプションの詳細解説とベストプラクティス
- タイムアウト値による動作比較表
- リトライ処理の実装方法
- プログレスバー付きのインタラクティブデモ
- 成功率と平均取得時間の統計表示
- 実践的なエラーハンドリングとリトライロジック

**[デモを見る](./timeout-control.html)**

---

## 🚀 使い方

1. このリポジトリをクローン
```bash
git clone https://github.com/nishiokya/geolocation-demo.git
cd geolocation-demo
```

2. ブラウザでHTMLファイルを開く
```bash
# macOS
open getlocation.html
# または
open watchlocation.html
# または
open error-handling.html
# または
open cache-control.html
# または
open timeout-control.html
```

3. 位置情報の使用許可を求められたら「許可」をクリック

## 📖 学べること

- Geolocation APIの基本的な使い方
- `getCurrentPosition()` と `watchPosition()` の違い
- `toJSON()` メソッドの活用
- エラーハンドリングの実装方法（GeolocationPositionError）
- 3種類のエラーコード（PERMISSION_DENIED, POSITION_UNAVAILABLE, TIMEOUT）の理解
- `maximumAge`を使用したキャッシュ制御とパフォーマンス最適化
- `timeout`を使用したタイムアウト制御とリトライ処理
- 位置情報のオプション設定（高精度モード、タイムアウトなど）

## 🔒 プライバシーについて

- 位置情報はブラウザ上でのみ処理され、外部に送信されません
- 各チュートリアルの実行には、ユーザーの明示的な許可が必要です
- HTTPS環境での実行が推奨されます

## 📝 ライセンス

MIT License

