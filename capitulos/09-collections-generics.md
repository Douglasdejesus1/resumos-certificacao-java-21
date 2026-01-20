---
capitulo: 09
titulo: Collections and Generics
tags: [collections]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Trabalhar com coleções, generics e utilitários de coleção.

## 📌 Conceitos Principais
- `List`, `Set`, `Map` e suas implementações.
- Generics: limites (`extends`, `super`), type inference, erasure.
- Métodos utilitários (`Collections`, `List.of`, `Map.of`).

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
