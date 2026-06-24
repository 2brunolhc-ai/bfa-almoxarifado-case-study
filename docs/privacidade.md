# Privacidade e segurança

O BFA Almoxarifado foi desenvolvido sobre um contexto operacional real. Por isso, o repositório público deve apresentar somente documentação, estudo de caso e imagens tratadas.

## Não publicar

- Código-fonte privado do sistema principal
- Arquivos `.env` ou variações
- URLs, chaves ou tokens do Supabase
- Dados reais de banco
- Backups, dumps ou arquivos `.db`/`.sqlite`
- Notas fiscais, PDFs e planilhas reais
- Nomes reais de obras, empresas, fornecedores, funcionários ou usuários
- Prints com informações internas
- Binários, instaladores ou artefatos internos de deploy

## Publicar apenas

- Descrição técnica do projeto
- Funcionalidades em linguagem geral
- Arquitetura resumida
- Tecnologias utilizadas
- Aprendizados
- Prints com dados fictícios e revisados

## Recomendação

Se algum segredo já tiver sido commitado no histórico de um repositório, apague a chave no provedor, gere uma nova e mantenha o repositório privado. Remover o arquivo atual não remove o conteúdo do histórico Git.
