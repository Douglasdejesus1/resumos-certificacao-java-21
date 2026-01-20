---
capitulo: 04
titulo: Core APIs
tags: [apis]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Seguir o sumário para revisar APIs centrais e suas operações-chave.

## 📌 Conceitos Principais
- Creating and Manipulating Strings
- Using the StringBuilder Class
- Understanding Equality
- Understanding Arrays
- Calculating with Math APIs
- Working with Dates and Times

## 💡 Pontos Importantes para a Prova
- Operações que criam novas instâncias vs mutáveis.
- Pitfalls de formatação e parsing de datas.
- Comparações de arrays vs listas.

## 🔍 Exemplos de Código
```java
var date = LocalDate.of(2024, 1, 1);
var next = date.plusDays(30);
var formatted = next.format(DateTimeFormatter.ISO_DATE);
```

## ✅ Checklist de Estudo
- [ ] Revisar métodos principais de `String` e `StringBuilder`.
- [ ] Praticar criação e formatação de datas.
- [ ] Relembrar diferenças entre arrays e coleções.

## 🔗 Links e Recursos
- Java SE 21: java.base API
