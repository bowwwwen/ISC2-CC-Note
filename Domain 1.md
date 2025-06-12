# Domain 1：資訊安全原則（Security Principles）

## 1.1 了解資訊保障的安全概念（Understand the security concepts of information assurance）

### a. CIA 三要素
- **機密性（Confidentiality）**：資訊僅對授權者可用，防止未授權存取。
- **完整性（Integrity）**：資訊未經未授權變更，保持正確性。
- **可用性（Availability）**：資訊及服務在需要時可被合法用戶取得。

### b. Personally Identifiable Information（PII）
- 定義：能單獨或與其他資訊組合後識別個人的資料，如姓名、地址、生日、ID、Email、電話等。
- PII 的敏感度視組合而定，資料交叉比對越多，越能精確定位個人身分。

### c. 驗證因素（Authentication Factors）
1. **Something you know**：如密碼、PIN。
2. **Something you have**：如智能卡、OTP 裝置。
3. **Something you are**：如指紋、臉部辨識。
4. 延伸還包括 **Somewhere you are**（地理位置）、**Something you do**（行為特徵）。

### d. Non-repudiation（不可否認性）
- 定義：防止交易雙方事後否認其行為，常見於電子商務、數位簽章等場景。
- 實現方式：數位簽章、審計日誌、電子簽名等。

### e. 隱私與資料保護法規
- **HIPAA（Health Insurance Portability and Accountability Act）**
  - 美國醫療資訊隱私法案，規範 PHI（受保護醫療資訊）的收集、處理、存取與分享。違反可處罰金或監禁。
- **GDPR（General Data Protection Regulation）**
  - 歐盟個資保護法，強調資料主體權利，適用於 EU 境內所有人的個資（不論國籍），企業違規可處高額罰款。GDPR 也適用於在 EU 境外處理 EU 居民資料的公司。
- 其他常見法規還有 FERPA（美國學生教育紀錄保護法），但在 CC 主要強調 HIPAA 與 GDPR。

---

## 1.2 了解風險管理流程（Understand the risk management process）

### a. 流程步驟
1. **風險識別（Risk Identification）**：找出威脅、漏洞及其影響資產的方式。
2. **風險評估（Risk Assessment）**：評估威脅發生的可能性與影響程度。
3. **風險處理（Risk Treatment）**：包括避免、降低、轉移（如保險）、接受。
4. **風險監控與審查（Risk Monitoring and Review）**：持續追蹤風險狀態與控制效果。

### b. 風險容忍度（Risk Tolerance）
- 由高階管理層（執行長、董事會）決定整個組織可接受的風險範圍。

---

## 1.3 了解安全控制（Understand security controls）

### a. 控制類型
- **技術性控制（Technical）**：如存取控制、防火牆、加密、日誌紀錄。
- **管理性控制（Administrative）**：如政策、程序、員工訓練、背景調查。
- **實體性控制（Physical）**：如門禁、警報、CCTV、鎖。

### b. 控制功能分類
- 預防（Preventive）、偵測（Detective）、矯正（Corrective）、威懾（Deterrent）、補償（Compensating）。

---

## 1.4 了解 ISC2 道德守則（Understand the ISC2 Code of Ethics）

1. 保護社會與基礎設施
2. 誠實守法、公正負責
3. 勤奮盡責
4. 推動資安專業發展

---

## 1.5 了解治理流程（Understand governance processes）

### a. 法規與法律（Regulations & Laws）
- 由政府機構制訂，最高規範。違反通常有罰則。例如：
  - **HIPAA**：規範美國醫療資料保護。
  - **GDPR**：規範歐盟個資保護，影響力及罰則極大。
- 法規具有強制力，組織必須遵循。

### b. 標準（Standards）
- 規定具體執行細節、格式與技術規範，確保政策落實且一致。
- 例如：ISO/IEC 27001、NIST 標準等。

### c. 政策（Policies）
- 組織內部高階制定的原則與規定，指導方向及目標。

### d. 程序（Procedures）
- 詳細描述怎麼執行政策與標準的步驟與方法。

#### 治理正確順序：
Regulations → Standards → Policies → Procedures
