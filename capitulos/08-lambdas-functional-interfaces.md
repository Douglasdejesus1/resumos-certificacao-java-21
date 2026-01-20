---
capitulo: 08
titulo: Lambdas and Functional Interfaces
tags: [functional]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Aplicar lambdas, method references e interfaces funcionais.

## 📌 Conceitos Principais
- Sintaxe de lambdas e escopo.
- Interfaces funcionais da API (`Predicate`, `Function`, etc.).
- Method references e constructors references.

## 💡 Pontos Importantes para a Prova
- Regras de efetivamente final em lambdas.
- Compatibilidade de assinaturas com tipos genéricos.
- Diferença entre captura de variáveis e shadowing.

## 🔍 Exemplos de Código
```java
Predicate<String> nonEmpty = s -> s != null && !s.isBlank();
Function<String, Integer> len = String::length;
```

## ✅ Checklist de Estudo
- [ ] Revisar `java.util.function` principal.
- [ ] Praticar method references equivalentes a lambdas.
- [ ] Verificar inferência de tipos em contextos diferentes.

## 🔗 Links e Recursos
- Java SE 21: Functional Interfaces
