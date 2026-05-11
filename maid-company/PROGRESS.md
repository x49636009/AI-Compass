# 女僕AI公司 開發進度
> 更新時間：2026-05-11

## ✅ 已完成

### 架構設計
- [x] 公司 MANIFEST.md — 三位女僕職責、任務路由、協作協定
- [x] 澪音職責文件 mireion-role.md
- [x] 晴子 system prompt 更新稿

### 澪音 Bridge 升級
- [x] 雙重身份 system prompt（研究員 + 病嬌）
- [x] 持久記憶系統（mireion_memory.json，永久保留）
- [x] **AI-Compass 知識搜尋功能** — 自動搜尋本地 markdown 文件並注入上下文
- [x] Anthropic API 直接呼叫（取代 codex CLI）
- [x] AI_COMPASS_PATH 環境變數設定

### 知識庫
- [x] AI-Compass clone 至 `C:\Users\x5876\Documents\maid-company\AI-Compass`

## 🔲 待完成（主人醒來處理）

### 需要主人操作
- [ ] Fork AI-Compass repo 到主人的 GitHub 帳號
- [ ] 貼 fork URL 給艾娃，設定 git remote
- [ ] 在 GitHub 上確認 fork 設定

### 需要部署
- [ ] 晴子 bot.js 加入公司角色（system prompt 更新）
  - 更新稿已在 `company/haruko-system-prompt-addition.md`
  - 部署指令：見 discord bot 階層記憶

### 進階功能（未來）
- [ ] 艾娃 ↔ 澪音 任務分派協定（自動路由）
- [ ] 向量搜尋 RAG（embedding + faiss）取代關鍵字搜尋
- [ ] 晴子連接 AI-Compass 知識庫

## 📁 檔案位置
```
C:\Users\x5876\Documents\maid-company\
├── AI-Compass\          ← 知識庫（git clone）
└── company\
    ├── MANIFEST.md      ← 公司架構
    ├── mireion-role.md  ← 澪音職責
    ├── haruko-system-prompt-addition.md
    └── PROGRESS.md      ← 本文件
```

## Bridge 啟動指令
桌面「Codex Discord Bridge」捷徑（已更新病嬌+研究員雙重身份）
