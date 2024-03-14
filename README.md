### Hi there 👋


- 🔭 I’m currently working on Forecasting using **R**
- I use **M** for data transformation (_ETL_), **DAX** and **R** for data visualisation and analysis, and **SQL** for data query
- Have a look at my short presentation about my prefered solutions in BI 👉 [:computer:](https://md3629.github.io/)
- check out my repositories :point_down: and :black_nib: if you need any help

```mermaid
graph TD;
    MyGitHub-->|Repository|FP&A;
    Inv[/Inventory<br>Management/]-->|Repository|Budget;
    FP&A-->|Repository|Budget;
    R(R)-->DataScience;
    MyGitHub-->|Repository|DataScience;
    MyGitHub-->|Repository|MacroEconomics;
    DataScience-->Modeling;
    DataScience-->Forecasting;
    DataScience-->Clustering;
    DataScience-->Uncertainity;
    Uncertainity-->P((Power<br>BI));
    Forecasting-->P((Power<br>BI));
    Clustering-->P((Power<br>BI));
    Budget-->P((Power<br>BI));
    Budget-->E((Excel<br>BI));
    D(DAX)-->E((Excel<br>BI));
    M(M)-->E((Excel<br>BI));
    E((Excel<br>BI))-->P((Power<br>BI));
    E((Excel<br>BI))-->A(MDX);
```
