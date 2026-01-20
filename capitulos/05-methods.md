---
capitulo: 05
titulo: Methods
tags: [fundamentos]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Escrever e invocar métodos com assinaturas corretas.

## 📌 Conceitos Principais
- Assinatura, sobrecarga e varargs.
- Passagem por valor de referências.
- Encapsulamento e visibilidade.

## 💡 Pontos Importantes para a Prova
- Regras de resolução de sobrecarga com varargs.
- Imutabilidade de parâmetros vs mutabilidade de objetos.
- Métodos estáticos vs de instância.

## 🔍 Exemplos de Código
```java
static int sum(int... nums) {
    return Arrays.stream(nums).sum();
}
```

## ✅ Checklist de Estudo
- [ ] Exercitar sobrecarga com tipos primitivos e wrappers.
- [ ] Revisar modificadores de acesso.
- [ ] Entender bem varargs e ambiguidade.

## 🔗 Links e Recursos
- Java SE 21: Methods
