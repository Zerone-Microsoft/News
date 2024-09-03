# Azure Tenant Security Solution (AzTS) 提供企業環境多訂閱和資源配置的可見性

**日期與時間：2024.09.03 AM 10:12**

**編輯者：Brian Hsing (brian.hsing@zerone.com.tw)**  
**編修者：Mark Chang (mark.chang@zerone.com.tw)**

由 AzSK 團隊提供的 **Azure Tenant Security Solution (AzTS)** 是一個開放原始碼專案，旨在幫助企業在多訂閱和資源配置中獲得更高的可見性。AzTS 是 DevOps Kit 的邏輯進展，利用當前 Azure 平台中的原生安全功能，實現雲安全合規解決方案的實施。其功能類似於以中央掃描模式運行的 AzSK 持續保證 (Continuous Assurance)。

!![image](https://github.com/user-attachments/assets/ce40ba28-75a4-4519-b11a-84741a663b26)

## AzTS 的建立有以下幾個明確目標：

- **高效掃描大量訂閱**：在中央掃描模式下，以成本效益高且時間效率高的方式掃描大量訂閱。
- **靈活調整掃描能力**：在不受外部限制（例如 runbook memory、runbook limits）的情況下，靈活調整掃描能力。
- **加快向原生功能過渡**：能夠更快地響應 Azure 的變更，並部署控制修改，加快向原生功能過渡的努力。
- **逐步過渡到基於 Azure/MDC 策略的方法**：使控制從自定義代碼逐步過渡到基於 Azure/MDC 策略的方法，使用當前可用的 MDC/策略控制，並隨著更多控制的可用性繼續遷移。

AzTS 的這些目標旨在提升企業在雲端環境中的安全性和合規性，為企業提供更強大的安全保障。

**資料來源**：https://github.com/azsk/AzTS-docs
