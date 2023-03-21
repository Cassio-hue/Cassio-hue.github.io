---
layout: post
title: Padrões de Commits
---

Padrões de commits ajudam a manter o repositório organizado e otimizar o tempo de leitura dos commits na revisão do código ou busca por alguma modificação específica.

## Como é a estrutura da mensagem do commit

```
<tipo>(escopo opcional): <descrição>

[corpo opcional]

[rodapé(s) opcional(is)]
```

### Tipos:
Os tipos são a descrição inicial para explicarem o que aquele comit está fazendo no código.

- feat: adições de novas funcionalidades ao software em desenvolvimento;
- test: adição ou modificação de testes;
- fix: resolução de bugs ou erros no código;
- docs: adições ou modificações que alteram documentações;  
- refactor: modificações no código que não alteram regras de negócio ou funcionamento de uma funcionalidade;
- style: formatações no código como espaços em branco, aspas simples, indentação do código e semelhantes;
- build: mudanças que afetam a build do sistema ou dependências externas (atualizações de bibliotecas);


## Referência
[Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)