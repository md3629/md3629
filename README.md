### Hi there 👋
- [x] I use **M** for data transformation (_ETL_), **DAX** and **R** for data visualisation and analysis, and **SQL** for data query

```mermaid
graph TD;
    my(MyGitHub)-->|Repository|FP&A;
    FP&A-->|Repository|Reporting;
    FP&A-->|Repository|Budget;
    
    my(MyGitHub)-->|Repository|a((DataScience<br> with R));
    
    my(MyGitHub)-->|Repository|MacroEconomics;
    a((DataScience<br> with R))--Repository-->Forecasting;
    a((DataScience<br> with R))--Repository-->Segmentation;
    a((DataScience<br> with R))--Repository-->Uncertainity;
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

- [ ] check out all my repositories :point_down: 
