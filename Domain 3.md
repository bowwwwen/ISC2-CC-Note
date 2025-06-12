# Domain 3：存取控制概念（Access Control Concepts）

## 3.1 物理存取控制（Physical Access Control）

- **目的**：防止未授權者進入敏感地區或設備，保護資產與人身安全。
- **防護方式**：
  - 門禁系統、磁卡、電子鑰匙、安全閘門、保全人員、訪客登記。
  - 監控設備如 CCTV、訪客簽到登記系統。
- **常見風險與緩解**：
  - 尾隨（tailgating）：使用閘門與保全提醒。
  - 強行開門：安裝磁錠、門狀態監控。

## 3.2 存取控制基本概念（Access Control Fundamentals）

- **元素**：
  1. Subject（主體）— 發出存取請求者（使用者、進程）。
  2. Object（物件）— 被存取的目標（檔案、資料、資源）。
  3. Rules（規則）— 決定存取允許或拒絕的政策。  
  同時包含授權與阻止機制，構成全面存取控制策略。

## 3.3 存取控制模型（Access Control Models）

- **DAC（Discretionary Access Control）**：資源所有者自行設定權限，可自由分享。
- **MAC（Mandatory Access Control）**：基於安全等級與標籤，由中央策略強制控管。
- **RBAC（Role-Based Access Control）**：依角色賦予權限，便於規模管理。
- **ABAC（Attribute-Based Access Control）**：依屬性（角色、地點、時間等）動態決策，更靈活。詳見 XACML、ALFA。
- **ReBAC（Relationship-Based Access Control）**：根據主體與物件間關係進行授權。
- **PAM（Privileged Access Management）**：專門控管特權帳號與操作。

## 3.4 存取控制類別（Access Control Categories）

- **技術性控制**：ACL、授權系統、加密、身份驗證。
- **管理性控制**：政策與程序、背景調查、EPP、帳戶審查。
- **實體性控制**：硬體門禁、機房控制、CCTV、保全人員。

## 3.5 存取控制功能（Access Control Functions）

- **存取強制（Enforcement）**：依規則執行授權或阻止。
- **最小權限（Least Privilege）**：僅授予最低必要權限。
- **分離職責（Separation of Duties）**：防止權力集中導致濫用。
- **帳號管理與審計**：如帳戶註冊、撤銷、定期復核與日誌。
- **持續存取控制**：定期再認證、異常登入告警、異常帳號通知。

## 3.6 遠端存取控制（Remote Access Control）

- **重要性**：隨遠距工作普及與第三方連線需求提高，遠端存取面臨更多威脅。
- **最佳實踐內容**：
  - **策略明確**：明訂允許的遠端工具（VPN、SSH、RDP）與使用程序。
  - **Least Privilege 原則**：限權存取，定期清理不必要帳號。
  - **強化驗證**：施行 MFA 或硬體憑證登入。
  - **連線安全**：使用加密隧道、NLA、限制 IP 地址。
  - **裝置強化**：確保終端設備打補丁、使用 EDR、防毒、防火牆與 MDM。
  - **Zero Trust 架構**：每次存取皆需驗證身份與位置。
  - **監控與稽核**：持續審計遠端活動、登入嘗試與配置變更。
- **安全控管工具**：VPN、MFA、MFA、MDM/EDR；針對 RDP 加強限制。

## 3.7 遵循與標準（Policies & Standards）

- **存取控制政策（Access Control Policy）**：
  - 確定角色、帳戶流程、回收機制、日誌紀錄與審查。
- **遵循法規與標準**：
  - 例：NIST 800‑53 AC‑1、ISO 27001 中相關 Access Control 條款。
  - 適用於資料保護與隱私要求（GDPR、FIPS）。
