# Xilinx HBM 測試專案

此倉庫包含Xilinx HBM (High Bandwidth Memory) 測試專案的VCS (Synopsys VCS) 模擬相關檔案，包括：

- 模擬日誌檔案 (*.log)
- 腳本檔案 (*.sh, *.do)
- 配置檔案
- 其他模擬相關成品

## 注意事項

- FSDB波形檔案 (*.fsdb) 已被忽略，不包含在此倉庫中。
- 二進制檔案和大型模擬成品也可能被排除。

## 檔案說明

- `simulate.log`: 模擬執行日誌
- `memory_test.log`: 記憶體測試日誌
- `tb_design_wrapper.sh`: 測試平台執行腳本
- `glbl.v`: 全域模組定義
- `synopsys_sim.setup`: Synopsys模擬設定檔