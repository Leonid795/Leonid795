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
2.import pandas as pd
import matplotlib.pyplot as plt

file_path = 'data.xlsx'
df = pd.read_excel(file_path)

print(df.head())
plt.figure(figsize=(5, 7))
plt.plot(df['x'], df['y'], marker='o', label='Зависимость y от x')
plt.title('График из Excel')
plt.xlabel('Ось X')
plt.ylabel('Ось Y')
plt.legend()
plt.grid(True)
plt.show()

3.import pandas as pd
import matplotlib.pyplot as plt

file_path = 'data.xlsx'
df = pd.read_excel(file_path)

print(df.head())
plt.figure(figsize=(5, 7))
plt.plot(df['x'], df['y'], marker='o', label='Зависимость y от x')
plt.title('График из Excel')
plt.xlabel('Ось X')
plt.ylabel('Ось Y')
plt.legend()
plt.grid(True)
plt.show()
