# 孔子·華佗傳統美德故事 (SEN Hub)

多圖少字、互動嘅粵語 TTS 學習 App，畀 SEN（有特殊教育需要）學生透過孔子同華佗嘅故事學習傳統美德（仁愛、禮貌、醫德、助人、學習、健身）。

## 功能

- 📖 **8 則美德故事** — 孔子 (仁·禮·學) + 華佗 (醫德·助人) 配大字 + 粵語 TTS
- 📜 **人物詳解** — 孔子與華佗美德概覽
- ✍️ **拼美德句** — 8 句循環互動練習
- 📚 **24 個圖像詞彙** — 點擊聽粵語讀音
- 📝 **6 題小評估** — 簡單/中級程度，含即時語音回饋
- 🏆 **金銀銅證書** — 完成評估後可打印
- ⭐ **徽章系統** — 6 個徽章 3 種分類（每日 / 階梯 / 永久）

## 技術

- 純 Single-File Web App (`index.html`)，冇 framework、冇 build step
- 原生 Web Speech API (`zh-HK` / 粵語 TTS)
- GitHub Pages auto-deploy (`.github/workflows/pages.yml`)
- 適合平板/手機（`touch-action: manipulation`，大按鈕 ≥70px）

## 本地跑

直接開 `index.html` 喺瀏覽器就得。

```bash
open index.html
# 或
python3 -m http.server 8000  # 然後瀏覽 http://localhost:8000
```

## 部署

推上 `main` branch 即觸發 GitHub Pages deploy（GitHub repo Settings → Pages → 揀 `GitHub Actions`）。

## 瀏覽器支援

- Safari 14+ ✅ (iPad / iPhone 粵語 TTS 最佳)
- Chrome 90+ ✅
- Firefox 88+ ✅ (TTS 表現因系統而異)

## License

MIT
