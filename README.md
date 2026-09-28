# Wuri TT Test Pages

這是 **Wuri TT Test** 的部署專用 GitHub Pages repository。

- 測試網站：`https://bollinmore-hermes.github.io/wuri-table-tennis-league-test/`
- 唯一原始碼來源：`bollinmore-hermes/wuri-table-tennis-league`
- Supabase Test project ref：`vppjcjfbcoxzofcuxmzz`

此 repository 不維護應用程式副本。Pages workflow 會 checkout 原始碼 repository 的指定 branch、tag 或 commit，執行測試，再產生 fail-closed Test artifact。

## 手動部署

在 GitHub Actions 執行 **Deploy Wuri TT Test Pages**，並填入要驗證的 `source_ref`。預設為 `main`。

Test 與 Production 使用不同 Supabase project；workflow 會驗證 artifact 不含 Production project ref。
