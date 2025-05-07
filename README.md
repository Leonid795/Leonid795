- 👋 Hi, I’m @Leonid795
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Leonid795/Leonid795 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Сундуков Леонид(МФ-71)Средний уровень(B)
1.import pandas as pd
df_excel = pd.read_excel('Книга.xlsx')
print(df_excel.head())
print(df_excel.sample(3))
print(df_excel.tail(3))
a=int(input("напишите строки которые вам нужны"))
df_excel = pd.read_excel('Книга (1).xlsx',index_col=a)
print(df_excel)
