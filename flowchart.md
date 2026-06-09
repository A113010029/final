# 新聞專題 Pipeline 流程圖
## 主題：基隆漢他病毒疫情（2026年5月）

```mermaid
flowchart TD
    A([🦠 主題確立\n基隆漢他病毒疫情]) --> B

    B[步驟 1：選題與素材蒐集\n搜尋基隆漢他病毒相關新聞]
    B --> B1[📰 Taipei Times 2026/05/19\nKeelung reports suspected hantavirus case]
    B --> B2[📰 more-news.tw 2026/05/19\n基隆傳疑似漢他病毒病例]
    B --> B3[📰 more-news.tw 2026/05/20\n謝國樑祭三箭滅鼠]
    B --> B4[📰 more-news.tw 2026/05/22\n基隆全面防鼠防疫]
    B1 & B2 & B3 & B4 --> C

    C[步驟 2：寫新聞草稿\n產出 300–500 字新聞稿]
    C --> C1{AI 起草完成？}
    C1 -- 是 --> C2[✏️ 自己修改潤稿]
    C1 -- 否 --> C

    C2 --> D[步驟 3：事實查核\n驗證至少 1 個 claim]
    D --> D1{查核通過？}
    D1 -- 通過 --> E
    D1 -- 未通過 --> D2[修正內容] --> D

    E[步驟 4：上稿 WordPress\n發布至 cocorico.info]
    E --> E1{發布成功？}
    E1 -- 是 --> F
    E1 -- 否 --> E1b[檢查後台設定] --> E

    F[步驟 5：第二平台發布\nFB 或 X 版本 + 連結]
    F --> G([✅ 完成發布])

    style A fill:#f9c74f,stroke:#f3722c,color:#000
    style G fill:#90be6d,stroke:#43aa8b,color:#000
    style B fill:#4d908e,color:#fff
    style C fill:#4d908e,color:#fff
    style D fill:#4d908e,color:#fff
    style E fill:#4d908e,color:#fff
    style F fill:#4d908e,color:#fff
```

## 工具與負責人對照

| 步驟 | 工具 | 負責人 |
|------|------|--------|
| 1. 選題與素材蒐集 | Kiro | AI + 自己確認 |
| 2. 寫新聞草稿 | Kiro | AI 起草，自己修改 |
| 3. 事實查核 | Google + Kiro | 自己做 |
| 4. 上稿 WordPress | WordPress 後台 | 自己操作 |
| 5. 第二平台發布 | Facebook / X | 自己操作 |
