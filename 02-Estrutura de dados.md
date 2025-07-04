# 🐍 Estruturas de Dados em Python
> Aqui estão alguns exemplos de Estruturas de Dados em Python, explicados de um jeito fácil, com exemplos para me ajudar a lembrar.
---

### 📦 1. Listas (list)
As listas são coleções ordenadas e mutáveis de itens. Isso significa que você pode adicionar, remover ou modificar elementos após a criação da lista. Elas podem conter itens de diferentes tipos de dados.

Características:
- Ordenadas (mantêm a ordem de inserção)
- Mutáveis (podem ser modificadas)
- Permitem elementos duplicados
- Acessadas por índice

```Python
minha_lista = [1, 'Leonardo', 3.14, True]

print(minha_lista[0])  # Saída: 1
minha_lista.append('Novo Item')
print(minha_lista) # Saída: [1, 'Leonardo', 3.14, True, 'Novo Item']
```

### 🔒 2. Tuplas (tuple)
As tuplas são coleções ordenadas e, ao contrário das listas, são imutáveis. Uma vez criada, uma tupla não pode ser alterada. Elas são úteis para representar coleções de itens que não devem ser modificados, como coordenadas geográficas ou configurações.

Características:
- Ordenadas (mantêm a ordem de inserção)
- Imutáveis (não podem ser modificadas após a criação)
- Permitem elementos duplicados
- Acessadas por índice

```Python
minha_tupla = (10, 20, 30)

print(minha_tupla[1]) # Saída: 20
# minha_tupla.append(40) # Isso geraria um erro!
```

### 🧩 3. Conjuntos (set)
Os conjuntos são coleções não ordenadas de itens únicos. Eles são extremamente úteis para remover duplicatas de uma lista ou para realizar operações matemáticas de conjunto, como união, interseção e diferença.

Características:
- Não ordenados (a ordem dos elementos não é garantida)
- Mutáveis (podem ser modificados)
- Não permitem elementos duplicados (apenas valores únicos)
- Não permitem fatiamento

```Python
meu_conjunto = {1, 2, 3, 2, 4}
print(meu_conjunto) # Saída: {1, 2, 3, 4} (a ordem pode variar)

conjunto_a = {1, 2, 3}
conjunto_b = {3, 4, 5}
print(conjunto_a.union(conjunto_b)) # Saída: {1, 2, 3, 4, 5}

print(conjunto_a[0]) # Saída: TypeError: 'set' object is not subscriptable
```

### 📚 4. Dicionários (dict)
Os dicionários são coleções não ordenadas de pares chave-valor. Cada valor é associado a uma chave única, permitindo uma recuperação eficiente dos dados. São ideais para representar dados estruturados, como informações de usuários ou configurações.

Características:
- Não ordenados (a partir do Python 3.7, a ordem de inserção é mantida, mas não se deve confiar totalmente nisso para versões anteriores)
- Mutáveis (podem ser modificados)
- As chaves devem ser únicas e imutáveis (strings, números, tuplas)
- Os valores podem ser de qualquer tipo e podem ser duplicados

```Python
meu_dicionario = {
    "nome": "Roberval",
    "idade": 57,
    "cidade": "São Pedro dos Morrinhos"
}
print(meu_dicionario["nome"]) # Saída: Roberval

meu_dicionario["idade"] = 31
print(meu_dicionario) # Saída: {'nome': 'Roberval', 'idade': 31, 'cidade': 'São Pedro dos Morrinhos'}
```

### 🧠 5. Funções (def)

Funções são blocos de código que podem ser reutilizados em diferentes partes do programa. Elas ajudam a deixar o código mais limpo, organizado e fácil de manter.

✏️ Como criar uma função
```python
def saudacao():
    print("Olá!")

# Para chamar a função:
saudacao()
```
🧩 Função com parâmetros
```python
def saudacao_personalizada(nome):
    print(f"Olá, {nome}!")

saudacao_personalizada("Leonardo")

# Um parâmetro com valor padrao
def saudacao_personalizada(nome="Cleitin"):
    print(f"Olá, {nome}!")

saudacao_personalizada("Leonardo") #Saída: Olá, Leonardo!
saudacao_personalizada() #Saída: Olá, Cleitin!
```
```python
🔁 Função com retorno
def soma(a, b):
    return a + b

resultado = soma(3, 5)
print(resultado)  #Saida: 8
```
