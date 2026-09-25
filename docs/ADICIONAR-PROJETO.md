# Como adicionar um projeto

[Perfil](../README.md) · [Portfólio](../portfolio/README.md) · [Checklist de publicação](PUBLICACAO-SEGURA.md)

## 1. Preparar material publicável

Antes de qualquer envio, revise código, dados, imagens e arquivos auxiliares conforme o checklist. Use uma implementação própria e autorizada para publicação. Não envie arquivos profissionais para depois tentar higienizá-los no repositório público.

## 2. Escolher o local

Laboratórios menores ficam em `portfolio/<area>/<nome-do-projeto>/`. Use nomes em minúsculas, sem espaços ou acentos, com palavras separadas por hífen e orientadas ao problema resolvido.

Por exemplo, `portfolio/bancos-de-dados/otimizacao-de-consultas/` é um caminho sugerido, ainda não criado como projeto.

Aplicações completas podem permanecer em repositórios próprios. Nesse caso, adicione uma descrição curta e um link no README da área. Não copie a implementação apenas para preencher o catálogo.

## 3. Organizar os arquivos

Uma estrutura possível, adaptável à stack:

```text
nome-do-projeto/
├── README.md
├── src/
├── tests/
├── docs/
└── data/
    └── synthetic/
```

Crie apenas diretórios necessários. Dados sintéticos também precisam de origem e método de geração documentados. Não inclua dependências instaladas, ambientes virtuais, credenciais ou artefatos de execução.

## 4. Documentar o código existente

Copie o [modelo de README](../templates/README-PROJETO.md) e preencha a partir da implementação. Remova instruções de preenchimento e seções que não se aplicam. Não invente comandos, testes, métricas, integrações ou funcionalidades.

Caso o código seja adicionado antes da documentação completa, um README curto deve identificar objetivo, estado atual e pendências reais. Não é necessário escrever a versão final para iniciar a organização.

Para solicitar documentação assistida, indique o link ou caminho do projeto e a branch relevante. A revisão deve ler os arquivos, dependências, entradas da aplicação e testes antes de descrever o funcionamento. Testes existentes não devem ser apresentados como aprovados sem execução verificada.

## 5. Atualizar a navegação

Inclua o projeto no README da área e atualize o resumo do portfólio. Acrescente referências em outras áreas quando houver evidência dessas competências, mantendo uma única origem do código. Altere os destaques do perfil somente quando fizer sentido destacar o projeto.

## 6. Conferir antes do commit

Revise o diff completo, execute as verificações disponíveis, confirme os links e confira novamente arquivos sensíveis. Atualize a documentação sempre que a implementação mudar.

Cada projeto precisa declarar sua autoria, dependências e condições de uso aplicáveis. A presença no catálogo não altera a licença de repositórios externos nem concede permissão sobre materiais de terceiros.
