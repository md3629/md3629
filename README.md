### Hi there 👋
- I use **M** for data transformation (_ETL_), **DAX** and **R** for data visualisation and analysis, and **SQL** for data query
- Have a look at my short presentation about my prefered solutions in BI 👉 [:computer:](https://md3629.github.io/)

```mermaid
graph TD;
    my(MyGitHub)-->|Repository|FP&A;
    Inv[/Inventory<br>Management/]-->|Repository|Budget;
    FP&A-->|Repository|Budget;
    my(MyGitHub)-->|Repository|DataScience;
    my(MyGitHub)-->|Repository|MacroEconomics;
    DataScience--Repository-->Forecasting;
    DataScience--Repository-->Segmentation;
    DataScience--Repository-->Uncertainity;
    Uncertainity-->P((Power<br>BI));
    Forecasting-->P((Power<br>BI));
    Segmentation-->P((Power<br>BI));
    Budget-->P((Power<br>BI));
    D(DAX)x--xE((Excel));
    M(M)x--xE((Excel));
    E((Excel))<-.->P((Power<br>BI));
    A(MDX)x--xE((Excel));
    E((Excel))<-->SSAS;
    P((Power<br>BI))<-->SSAS;
```

### Samples in Excel, Power BI or R
- [x] Budgeting (bottom up): https://github.com/md3629/FPA/blob/main/Budget/data/Model.xlsx
- [x] Forecasting: https://github.com/md3629/FPA/blob/main/Budget/data/Budget%20-%20Top%20Down.pbix
- [x] Sales backlog analysis https://github.com/md3629/FPA/blob/main/FinancialDetails/SalesBacklog/SalesBacklog.xlsx
- [x] Financial Summaries https://github.com/md3629/FPA/blob/main/data/Exec%20Summary%20with%20Budget.xlsx
- [x] Uncertainity (R scripts): https://github.com/md3629/Data-Science/tree/main/Predictive-Analytics
- [x] Inventory Analysis https://github.com/md3629/FPA/blob/main/FinancialDetails/InventoryManagement/Inventory%20Analysis.pbix
- [ ] check out all my repositories :point_down: and :black_nib: if you need any help
