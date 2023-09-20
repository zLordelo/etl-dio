# etl-dio

Script:

<code>import pandas as pd
caminho = input(print("Insira o caminho do arquivo: "))
df = pd.read_csv(caminho)
caminho = caminho.replace("csv", "xlsx")
df.to_excel(caminho, index=None, header=True)
print("Arquivo convertido com sucesso!")</code>

[Link do Colab](https://colab.research.google.com/drive/1uhPRwLYhBomyA5hKSl_59KSQ8Dpckh5o?usp=sharing)

  
