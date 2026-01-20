---
capitulo: 11
titulo: Exceptions and Localization
tags: [exceptions]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Alinhar o estudo de exceções e localização aos itens do sumário.

## 📌 Conceitos Principais
- Understanding Exceptions
- Recognizing Exception Classes
- Handling Exceptions
- Automating Resource Management
- Formatting Values
- Supporting Internationalization and Localization
- Loading Properties with Resource Bundles

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
