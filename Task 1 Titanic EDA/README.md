| Column          | Description                                                          |
| --------------- | -------------------------------------------------------------------- |
| **survived**    | 1 = survived, 0 = did not survive                                    |
| **pclass**      | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)                          |
| **sex**         | Gender of passenger                                                  |
| **age**         | Passenger’s age in years                                             |
| **sibsp**       | # of siblings/spouses aboard                                         |
| **parch**       | # of parents/children aboard                                         |
| **fare**        | Ticket fare                                                          |
| **embarked**    | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |
| **class**       | Duplicate of pclass (categorical version)                            |
| **who**         | man / woman / child (auto-classified)                                |
| **adult_male**  | Boolean (True if male adult)                                         |
| **deck**        | Cabin deck letter (many missing values)                              |
| **embark_town** | Port of embarkation (text form)                                      |
| **alive**       | “yes” or “no” version of survived                                    |
| **alone**       | True if passenger had no family aboard                               |

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Key Findings from Titanic EDA
1️ Survival Distribution

Only about 38% of passengers survived.

This confirms the Titanic tragedy’s scale — survival was far less common.

2️ Gender & Survival

Females had a much higher survival rate than males.
→ Reflects the “Women and children first” evacuation policy.

3️ Passenger Class & Survival

1st-class passengers had the highest chance of survival.

3rd-class passengers suffered the most losses.
→ Economic and cabin location differences clearly affected outcomes.

4️ Age & Survival

Majority of passengers were young adults (20–35 years).

Children had slightly better chances than middle-aged men.

Very few older passengers survived.

5️ Correlation Heatmap Insights

survived is negatively correlated with:

pclass (–0.34): higher class → better survival

adult_male (–0.56): males less likely to survive

fare shows positive correlation (0.26): wealthier passengers had higher survival odds.

Conclusion

This EDA provides a clear picture of the social and survival dynamics aboard the Titanic.
Survival was strongly influenced by gender, class, and wealth, with women and 1st-class passengers having the greatest advantage.
