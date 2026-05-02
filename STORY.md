# Day065 Story — Warranty Pocket Keeper

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day065専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: warranty_deadline_log
- Mechanic: block_fill
- Input/Output: receipt_items -> return_box
- Audience Promise: あとで探す物と場所を買った日に固定できる。
- Publish Hook: 保管場所と期限と必要書類が一画面で見え、買った直後に置き先が決まる。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day065｜保証書ポケット
保証書ポケットを作るためのツールです。
