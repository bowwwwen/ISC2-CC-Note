# Domain 1：資訊安全原則（Security Principles）

## 1.1 資訊保障概念（Security Concepts of Information Assurance）

### CIA 三要素
- **機密性（Confidentiality）**：資訊僅向授權者揭露，防止未授權存取，措施包括加密、防火牆、身份驗證等。
- **完整性（Integrity）**：防止資料被未授權或意外修改，措施如雜湊、數位簽章、版本控制。
- **可用性（Availability）**：確保授權者在需要時能使用資訊，措施包括備援、容錯、災難復原計畫（DRP）。

### PII（Personally Identifiable Information）
- 定義：任何可單獨或經由多種資料組合後識別個人的資訊，例如姓名、地址、生日、電子郵件、身分證號等。

### 驗證因素（Authentication）
1. **Something you know**：密碼、PIN。
2. **Something you have**：如硬體 token、一次性密碼（OTP）。
3. **Something you are**：如指紋、人臉、虹膜等生物識別。
- 延伸方式：行為辨識、地理位置等多因素驗證架構。

### Non‑repudiation（不可否認性）
- 確保行為或通訊不能被當事人否認，常使用數位簽章、時間戳記、審計日誌等技術。

### 隱私/資料保護法規（Privacy）
- **GDPR（歐盟）**：保護 EU 境內的個人資料，不論是否為歐盟公民，包括存取、更正及刪除等基本權利。違規可處高額罰款。
- **HIPAA（美國）**：保護美國 PHI（受保護的醫療資訊），處理需符合法規；違規可罰款或面臨刑責。

---

## 1.2 風險管理流程（Risk Management Process）

1. **識別（Identify）**：找出威脅、漏洞與資產；來源包括內部與外部。
2. **評估（Assess）**：依風險可能性與影響按高/中/低或定量分析，並繪製風險矩陣。
3. **優先排序（Prioritize）**：根據評估結果，列出優先處理清單，供後續處理及資源安排使用。
4. **決策與處理（Decision‑Making & Treatment）**：依優先順序與組織風險容忍度，採取：避免、減緩、轉移、接受。
5. **監控與審查（Monitor）**：定期監控、更新風險矩陣與控制效果，並由高階管理層制定風險容忍度。

---

## 1.3 安全控制（Security Controls）

### 控制類型
- **技術性**：存取控制、防火牆、IDS/IPS、加密等。
- **管理性**：政策、程序、培訓、AUP、背景調查。
- **實體性**：門禁、監視器（CCTV）、保全人員等。

### 控制功能分類
- **預防性**（Preventive）：阻止事故發生。
- **偵測性**（Detective）：監控並識別異常，例：IDS。
- **矯正/回復性**（Corrective / Recovery）：修復與恢復功能，例：備份、災難復原。
- **威懾性**（Deterrent）：透過規範、警示抑制行為。
- **補償性**（Compensating）：當主措施不夠時的替代方案。

### 多層防禦（Defense‑in‑Depth）
- 構建多層保護架構，避免單一措施成為唯一防線。

---

## 1.4 ISC2 職業道德守則（ISC2 Code of Ethics）

1. 保護社會與基礎設施  
2. 誠實、守法、公正與負責任的行為  
3. 勤奮盡責  
4. 推動資訊安全專業的發展與分享知識。

---

## 1.5 治理流程（Governance Processes）

### 層級關係與順序
1. **Regulations & Laws**（法規）：具有最高約束力，例：GDPR、HIPAA。
2. **Standards**（標準）：技術與流程細節，如 ISO 27001、NIST。
3. **Policies**（政策）：組織內部的目標與原則。
4. **Procedures**（程序）：執行政策的具體步驟與方法。
- 順序**Regulations → Standards → Policies → Procedures** 
