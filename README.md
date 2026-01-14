# Tntran - TNT Runミニゲーム

> ⚠️ **α版（アルファ版）** - このプラグインは現在開発中です。バグが存在する可能性があります。

TNT Runスタイルのミニゲームプラグインです。

## 概要

足場を走ると踏んだブロックが消えていく！落ちたら脱落、最後まで生き残った人が勝利！

## ⚠️ α版について

- 機能が不完全な場合があります
- バグが存在する可能性があります
- 問題を発見した場合は [Discord](https://discord.gg/zYY55dzhjd) でご報告ください

## ダウンロード

[Releases](https://github.com/henntekosennsi1-rgb/Tntran/releases)

## 主な機能

- 踏むとブロックが消える
- 複数層のカラフルなウールプラットフォーム
- 最大6人対応
- 自動マップ生成
- ロビーシステム
- 看板での参加/退出

## ゲームルール

- プラットフォームを走り回る
- 踏んだブロックは約1秒後に消滅
- 落下したら脱落
- 最後まで生き残れば勝利！

## コマンド

| コマンド | 説明 |
|---------|------|
| `/tntran join` | 参加 |
| `/tntran leave` | 退出 |
| `/tntran start` | ゲーム開始 |
| `/tntran stop` | ゲーム停止 |
| `/tntran setup spawn` | 退出スポーン設定 |
| `/tntran setup lobby` | ロビー設定 |
| `/tntran setup area pos1/pos2` | エリア設定 |
| `/tntran reload` | 設定再読み込み |

## 設定
```yaml
decay-delay-ticks: 20  # ブロック消滅遅延（20 = 1秒）
max-players: 6         # 最大人数
```

## 動作環境

- Spigot/Paper 1.21.x
- Java 17以上

## コミュニティ

**Discord:** https://discord.gg/zYY55dzhjd

## ライセンス

All Rights Reserved
