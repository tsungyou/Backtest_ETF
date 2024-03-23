
<!-- GETTING STARTED -->
## Getting Started

用00713加權方法重新對0056加權，比較選股邏輯不變情況下報酬差異，給出結論

V1 圖片:

![image](https://github.com/tsungyou/Backtest_ETF/blob/main/calculation/comp_c1.png)

### Backtest System
以標準差加權，不是最小變異數，但或許可以以1/變異數為加權概念找低波、非高息(高息透過選股達成) 組合
* Var-weighted(misunderstanding)
  ```sh
  cd '.\calculation\'
  backtest_var_weighted.ipynb
  ```

### Minimum Variance Portfolio
最小變異數x蒙地卡羅方法找投資組合變異數最小的權重組合
* Minimum Variance
  ```sh
  cd '.\calculation\'
  minimum_variance_portfolio.ipynb
  ```

### Database Implementation
Database
* Historical stock price
  ```sh
  cd '.\DB\TW'
  ```
* Historical 0056 Ingredient
  ```sh
  cd '.\DB\'
  0056_Ingred.json
  ```

* TW stock sybmol-to-codename list
  ```sh
  cd '.\DB\'
  tw_stock_symbol_code.json
  ```


