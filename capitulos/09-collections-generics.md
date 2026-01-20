---
capitulo: 09
titulo: Collections and Generics
tags: [collections]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Seguir o sumário para revisar coleções e generics de forma alinhada ao exame.

## 📌 Conceitos Principais
- Using Common Collection APIs
- Using the List Interface
- Using the Set Interface
- Using the Queue and Deque Interfaces
- Using the Map Interface
- Sorting Data
- Introducing Sequenced Collections
- Reviewing Collection Types
- Working with Generics

## 💡 Pontos Importantes para a Prova
- Diferença entre coleções mutáveis e imutáveis.
- Wildcards em métodos e PECS (Producer Extends, Consumer Super).
- Ordenação com `Comparable` e `Comparator`.

## 🔍 Exemplos de Código
```java
List<? extends Number> numbers = List.of(1, 2L, 3.0);
Comparator<String> byLen = Comparator.comparingInt(String::length);
```

## ✅ Checklist de Estudo
- [ ] Praticar limites superiores e inferiores.
- [ ] Revisar diferenças de performance entre implementações.
- [ ] Implementar comparadores personalizados.

## 🔗 Links e Recursos
- Java SE 21: Collections Framework
