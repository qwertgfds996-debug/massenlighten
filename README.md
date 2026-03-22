# Soya 許舒韻 | 第一桶金幸福學

FXVIC 創辦人 Soya 許舒韻的投資教學網頁，分享第一桶金幸福學，陪你邁向點石成金之路。

## 技術棧

- React 19 + TypeScript
- Vite 6
- Tailwind CSS v4
- Motion (動畫)
- Lucide React (圖示)

## 本地開發

**前置條件：** Node.js 18+

```bash
# 安裝依賴
npm install

# 啟動開發伺服器
npm run dev
```

開啟 http://localhost:3000 即可預覽。

## 建置與部署

```bash
# 建置靜態檔案
npm run build

# 預覽建置結果
npm run preview
```

建置產出位於 `dist/` 目錄，可部署至任何靜態託管平台（GitHub Pages、Vercel、Netlify 等）。

## GitHub Pages 自動部署

本專案已設定 GitHub Actions，推送到 `main` 分支時會自動建置並部署到 GitHub Pages。

設定步驟：
1. 前往 GitHub repo → Settings → Pages
2. Source 選擇 **GitHub Actions**
3. 推送程式碼到 `main` 分支即自動部署
