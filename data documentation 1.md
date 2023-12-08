## Data Documentation

Once you have created your final “clean” dataset, you will need to create transparent and accessible documentation about your dataset. This document should be enough for someone to begin using your dataset for their own work.

The documentation should include:

#### What are the original data sources (including web links or other pointers to the original material)

#### Explanation of all variables you include here.

#### Basic summary statistics: number of rows, column, and number of missing/otherwise invalid values by each column (You may add other helpful details, e.g. figures or tables, to the documentation)






1.Gun Violence Dataset(2021) US: CDC compiles and reports firearm mortality data.

Source:https://www.cdc.gov/nchs/pressroom/sosmap/firearm_mortality/firearm.htm

Variables:Year<dbl>, State<chr>, abbr<chr>(abbreviate of State), Death_Rate<dbl> caused by gun violence, Deaths<dbl> caused by gun violence

Rows: 50 because there are 50 states in US

column:5 there are Year<dbl>, State<chr>, abbr<chr>, Death_Rate<dbl>, Deaths<dbl>

missing values: None




2.Sex Ratio Dataset(2021) US: KFF gathers demographic information, including sex ratio.

Source: https://www.kff.org/other/state-indicator/distribution-by-sex/?currentTimeframe=1&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D

Variables:State<chr>,abbr<chr>(abbreviate of State), Male_Ratio<dbl>,Female_Ratio<dbl>,Total_Ratio<dbl>

Rows: 50 because there are 50 states in US

column:5 there are State<chr>,abbr<chr>(abbreviate of State), Male_Ratio<dbl>,Female_Ratio<dbl>,Total_Ratio<dbl>

missing values: None




3.Real GDP per Capita Dataset(2022) US: Statista collects economic data, specifically real GDP per capita.

Source: https://www/statista.com/statistics/248063/per-capita-us-real-gross-domestic-product-gdp-by-state/

Variables: State<chr>，abbr<chr>(abbreviate of State)，Real_GDP_per_Capita<dbl>

Rows: 50 because there are 50 states in US

column: 3 there are State<chr>，abbr<chr>，Real_GDP_per_Capita<dbl>

missing values: None




4.Number of Registered Weapons Dataset(2021) US: Statista compiles data on the number of registered weapons.

Source: https://www.statista.com/statistics/215655/number-of-registered-weapons-in-the-us-by-state/

Variables: State<chr>，abr<chr>(abbreviate of State)，Number_of_ Registered_Weapon<dbl>

Rows: 50 because there are 50 states in US
 
column: 3 there are State<chr>，abr<chr>，Number_of_ Registered_Weapon<dbl>

missing values: None



If you do not know some of the answers, the state it clearly: e.g. “The original data collector is unknown”. There should not be too many unknowns though. And you should know everything that you can compute from data, such as the number of missings.