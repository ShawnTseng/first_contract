# First Contract

這是一個最簡化的 [Sui Move](https://docs.sui.io/) 範例套件。專案目前只有一個模組，並提供一個空的 `say_hello` 函式，作為未來開發的起點。

## 結構
- `sources/first_contract.move`：定義 `first_contract::hello` 模組，其中包含 `say_hello` 函式。
- `tests/first_contract_tests.move`：預留的測試範例，目前全部被註解，可作為撰寫測試的參考。

## 開發
1. 安裝 [Sui CLI](https://docs.sui.io/build/install) 以取得 `sui` 指令。
2. 編譯套件：
   ```bash
   sui move build
   ```
3. 執行測試：
   ```bash
   sui move test
   ```

> 若尚未安裝 Sui CLI，上述指令將無法執行。

## 授權
本專案使用 MIT 授權。
