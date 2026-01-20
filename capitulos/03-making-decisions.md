---
capitulo: 03
titulo: Making Decisions
tags: [fundamentos]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Reorganizar os tópicos de decisão segundo o sumário oficial e praticar fluxos de controle.

## 📌 Conceitos Principais
- Creating Decision-Making Statements
- Building switch Statements and Expressions
- Writing while Loops
- Constructing for Loops
- Controlling Flow with Branching

## 💡 Pontos Importantes para a Prova
- Regras de compatibilidade de tipos em `switch`.
- Diferença entre `switch` statement e expression.
- Exigência de `default` ou completude exaustiva.

## 🔍 Exemplos de Código
```java
String role = "admin";
int level = switch (role) {
    case "admin" -> 3;
    case "power" -> 2;
    case "user" -> 1;
    default -> 0;
};
```

## ✅ Checklist de Estudo
- [ ] Praticar `switch` expression com `yield`.
- [ ] Revisar regras de fall-through em `switch` statement tradicional.
- [ ] Exercitar validação de escopo em blocos.

## 🔗 Links e Recursos
- Java SE 21: switch expressions
