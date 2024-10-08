

  <h3 align="center">A Zoom Clone</h3>


## <a name="tech-stack">⚙️ Tech Stack</a>

- Next.js
- TypeScript
- Clerk
- getstream
- shadcn
- Tailwind CSS

## <a name="features">🔋 Features</a>


**身份驗證**：使用 Clerk 實現身份驗證和授權功能，允許用戶通過社交登入或傳統的電子郵件和密碼方式安全登錄，同時確保平台內部適當的訪問級別和權限。

👉 新會議：快速啟動新會議，並在加入之前配置相機和麥克風設置。

👉 會議控制：參與者對會議各方面擁有完全控制權，包括錄音、表情符號反應、螢幕共享、靜音/解除靜音、音量調整、網格佈局、參與者列表查看和個別參與者管理（固定、靜音、解除靜音、阻止、允許視頻共享）。

👉 退出會議：參與者可以離開會議，或者創建者可以結束所有與會者的會議。

👉 安排未來會議：輸入會議詳細資訊（日期、時間）以安排未來的會議，並在「即將舉行的會議」頁面上訪問，方便分享連結或立即開始。

👉 過去會議列表：訪問之前舉行的會議列表，包括詳細資訊和元數據。

👉 查看錄製會議：訪問過去會議的錄音以進行回顧或參考。

👉 個人房間：用戶擁有一個個人房間，並擁有唯一的會議連結，用於即時會議，可與他人分享。

👉 通過連結加入會議：輕鬆通過提供連結加入他人創建的會議。

👉 響應式設計：遵循響應式設計原則，以確保在各種設備上提供最佳用戶體驗，自動適應不同的螢幕尺寸和解析度。


**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=
STREAM_SECRET_KEY=
```


**Running the Project**

```bash
npm run dev
```


