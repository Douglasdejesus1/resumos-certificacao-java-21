---
capitulo: 11
titulo: Exceptions and Localization
tags: [exceptions]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Tratar exceções e aplicar recursos de localização.

## 📌 Conceitos Principais
- Hierarquia de exceções (`Exception`, `RuntimeException`, `Error`).
- `try-with-resources` e `AutoCloseable`.
- `Locale`, `ResourceBundle`, formatação com `NumberFormat` e `DateTimeFormatter`.

## 💡 Pontos Importantes para a Prova
- Ordem de `catch` e unreachable code.
- Fechamento automático de recursos e supressed exceptions.
- Resolução de bundles e fallback de locale.

## 🔍 Exemplos de Código
```java
try (var reader = Files.newBufferedReader(Path.of("data.txt"))) {
    return reader.readLine();
} catch (IOException e) {
    throw new UncheckedIOException(e);
}
```

## ✅ Checklist de Estudo
- [ ] Revisar checked vs unchecked.
- [ ] Praticar mensagens localizadas com `ResourceBundle`.
- [ ] Simular try-with-resources aninhados.

## 🔗 Links e Recursos
- Java SE 21: Exceptions e Localization
