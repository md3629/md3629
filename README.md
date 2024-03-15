### Hi there 👋


- 🔭 I’m currently working on Forecasting using **R**
- I use **M** for data transformation (_ETL_), **DAX** and **R** for data visualisation and analysis, and **SQL** for data query
- Have a look at my short presentation about my prefered solutions in BI 👉 [:computer:](https://md3629.github.io/)
- check out my repositories :point_down: and :black_nib: if you need any help

```mermaid
graph TD;
    my(MyGitHub)-->|Repository|FP&A;
    Inv[/Inventory<br>Management/]-->|Repository|Budget;
    FP&A-->|Repository|Budget;
    R( R )x--xDataScience;
    my(MyGitHub)-->|Repository|DataScience;
    my(MyGitHub)-->|Repository|MacroEconomics;
    DataScience-->Modeling;
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
