# S_LEM Design - Jewelry OEM Website

## 概要
S_LEM DesignのジュエリーOEMサービスのランディングページです。

## ライブサイト
🌐 **Live Website**: [https://your-username.github.io/s-lem-design-website](https://your-username.github.io/s-lem-design-website)

## セクション構成
1. **ヘッダー**: ロゴ、ナビゲーション、Instagramリンク
2. **トップページ**: フルスクリーンヘッダー画像、スクロールアイコン
3. **Salemセクション**: 2分割レイアウト（左: sozai.png、右: gazou.png）
4. **Archiveセクション**: 2枚の画像を横スクロール表示
5. **About Usセクション**: OEMサービス紹介、2枚の画像グリッド
6. **Contactセクション**: 問い合わせフォーム
7. **フッター**: 連絡先情報、リンク

## 技術仕様
- **HTML5**: セマンティックマークアップ
- **CSS3**: Flexbox、Grid、レスポンシブデザイン
- **JavaScript**: スムーススクロール、フォーム処理
- **Google Fonts**: Oswaldフォント

## レスポンシブ対応
- **デスクトップ**: 1200px以上
- **タブレット**: 768px-1199px
- **モバイル**: 767px以下

## ローカル開発

### 前提条件
- Python 3.x
- Git

### セットアップ
```bash
# リポジトリをクローン
git clone https://github.com/your-username/s-lem-design-website.git
cd s-lem-design-website

# ローカルサーバーを起動
npm start
# または
python3 -m http.server 8000
```

### アクセス
```
http://localhost:8000
```

## デプロイメント

### GitHub Pages（推奨）
1. GitHubリポジトリにプッシュ
2. Settings > Pages で有効化
3. 自動デプロイ完了

### Netlify
1. ZIPファイルをアップロード
2. 自動デプロイ完了

### Vercel
1. GitHubリポジトリを接続
2. 自動デプロイ完了

## ファイル構成
```
/
├── index.html              # メインページ
├── package.json           # Node.js設定
├── netlify.toml           # Netlify設定
├── privacy-policy.html    # プライバシーポリシー
├── terms-of-service.html  # 利用規約
├── robots.txt             # SEO用
├── sitemap.xml            # SEO用
├── favicon.svg            # ファビコン
├── logo.png               # ヘッダーロゴ
├── header-image.png       # デスクトップヘッダー画像
├── mobile-header.png      # モバイルヘッダー画像
├── sozai.png              # Salemセクション画像
├── gazou.png              # Salemセクション画像
├── scroll-icon.png        # スクロールアイコン
├── instagram-icon.png     # Instagramアイコン
└── archive-images/        # アーカイブ画像
    ├── image1.jpeg
    └── image2.jpeg
```

## 連絡先
- **Email**: salem.jewellers.jp@gmail.com
- **Instagram**: https://www.instagram.com/s_lem_design/
- **住所**: 107 Chiharu Bldg. Jingumae Shibuya-ku Tokyo-to
- **営業時間**: 12:00~20:00

## ライセンス
MIT License

## 更新履歴
- 2025/10/05: GitHub Pages対応、Node.js設定追加
- 2025/10/05: 公開用に最適化、不要ファイル削除
- アーカイブ画像をJPEG形式に統一
- About Usセクションを2×2グリッドレイアウトに修正