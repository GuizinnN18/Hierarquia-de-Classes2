# 📘 README – Hierarquia de Classes e Polimorfismo em Python

## 📌 Descrição

Este projeto tem como objetivo demonstrar, na prática, a aplicação dos conceitos de **Programação Orientada a Objetos (POO)** em Python, com foco em **herança**, **abstração** e **polimorfismo**.

A implementação utiliza uma classe base abstrata chamada `Animal`, da qual derivam subclasses específicas (`Cachorro`, `Gato` e `Passaro`). Cada uma dessas subclasses implementa comportamentos próprios, evidenciando o uso do polimorfismo.

---

## 🧠 Conceitos Aplicados

### 🔹 Abstração

A classe `Animal` é definida como uma classe abstrata, utilizando a biblioteca `abc`. Ela contém métodos abstratos que devem ser obrigatoriamente implementados pelas subclasses:

* `emitir_som()`
* `mover()`

### 🔹 Herança

As classes `Cachorro`, `Gato` e `Passaro` herdam da classe `Animal`, reutilizando atributos e garantindo uma estrutura organizada.

### 🔹 Polimorfismo

O polimorfismo é aplicado ao permitir que diferentes objetos (Cachorro, Gato, Pássaro) sejam tratados de forma uniforme. A função `mostrar_comportamento()` chama os mesmos métodos para todos os objetos, mas cada um responde de maneira diferente.

---

## ⚙️ Estrutura do Código

* `Animal` (classe abstrata)
* `Cachorro`, `Gato`, `Passaro` (subclasses)
* Função `mostrar_comportamento()` (demonstra polimorfismo)
* Bloco principal (`main`) para execução

---

## ▶️ Como Executar

1. Certifique-se de ter o Python instalado
2. Salve o código em um arquivo, por exemplo: `animais.py`
3. Execute no terminal:

```bash
python animais.py
```

---

## 🧪 Exemplo de Saída

```
Rex diz: Au Au!
Rex está correndo.
------------------------------
Mimi diz: Miau!
Mimi está andando silenciosamente.
------------------------------
Loro diz: Piu Piu!
Loro está voando.
------------------------------
```

---

## ✅ Conclusão

O código demonstra como o uso de herança e polimorfismo contribui para um sistema mais organizado, reutilizável e de fácil manutenção. Além disso, evita o uso excessivo de estruturas condicionais, tornando a solução mais elegante e escalável.

---

