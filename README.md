# とある調査員のナゾトキ奇譚 - ファンアート アニメーション HP

ゲーム「都市伝説解体センター」の二次創作ファンアニメの公式ホームページです。

## 📁 プロジェクト構成

```
urban-myth-fanart-hp/
├── index.html              # メインページ（トップページ）
├── atantion.html           # 注意事項ページ
├── about.html              # About Meページ
├── song.html               # Image Songページ
├── animation.html          # Animationページ
├── css/
│   └── style.css          # メインスタイルシート
└── assets/
    └── images/            # 画像ファイル
        ├── logo.png       # タイトルロゴ
        ├── About.avif     # About Meアイコン
        ├── Attention.avif # Atantionアイコン
        ├── anime.avif     # Animationアイコン
        └── song.avif      # Image Songアイコン
```

## 🎨 デザインの特徴

### トップページ（index.html）
- **ヘッダー**: 黒背景に免責事項テキストを全幅表示
- **メインコンテンツ**: 黒背景にタイトルロゴを中央配置
- **フッター**: 黒背景にメニュー（4つのアイコン付きリンク）を全幅表示

### 子ページ（atantion.html, about.html, song.html, animation.html）
- **ヘッダー**: トップページと同じ黒背景の免責事項
- **メインコンテンツ**: 
  - 黄色背景（#FFE600）- SNSの闇をテーマにした演出
  - 右上にロゴ画像を透かし表示（opacity: 0.15）
  - **SNS風投稿カードデザイン**:
    - 白い投稿カードに黒い枠線とシャドウ
    - ユーザーアイコン（絵文字）+ ユーザー名 + タイムスタンプ
    - ホバー時に浮き上がるエフェクト
    - 左からスライドインするアニメーション
    - ミステリー感を演出する配色
- **フッター**: 黒背景にメニューとトップへ戻るボタン

## 🚀 GitHub Pagesへのデプロイ方法

1. GitHubで新しいリポジトリを作成
2. ローカルでプロジェクトを初期化:
   ```bash
   cd urban-myth-fanart-hp
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/あなたのユーザー名/リポジトリ名.git
   git push -u origin main
   ```

3. GitHub Pagesの設定:
   - リポジトリの「Settings」→「Pages」
   - Source: 「Deploy from a branch」
   - Branch: 「main」/「root」を選択
   - 「Save」をクリック

4. 数分後、`https://あなたのユーザー名.github.io/リポジトリ名/`でアクセス可能になります

## 📱 レスポンシブデザイン

以下のブレークポイントで最適化されています:
- **デスクトップ**: 768px以上
- **タブレット**: 768px以下
- **モバイル**: 480px以下

## 🎭 カスタマイズ方法

### コンテンツの編集
各HTMLファイルの`<div class="content-text">`内を編集してください。

### 色の変更
`css/style.css`で以下の色を変更できます:
- 黒背景: `#000000`
- 黄色背景: `#FFE600`
- テキスト色: `#000000` (黄色背景上), `#ffffff` (黒背景上)

### ロゴの透かし調整
`css/style.css`の`.logo-watermark`セクションで調整:
- `opacity`: 透明度（0.15が現在の設定）
- `width`, `height`: サイズ
- `background-position`: 位置

## 📝 注意事項

- このサイトはゲーム「都市伝説解体センター」の二次創作です
- 実在するすべてのものと無関係です
- AI生成楽曲を使用しており、完全無料公開を限定として使用しています

## 🔧 技術スタック

- HTML5
- CSS3（Flexbox、アニメーション）
- レスポンシブデザイン
- 静的サイト（JavaScriptなし）

## 📄 ライセンス

このプロジェクトは二次創作作品であり、原作の著作権は原作者に帰属します。

---

制作: アンブローズ様
最終更新: 2024年11月21日
