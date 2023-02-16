## 請實作一個 Android app 滿足以下需求:
1. 程式碼使用 Java or Kotlin 撰寫。
2. 包含一個文字輸入框,偵測到輸入文字改變時,將文字內容帶到 GitHub API 查詢 GitHub repositories,並在畫面上展示搜尋結果。
3. 包含以下 UI 狀態:
    - 空狀態:輸入框為空時,提示使用者輸入內容。
    - 載入狀態:呼叫 API 等待回應時。
    - 錯誤狀態:API 回應錯誤時(例如達到 rate limit)。
4. 點擊其中的 repo ,可以跳轉至詳細資訊頁面。
## 加分項目
1. 使用最新的 MDC-Android 套件,UI 符合 Material Design Guidelines。
2. 使用 Android Jetpack。
3. 使用 Kotlin Coroutines。
4. 撰寫測試。
5. 任何上述需求裡沒有提到的額外功能或創意。
## 評分重點
1. 正確性
2. 效能
3. 程式架構與品質
## 提交方式
1. 請將原始碼壓縮成 ZIP 檔提交,亦或是提供 Github Repo。
2. 也一併附上可供安裝的 APK。
## 推薦的開發環境 / 開發工具
> 僅作開發時參考,可自行評估是否使用
  - Target sdk version: 33; Min sdk version: 23
  - Http framework: Retrofit, OkHttp
  - Image Loader: Glide , Coil
  - DI: Koin
  - Json Serializer: kotlinx.serialization, Gson
  - Unit Test: Kotest, Mockk
