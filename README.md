# えいこを投げ飛ばしました

ハンマー投げの要領で「えいこ」を投げ飛ばし、日本から世界のどこまで届くかを競うiPhone向けHTMLゲーム。

- 遊ぶファイル：`web/index.html`（単一HTML・オフライン動作）
- ソース：`web/src/game.html`、素材：`web/assets/`
- ビルド：`python3 web/build.py`（素材をBase64で埋め込み `web/index.html` を生成）

素材
- 地球：NASA Blue Marble（パブリックドメイン）
- 街の背景・人物：AI生成画像（グリーンバックから切り抜き）
- 回転アクション：Geminiで生成したグリーンバック動画から1周分を48方向のコマに切り出し（web/assets/spin）
- 曲：ユーザー提供の動画から音声のみを抽出
