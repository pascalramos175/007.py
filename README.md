# 📝 Exibir Informações em Múltiplas Linhas — Python

Um programa simples em **Python** que demonstra diferentes maneiras de exibir textos em várias linhas no terminal.

## 📌 Sobre o projeto

Normalmente, uma chamada de `print()` exibe uma mensagem e pula automaticamente para a próxima linha.

Neste exercício, são apresentadas **duas formas diferentes** de criar uma saída com várias linhas:

* Utilizando **strings multilinha** com `"""`.
* Utilizando o parâmetro `sep="\n"` do `print()`.

## 💻 Código

```python
print("""Linha 1: Bem-vindo ao Python.
Linha 2: Esta é uma string multilinha.
Linha 3: Fim do bloco.""")

# Outro jeito também seria:

print(
    "Linha 1: Bem-vindo ao Python.",
    "Linha 2: Esta é uma string multilinha.",
    "Linha 3: Fim do bloco.",
    sep="\n"
)
```

## 🔎 Como funciona?

### 1. Strings multilinha

Python permite criar uma string que ocupa várias linhas utilizando **aspas triplas**:

```python
print("""Linha 1
Linha 2
Linha 3""")
```

Tudo que estiver entre `"""` será considerado parte da mesma string, incluindo as quebras de linha.

Isso é útil para textos maiores que precisam manter sua formatação.

### 2. Utilizando `sep="\n"`

Outra maneira é passar várias strings para o `print()`:

```python
print(
    "Linha 1",
    "Linha 2",
    "Linha 3",
    sep="\n"
)
```

O parâmetro `sep` define o que será colocado **entre cada argumento** recebido pelo `print()`.

Por padrão, o separador é um espaço:

```python
print("Olá", "Python")
```

Resultado:

```text
Olá Python
```

Ao utilizar:

```python
sep="\n"
```

o separador passa a ser uma **quebra de linha**.

O resultado será:

```text
Olá
Python
```

## 🧠 O que é `\n`?

`\n` é um **caractere especial** que representa uma quebra de linha.

Por exemplo:

```python
print("Linha 1\nLinha 2")
```

Resultado:

```text
Linha 1
Linha 2
```

## ▶️ Resultado

As duas formas produzem essencialmente a mesma saída:

```text
Linha 1: Bem-vindo ao Python.
Linha 2: Esta é uma string multilinha.
Linha 3: Fim do bloco.
```

## 📚 Conceitos aprendidos

| Conceito           | Descrição                                        |
| ------------------ | ------------------------------------------------ |
| Strings            | Representam textos em Python                     |
| Strings multilinha | Permitem escrever textos em várias linhas        |
| `"""`              | Delimita strings multilinha                      |
| `print()`          | Exibe informações no terminal                    |
| `sep`              | Define o separador entre argumentos do `print()` |
| `\n`               | Representa uma quebra de linha                   |

## 🎯 Objetivo

Aprender diferentes maneiras de **organizar e exibir textos em múltiplas linhas**, utilizando recursos nativos do Python.

---

🐍 **Python — Fundamentos**
