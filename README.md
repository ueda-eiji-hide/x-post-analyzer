# X Post Analyzer

A lightweight, browser-only analytics dashboard for X (Twitter) content creators — analyze post performance, content types, and posting patterns from your own data.

🇯🇵 X（旧Twitter）の投稿データ（CSV）をアップロードするだけで、インプレッション・ブックマーク・エンゲージメント率などを自動分析できる軽量ダッシュボードです。どんなジャンルのアカウントでも使えます。

## What it does / できること

- 📊 Upload X analytics CSV exports and visualize impressions, bookmarks, and engagement trends
- 🏷️ Tag posts by content type (review / concept / know-how / activity / quote / other) and compare performance by type
- 📅 See weekday-based posting performance breakdown
- 📈 Track impression and bookmark trends over time
- 🔍 Sortable post table with detailed modal view per post

## Why I built this / 作った理由

I run an X account and wanted a simple way to understand which post types and timing actually perform — without relying on paid analytics tools.

Xアカウントを運用する中で、「どの投稿タイプが伸びるか」「曜日でどう変わるか」を手元で素早く把握したくて作りました。有料の分析ツールを使わず、CSVをアップロードするだけで完結します。

## How to use / 使い方

1. Open `index.html` in any modern browser (no installation needed)
2. Export your post analytics as CSV from X's analytics dashboard
3. Upload the CSV in the app
4. Browse the Overview / Posts / Types / Trends tabs

特別なインストールは不要です。HTMLファイルをブラウザで開き、X analyticsからエクスポートしたCSVをアップロードするだけで使えます。

## Tech stack

- Vanilla JavaScript, HTML, CSS (no build step, no dependencies)
- Runs entirely client-side — no data is sent anywhere

## License

MIT

## Roadmap / 今後の予定

- [ ] Support for multiple CSV format auto-detection improvements
- [ ] Export analysis results as image/PDF
- [ ] Multi-account comparison view
