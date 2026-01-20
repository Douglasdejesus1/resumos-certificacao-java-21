---
capitulo: 07
titulo: Beyond Classes
tags: [oop]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Entender interfaces, enumerações e nested classes.

## 📌 Conceitos Principais
- Interfaces, métodos default e static.
- Enums com campos e métodos.
- Classes internas, locais e anônimas.

## 💡 Pontos Importantes para a Prova
- Regras de implementação múltipla de interfaces.
- Enum com construtores privados e constantes especializadas.
- Captura de variáveis efetivamente finais em classes internas.

## 🔍 Exemplos de Código
```java
enum Priority { LOW, MEDIUM, HIGH }

interface Task { default boolean isHigh() { return priority() == Priority.HIGH; } Priority priority(); }
```

## ✅ Checklist de Estudo
- [ ] Praticar default methods e conflitos de herança.
- [ ] Revisar usos de classes internas.
- [ ] Exercitar enums com comportamento.

## 🔗 Links e Recursos
- Java SE 21: Enums e Interfaces
