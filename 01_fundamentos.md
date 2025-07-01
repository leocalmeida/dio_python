# 🐍 Fundamentos do Python

> Aqui estão os conceitos básicos do Python explicados de um jeito fácil, com exemplos para me ajudar a lembrar.

---

## 📌 Conhecendo a Linguagem de Programação Python

- Python é uma linguagem de **alto nível**, **interpretada**, com **tipagem dinâmica** e **forte**.
- Muito utilizada em automações, análise de dados, web, IA, entre outros.
- Utiliza indentação para definir blocos de código, no lugar de chaves `{}` ou `begin/end`.

### 🧪 Exemplo:

```python
nome = "Leonardo"
print(f"Olá, {nome}!")
```

### 🧮 Tipos de Operadores com Python

🔢 Aritméticos
| Operador | Descrição       | Exemplo          |
| -------- | --------------- | ---------------- |
| `+`      | Soma            | `3 + 2` → `5`    |
| `-`      | Subtração       | `5 - 1` → `4`    |
| `*`      | Multiplicação   | `2 * 3` → `6`    |
| `/`      | Divisão real    | `10 / 4` → `2.5` |
| `//`     | Divisão inteira | `10 // 3` → `3`  |
| `%`      | Módulo          | `10 % 3` → `1`   |
| `**`     | Potência        | `2 ** 3` → `8`   |


🔄 Relacionais (comparação)
| Operador | Significado    | Exemplo           |
| -------- | -------------- | ----------------- |
| `==`     | Igualdade      | `5 == 5` → `True` |
| `!=`     | Diferente      | `5 != 3` → `True` |
| `>`      | Maior que      | `7 > 3` → `True`  |
| `<`      | Menor que      | `2 < 5` → `True`  |
| `>=`     | Maior ou igual | `5 >= 5` → `True` |
| `<=`     | Menor ou igual | `3 <= 4` → `True` |


⚙️ Lógicos
| Operador | Exemplo          | Resultado |
| -------- | ---------------- | --------- |
| `and`    | `True and False` | `False`   |
| `or`     | `False or True`  | `True`    |
| `not`    | `not True`       | `False`   |


### 🧭 Estruturas Condicionais e de Repetição

✅ Condicional if, elif, else
```python
idade = 18

if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```
🔁 Laço for
```python
for i in range(5):
    print(i)
```
🔁 Laço while
```python
contador = 0
while contador < 3:
    print(contador)
    contador += 1
```

### 🔤 Manipulando Strings com Python

🛠️ Operações básicas
```python
texto = "Python é incrível"

print(len(texto))             # Tamanho da string: 17
print(texto.upper())          # Maiúsculas: PYTHON É INCRÍVEL
print(texto.lower())          # Minúsculas: python é incrível
print(texto.replace("incrível", "poderoso"))  # Substituição: Python é poderoso
print(texto.split())          # Quebra em lista de palavras: ['Python', 'é', 'incrível']
```

🧩 Fatiamento
```python
nome = "Leonardo"
print(nome[0])      # Primeira letra: L
print(nome[:4])     # Do início até o índice 3: Leon
print(nome[-1])     # Última letra: o
```
