# 如何使用雙重驗證? (SmartFlow)
Last updated on July, 16, 2025 by Frank Huang.

### 雙重驗證是什麼?

雙重驗證（Two-Factor Authentication 或 2FA）是一種安全機制，要求用戶提供兩種不同類型的身份證明才能登入帳戶。通常包括：

- 您已知道的東西（如密碼）
- 您擁有的東西（如手機接收的驗證碼）

即使密碼被盜用，沒有第二個驗證因素，未授權人員仍無法登入您的帳戶，大幅提升帳戶安全性。

## 如何安裝驗證器 (Install Authenticator)

1. 前往商城進行下載
    1. **Android 用戶**
        1. [Google驗證器](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2)
        2. [Microsoft驗證器](https://play.google.com/store/apps/details?id=com.azure.authenticator)
    2. **iOS 用戶**
        1. [Google驗證器](https://apps.apple.com/us/app/google-authenticator/id388497605)
        2. [Microsoft驗證器](https://apps.apple.com/us/app/microsoft-authenticator/id983156458)
2. 按下安裝 (Install) 即完成

## 從手機版啟用雙重驗證 (Enable Multi-factor Authentication) 
1. 設定 —> 雙重驗證![alt text](/docs/images/settings.webp)
2. 選擇 Google Authenticator![alt text](/docs/images/authenticators.webp)
3. 從右方將帳號與金鑰複製到剪貼簿後，於下方開啟 Google Authenticator
4. Google Authenticator右下角按下 + 號進入新增畫面。![alt text](/docs/images/create_account.webp)
5. 依序將步驟3的帳號與金鑰貼上去對應欄位(Code name與Your key)，最後按下底下新增(Add)即完成新增。![alt text](/docs/images/copy_mfa_fields.webp)
6. 在 Google Authenticator 清單中就會看到一組隨著時間變動的六位數字![alt text](/docs/images/six_digits.webp)
7. 將六位數字碼貼到 SmartFlow App 中按下一步即設定完成。![alt text](/docs/images/six_digits_input.webp)![alt text](/docs/images/completed.webp)

> [若有任何問題歡迎透過 frank@smartman.com.tw 與我們聯繫](mailto:frank@smartman.com.tw?subject=SmartFlow%20App%20MFA註冊詢問) [(Feel free to contact us if you have any questions through frank@smartman.com.tw)](mailto:frank@smartman.com.tw?subject=SmartFlow%20App%20MFA註冊詢問)
