### Hi there 👋
- [x] I use **M** for data transformation (_ETL_), **DAX** and **R** for data visualisation and analysis, and **SQL** for data query

```mermaid
graph TD;
    my(MyGitHub)-->|Repository|FP&A;
    FP&A-->|Repository|Reporting;
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
    DataScience-->R;
```

- [ ] check out all my repositories :point_down: 
