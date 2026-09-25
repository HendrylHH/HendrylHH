# Checklist de publicação responsável

[Perfil](../README.md) · [Portfólio](../portfolio/README.md) · [Como adicionar um projeto](ADICIONAR-PROJETO.md)

Este checklist orienta a revisão dos materiais do portfólio. Não é auditoria jurídica, garantia de anonimização ou certificação de conformidade com a LGPD.

## Autoria e autorização

- [ ] Tenho direito de publicar o código, os textos, os recursos visuais e os dados.
- [ ] Não copiei código proprietário, regras confidenciais, documentos ou detalhes identificáveis de operações profissionais.
- [ ] Quando houver dúvida contratual ou de titularidade, mantive o material fora do repositório até esclarecer a autorização.
- [ ] Identifiquei componentes de terceiros e preservei as licenças e atribuições aplicáveis.

## Dados e identificação

- [ ] Os dados de demonstração foram criados para o projeto ou vêm de fonte cuja publicação foi revisada e documentada.
- [ ] Não usei uma base profissional como entrada para gerar uma versão supostamente anônima com IA.
- [ ] Revisei nomes, documentos pessoais, mensagens, valores, datas, identificadores, nomes de clientes e combinações que possam revelar pessoas ou operações.
- [ ] Revisei planilhas, relatórios, imagens, metadados, arquivos de teste, notebooks e resultados de execução.

## Credenciais e ambiente

- [ ] Não há senhas, tokens, cookies, sessões de navegador, certificados privados ou arquivos de configuração reais.
- [ ] Exemplos de configuração contêm apenas placeholders; não apontam para ambientes profissionais.
- [ ] Não publiquei bancos locais, backups, logs reais, catálogos de memória, índices vetoriais ou traces de aplicações profissionais.
- [ ] Revisei os arquivos efetivamente rastreados e o diff, e não apenas as regras do `.gitignore`.

## Documentação e resultados

- [ ] Screenshots e demonstrações vêm de um ambiente preparado para publicação.
- [ ] Funcionalidades planejadas estão separadas das implementadas.
- [ ] Resultados identificam origem, configuração e metodologia; métricas de trabalho não foram atribuídas ao projeto demonstrativo.
- [ ] A documentação informa o que foi testado, o que não foi executado e as limitações conhecidas.

## Se algo sensível já foi enviado

Interrompa novos envios e acione o responsável pelo material. Credenciais expostas exigem revogação ou rotação; removê-las do arquivo não resolve a exposição. A revisão deve considerar histórico, cópias e artefatos, não apenas o estado atual do repositório.

Referências operacionais: [remoção de dados sensíveis no GitHub](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository) e [verificação de segredos](https://docs.github.com/en/code-security/secret-scanning/introduction/about-secret-scanning).

Nenhum controle descrito neste documento deve ser considerado habilitado automaticamente. O `.gitignore` adicionado é uma medida preventiva limitada, não um scanner de dados pessoais ou segredos.
