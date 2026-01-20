---
capitulo: 06
titulo: Class Design
tags: [oop]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Reorganizar o estudo de design de classes seguindo o sumário do exame.

## 📌 Conceitos Principais
- Understanding Inheritance
- Creating Classes
- Declaring Constructors
- Initializing Objects
- Inheriting Members
- Creating Abstract Classes
- Creating Immutable Objects

## 💡 Pontos Importantes para a Prova
- Regras de acesso a membros em hierarquias.
- Cadeia de construtores e chamadas a `super()`.
- Contratos de classes seladas e subclasses permitidas.

## 🔍 Exemplos de Código
```java
public sealed class Shape permits Circle, Rectangle {}
public final class Circle extends Shape {}
```

## ✅ Checklist de Estudo
- [ ] Revisar ordem de inicialização (estáticos vs instância).
- [ ] Praticar criação de records e implicações de imutabilidade.
- [ ] Verificar regras de herança com classes seladas.

## 🔗 Links e Recursos
- Java SE 21: Sealed Classes
