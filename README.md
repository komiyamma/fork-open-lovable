# Open Lovable

AIとチャットして、Reactアプリを即座に構築します。[Firecrawl](https://firecrawl.dev/?ref=open-lovable-github)チームによって作成されました。

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExbmZtaHFleGRsMTNlaWNydGdianI4NGQ4dHhyZjB0d2VkcjRyeXBucCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ZFVLWMa6dVskQX0qu1/giphy.gif" alt="Open Lovable Demo" width="100%"/>

## セットアップ

1. **クローンとインストール**
```bash
git clone https://github.com/mendableai/open-lovable.git
cd open-lovable
npm install
```

2. **`.env.local`の追加**
```env
# 必須
E2B_API_KEY=your_e2b_api_key  # https://e2b.dev から取得 (サンドボックス)
FIRECRAWL_API_KEY=your_firecrawl_api_key  # https://firecrawl.dev から取得 (ウェブスクレイピング)

# オプション (少なくとも1つのAIプロバイダーが必要)
ANTHROPIC_API_KEY=your_anthropic_api_key  # https://console.anthropic.com から取得
OPENAI_API_KEY=your_openai_api_key  # https://platform.openai.com から取得 (GPT-5)
GEMINI_API_KEY=your_gemini_api_key  # https://aistudio.google.com/app/apikey から取得
GROQ_API_KEY=your_groq_api_key  # https://console.groq.com から取得 (高速推論 - Kimi K2推奨)
```

3. **実行**
```bash
npm run dev
```

[http://localhost:3000](http://localhost:3000) を開きます。

## ライセンス

MIT
