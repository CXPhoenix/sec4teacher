# 1_資訊安全_CIA
```
1.資訊安全
2.資訊安全目標:機密性、完整性與可用性CIA
3.破壞CIA的情境
4.保護CIA的方法:概述
5.其他資訊安全相關概念[若授課時間不足,可略過 或是當作作業]
```

# 1.資訊安全(Information security)
```
https://en.wikipedia.org/wiki/Information_security

https://zh.wikipedia.org/wiki/資訊安全
保護資訊及資訊系統 免受 未經授權的 進入、使用、披露、破壞、修改、檢視、記錄及銷毀。
```
# 2.資訊安全目標:機密性、完整性與可用性CIA
```
The CIA triad :
機密性(Confidentiality)
完整性(Integrity)
可用性(Availability)
```
```
機密性（Confidentiality） ==> 確保資料傳遞與儲存的隱密性，避免未經授權的使用者有意或無意的揭露資料內容。

資料完整性（Integrity） ==> 代表確保資料無論是在傳輸或儲存的生命週期中，保有其正確性與一致性。

在資訊安全領域，可用性（Availability）是成功的資訊安全計畫應具備的需求，意及當使用者需透過資訊系統進行操作時，
資料與服務須保持可用狀況(能用)，並能滿足使用需求(夠用)。
```
```
[隨堂小測驗]下列何者是「機密性」的正確意涵？
(A) 確保被使用的為正確資料，未遭人竄改   (B) 確保網路通訊中的參與者，不會拒絕承認他們的行為
(C) 確保資訊服務隨時可被取用            (D) 防止未經授權的人或系統存取資料或訊息
```
```
[隨堂小測驗]下列何項說明內容是關於「可用性」的敘述？
(A) 使用者以專用帳號及密碼登入ERP系統   (B) 電信商機房故障，暫時無法使用網路
(C) 親自遞送機密文件給總經理核閱        (D) 出勤系統異常，導致薪資計算錯誤
```
# 3.破壞CIA的情境
```
[隨堂小測驗]某日新聞陳述有學生侵入學校的伺服器，偷偷竄改自己的期末考成績。
請問這是破壞了資訊的哪一項特性？
(A) 保密性（Confidentiality） (B) 完整性（Integrity）
(C) 可用性（Availability）(D) 責任性（Accountability）
```

```
[隨堂小測驗]國外新聞報導某組織對外服務之官方網站遭受駭客透過DDoS攻擊，
請問此為下列哪項遭受破壞？
(A) 機密性  (B) 完整性  (C) 可用性  (D) 可讀性
```

```
[隨堂小測驗]國外新聞報導某組織內部某資料庫遭受駭客藉由惡意程式入侵，竊走大量個人資料，
請問此為下列哪些特性遭受破壞？
(A) 可用性  (B) 機密性   (C) 完整性  (D) 可讀性
```

# 4.保護CIA的方法:概述
```
保護資訊C.I.A.不同的技術與方法

機密性保護技術
– 加解密技術
– 存取控制(Access control)

完整性保護技術
– 使用雜湊函數(Hash)
– 數位簽章
– 存取控制(Access control)

可用性保護技術
– 容量規劃(Volume planning) 
– 善用各種備份
– 容錯、備援及負載平衡 ==> 瞬間登入人數過多導致電腦當機
– 存取控制(Access control)
```
```
[隨堂小測驗]開發資訊系統時須建立資訊系統資料備份機制，此技術與下列何者關聯性最高?
(A) 可歸責性    (B) 可用性   (C) 完整性   (D) 機密性
```
```
[隨堂小測驗]開發資訊系統時須建立資訊系統資料備份機制，為確保公司備份資料之完整性，
下列何者方式最佳？ (A) 加解密 (B) 身分驗證 (C) 雜湊計算 
```

```
存取控制(Access control)
https://en.wikipedia.org/wiki/Access_control
```
# 5.其他資訊安全相關概念 [若授課時間不足,可略過 或是當作作業]
## 3A(AAA) 
```
3A == AAA == Authentication, Authorization and Accounting.
https://en.wikipedia.org/wiki/AAA_(computer_security)

認證(Authentication)
授權(Authorization)
紀錄(Accounting) 
```
### 認證(Authentication)
```
識別資訊使用者的身分，可記錄資訊被誰所存取使用，例如：透過密碼或憑證方式驗證使用者身分。

實務做法：
你所知道的（Something you know）：帳號／密碼
你所擁有的（Something you have）：IC卡、數位裝置、數位簽章、一次性密碼(OTP)
你所具備的（Something you are）：指紋、虹膜、聲紋、臉部特徵、靜脈脈紋、DNA
```
```
https://en.wikipedia.org/wiki/Authentication

1.身分驗證（Authentication）又稱「認證」、「鑒權」，是指通過一定的手段，完成對使用者身分的確認。

2.認證因子 == Authentication factors == factors of authentication

[1]the knowledge factors: Something the user knows 
   (e.g., a password, partial password, pass phrase, personal identification number (PIN), 
   challenge response (the user must answer a question or pattern), security question).

[2]the ownership factors: Something the user has 
    (e.g., wrist band, ID card, security token, implanted device, 
    cell phone with built-in hardware token, software token, or cell phone holding a software token).

[3]the inference factors: Something the user is or does 
   (e.g., fingerprint指紋, retinal pattern, DNA sequence 
   (there are assorted definitions of what is sufficient), 
   signature, face, voice, unique bio-electric signals, or other biometric identifier).

3. 認證類型:
Single-factor authentication(單因子認證)
Multi-factor authentication(多因子認證)
```

### 授權(Authorization)
```
依照實際需求給予實體適當的權限
一般建議採最小權限（Least privilege）== 僅給予實際作業所需要的權限，避免過度授權可能造成的資訊暴露或洩漏。

資訊系統層面的實務存取控制方法分類如下：
強制存取控制（Mandatory Access Control）
自由選定存取控制（Discretionary Access Control）
以角色為基礎的存取控制（Role-Based Access Control）
以規則為基礎的存取控制（Rule-Based Access Control）
```
### 紀錄(Accounting) 
```
內容項目包含量測（Measuring）、監控（Monitoring）、報告（Reporting）與紀錄檔案(Logging)，
以便提供未來作為稽核（Auditing）、計費（Billing）、分析（Analysis）與管理之用，
主要精神在於收集使用者與系統之間互動的資料，並留下軌跡紀錄。
```

## 其他概念
```
可歸責性(Accountability) == > 確保實體之行為可唯一追溯到該實體的性質。

可鑑別性（Authenticity）== > 能證明主體或資源之識別就是所聲明者的特性。

不可否認性(Non-repudiation) == > 對已發生的動作或事件的證明，使發起該動作或事件的實體，
                             往後無法否認其行為。實務上做法採用數位簽章技術。
```
