---
capitulo: 13
titulo: Concurrency
tags: [concurrency]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Estruturar o estudo de concorrência segundo os tópicos do sumário.

## 📌 Conceitos Principais
- Introducing Threads
- Creating Threads with the Concurrency API
- Writing Thread-Safe Code
- Using Concurrent Collections
- Identifying Threading Problems
- Working with Parallel Streams

## 💡 Pontos Importantes para a Prova
- Ciclo de vida de `ExecutorService` (submit, shutdown).
- Riscos de deadlock e starvation.
- Quando usar virtual threads vs platform threads.

## 🔍 Exemplos de Código
```java
try (var executor = Executors.newVirtualThreadPerTaskExecutor()) {
    Future<Integer> sum = executor.submit(() -> 1 + 2);
    System.out.println(sum.get());
}
```

## ✅ Checklist de Estudo
- [ ] Revisar sincronização e coleções concorrentes.
- [ ] Praticar uso de `CompletableFuture`.
- [ ] Experimentar virtual threads.

## 🔗 Links e Recursos
- Java SE 21: Concurrency
