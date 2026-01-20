---
capitulo: 06
titulo: Class Design
tags: [oop]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Modelar classes com herança, composição e encapsulamento adequados.

## 📌 Conceitos Principais
- Herança, `super`, construtores e ordem de inicialização.
- Classes seladas (`sealed`), finais e abstratas.
- Records e quando usá-los.

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
