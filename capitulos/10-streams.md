---
capitulo: 10
titulo: Streams
tags: [streams]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Estruturar o estudo de streams com base nos tópicos do sumário.

## 📌 Conceitos Principais
- Returning an Optional
- Using Streams
- Working with Primitive Streams
- Working with Advanced Stream Pipeline Concepts

## 💡 Pontos Importantes para a Prova
- Propriedades de pipeline (sem estado, não interferência).
- Diferença entre `map` e `flatMap`.
- Coletores comuns (`collect`, `toList`, `groupingBy`).

## 🔍 Exemplos de Código
```java
List<String> names = List.of("Ana", "Bruno", "Carla");
var upper = names.stream()
    .filter(n -> n.length() > 3)
    .map(String::toUpperCase)
    .toList();
```

## ✅ Checklist de Estudo
- [ ] Praticar pipelines com `map`, `filter`, `flatMap`.
- [ ] Revisar coletores mais usados.
- [ ] Testar streams paralelas e regras de segurança.

## 🔗 Links e Recursos
- Java SE 21: Stream API
