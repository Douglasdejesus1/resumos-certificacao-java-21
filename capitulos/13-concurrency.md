---
capitulo: 13
titulo: Concurrency
tags: [concurrency]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Aplicar APIs de concorrência moderna e clássica.

## 📌 Conceitos Principais
- `Runnable`, `Callable`, `ExecutorService`.
- Sincronização, locks, atomics.
- Virtual threads (Project Loom) e executores por thread.

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
