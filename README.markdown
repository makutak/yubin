# Yubin

郵便番号から住所を取得するCommon Lisp CLIツール

Yubin（郵便）は、日本の郵便番号から住所を取得するためのCommon Lisp CLIツールです。zipcloud.ibsnet.co.jp APIを使用して、郵便番号を入力として住所を検索します。

## インストール

### Roswellを使用

```bash
ros install makutak/yubin
```
## 使用方法

```bash
yubin 1050001
# 東京都港区虎ノ門
```
## 依存関係

- `dexador` - HTTP クライアント
- `jonathan` - JSON パーサー
- `quri` - URI 操作（実装で使用）
