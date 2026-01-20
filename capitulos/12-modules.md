---
capitulo: 12
titulo: Modules
tags: [modules]
data: YYYY-MM-DD
status: em-andamento
---

## 🎯 Objetivos do Capítulo
- Compreender o sistema de módulos do Java.

## 📌 Conceitos Principais
- Arquivo `module-info.java` e diretivas (`requires`, `exports`, `opens`).
- Caminho de módulos vs caminho de classe.
- Serviços (`provides`, `uses`).

## 💡 Pontos Importantes para a Prova
- Regras de acessibilidade entre módulos.
- Encapsulamento forte e reflexão com `opens`.
- Resolução de dependências e erros comuns.

## 🔍 Exemplos de Código
```java
module academy.finance {
    requires java.base;
    exports academy.finance.api;
}
```

## ✅ Checklist de Estudo
- [ ] Criar módulo simples e compilar com `javac --module-path`.
- [ ] Testar exportações e aberturas de pacotes.
- [ ] Revisar serviços com `provides/uses`.

## 🔗 Links e Recursos
- Java SE 21: Module System
