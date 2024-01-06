
#  Matplotlib 

Repositorio de Dicas


## Comandos básico

Lista de comandos mais ultilizado no dia a dia 


```bash

import matplotlib.pyplot as plt

# Dados
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

# Criar o gráfico de linha
plt.plot(x, y)

# Adicionar rótulos aos eixos
plt.xlabel('Eixo X')
plt.ylabel('Eixo Y')

# Adicionar um título
plt.title('Gráfico de Linha Simples')

# Exibir o gráfico
plt.show()

import matplotlib.pyplot as plt

# Dados
x = [1, 2, 3, 4, 5]
y = [2, 4, 6, 8, 10]

# Criar o gráfico de dispersão
plt.scatter(x, y, marker='o', color='blue')

# Adicionar rótulos aos eixos
plt.xlabel('Eixo X')
plt.ylabel('Eixo Y')

# Adicionar um título
plt.title('Gráfico de Dispersão com Marcadores')

# Exibir o gráfico
plt.show()

import matplotlib.pyplot as plt

# Dados
categorias = ['Categoria A', 'Categoria B', 'Categoria C']
valores = [3, 7, 5]

# Criar o gráfico de barras
plt.bar(categorias, valores, color='green')

# Adicionar rótulos aos eixos
plt.xlabel('Categorias')
plt.ylabel('Valores')

# Adicionar um título
plt.title('Gráfico de Barras Simples')

# Exibir o gráfico
plt.show()
```




## Autores

- [Aclelino](https://github.com/Aclelino)


