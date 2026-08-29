# 生成AIパスポート 勉強ノート

### 📘 https://miyazakiryuji.github.io/genai-passport-notes/

生成AIパスポート試験（一般社団法人 生成AI活用普及協会／GUGA）の自習用ノート。
1ページ完結の HTML で、外部 CDN に依存していない（オフラインでもそのまま開ける）。

## 対象範囲

第7シラバス（2026年2月試験より適用）のうち、次の2か所にしぼっている。

| シラバス | 内容 |
|---|---|
| 第3章 生成AIができることと主なサービス | テキスト／画像／音楽／音声／動画 の5つの生成AI |
| 第2章 ChatGPT | ChatGPT の概要と歴史（GPT-1 〜 GPT-5、Sora・Operator・Codex ほか） |

## 中身

1. 生成AIの5分類（早見表）
2. テキスト生成AI — NLP・LLM・主なサービスと提供元
3. 画像生成AI — GAN／VAE／CNN と拡散モデル、自己回帰型 Transformer
4. 音楽生成AI — MIDI・RNN・リスナーのフィードバック
5. 音声生成AI — 教師あり学習・TTS・Eleven Labs・リップシンク
6. 動画生成AI — GAN/VAE と RNN、Sora・Veo 3
7. 5分類の横断まとめ
8. メリットとデメリット
9. ChatGPTとは — 名前の意味、RLHF・アライメント・ハルシネーション
10. ChatGPTの歴史 — 年表、パラメータ数、GPT-4 の3つの進化、o シリーズ、周辺サービス
11. 数字・年号シート
12. ひっかけ対策（誤りの肢 → 正しくは）
13. 一問一答（クリックで答えを表示・38問）

## 使い方

- **公開ページ**：<https://miyazakiryuji.github.io/genai-passport-notes/>（スマホからはこちら）
- 手元で開くなら `index.html` をブラウザにドロップするだけ。ビルド不要
- 右上の **配色** ボタンで 自動 / 明るい / 暗い を切り替え（選択はブラウザに保存される）
- **印刷 / PDF** ボタンで、一問一答をすべて開いた状態の紙面を出力できる
- 1ページなので `Ctrl`（`⌘`）+ `F` で全体を串刺し検索できる

## 注意

- 試験対策として整理した個人ノートであり、公式の見解ではない
- 出題範囲・受験要項は必ず[公式サイト](https://guga.or.jp/generativeaiexam/)の一次情報で確認すること
- モデルの仕様や提供状況は変化が速いため、年月・数値は**試験教材の記述に合わせて**ある

## 検索避け

- `robots.txt`（サイト全体 Disallow）と `<meta name="robots" content="noindex,...">` の二重で、
  検索エンジンにこのサイトを登録させないようにしている
- ただし効くのは Pages のサイト（<https://miyazakiryuji.github.io/genai-passport-notes/>）まで。
  **GitHub のリポジトリページ（`github.com/...`）は Public なので検索に載りうる**。
  そこまで隠すならリポジトリを private に戻し、Pages 以外のホスティングへ移す必要がある

## 公開の仕組み

`main` ブランチのルートを GitHub Pages が配信している。
**`git push` するだけでサイトに反映される**（ビルドは20秒ほど）。
