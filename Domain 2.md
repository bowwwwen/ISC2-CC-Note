# Domain 2：業務持續性、災難復原與事件回應（BC / DR / IR）

## 2.1 業務持續性（Business Continuity, BC）

### a. 目的
確保企業在面對重大中斷（自然災害、網路攻擊、硬體故障等）時能持續運作與提供關鍵服務。:contentReference[oaicite:1]{index=1}

### b. 重要性
- 維持系統與服務的可用性，避免財務損失。
- 保護公司聲譽與客戶信任。
- 滿足法規（例如金融或醫療產業）對於業務不中斷的要求。:contentReference[oaicite:2]{index=2}

### c. 關鍵組成
1. 範圍定義：鑑別哪些業務流程與資產為關鍵。
2. **業務影響分析（BIA）**：評估停擺對時間與財務的影響，確定 RTO / RPO 目標。:contentReference[oaicite:3]{index=3}
3. 策略與控管：如冗餘備援、異地備援、替代工作地、跨團隊支援。
4. 實作與測試：建立計劃、演練並驗證安全性。

---

## 2.2 災難復原（Disaster Recovery, DR）

### a. 目的
在重大中斷後能迅速恢復 IT 基礎架構與系統功能，用以支援業務持續。:contentReference[oaicite:4]{index=4}

### b. 重要性
- 恢復關鍵 IT 基礎設施並快速回歸服務。
- 避免資料永久遺失與業務持續中斷。
- 確保遵守 SLA 與法規要求。

### c. 組成要素
- 資料備份頻率與形式（異地／雲端）。
- RPO (Recovery Point Objective)、RTO (Recovery Time Objective)。
- 混合或異地備援架構（例如冷備/熱備站）。
- 定期恢復測試與驗證程序。
- 建立緊急 DR 團隊與連絡機制。

---

## 2.3 事件回應（Incident Response, IR）

### a. 目的
在事件發生時快速偵測、遏止、清除威脅，並恢復營運與降低影響。:contentReference[oaicite:5]{index=5}

### b. 重要性
- 快速響應可顯著減少損害程度。
- 依循法規與合規要求。
- 有助建立信任與控制機制持續改進。

### c. 事件回應流程（依 NIST SP 800‑61 四階段模型）：

1. **預備（Preparation）**  
   - 建立 IR 團隊與角色分工。
   - 制定流程、工具與資源（如 SIEM, IR playbook）。
   - 進行教育與桌面演練。

2. **偵測與分析（Detection & Analysis）**  
   - 通過告警、日誌、異常活動辨識事件。
   - 建立事件嚴重程度分類（如 P1～P4）。
   - 蒐集證據、保留截圖與日誌。

3. **遏止、根除與回復（Containment, Eradication & Recovery）**  
   - 快速遏制事件範圍。
   - 清除惡意程式或漏洞根源。
   - 恢復受影響系統至正常狀態。

4. **事後檢討（Post-Incident Activity）**  
   - 執行根因分析與改善步驟。
   - 更新計劃、程序與控管措施。
   - 分享經驗並舉辦教育訓練。

### d. IR 團隊成員
- 高層管理、資安工程師、法律、公關、IT、SOC 人員等跨部門共同支援。:contentReference[oaicite:6]{index=6}

---

## 2.4 BC、DR 與 IR 的關係

- **IR**：立即應對事件。
- **BC**：在危機期間保持業務運作。
- **DR**：恢復基礎設施與系統功能。
三者協同保障持續運營。:contentReference[oaicite:7]{index=7}

---

### 📌 小結比較表

| 項目 | 目的 | 範圍/重點 |
|------|------|----------|
| IR   | 快速偵測與應變 | 偵測、根除、恢復正常 |
| BC   | 維持業務不中斷 | 範圍定義、BIA、運營替代策略 |
| DR   | 恢復 IT 系統 | 備援架構、資料恢復、測試 |

---

> ✅ **接下來的步驟：**
> - 將這份 `Domain 2.md` 上傳至 GitHub；
> - 若未來你完成官網課程並產生錯題，請直接貼出來，我會協助你逐題補強內容與筆記！

---

這份筆記已完整涵蓋 2.1～2.3 所有考綱項目，如需更進階案例或實務工具介紹（如 RTO/RPO 範例、IR playbook 範本）也可以後續補充！
::contentReference[oaicite:8]{index=8}
