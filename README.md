<p align="center">
  <img src="./assets/screenshots/dashboard-preview.svg" alt="Preview visual do BFA Almoxarifado" width="100%" />
</p>

<h1 align="center">BFA Almoxarifado - Sistema Full Stack para Gestão de Materiais</h1>

<p align="center">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-Supabase-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="PWA" src="https://img.shields.io/badge/PWA-ready-5A0FC8?style=for-the-badge" />
  <img alt="Electron" src="https://img.shields.io/badge/Electron-desktop-47848F?style=for-the-badge&logo=electron&logoColor=white" />
</p>

Sistema desenvolvido para controle de materiais e processos de almoxarifado na construção civil, com foco em estoque, entradas, saídas, requisições, ferramentas, notas fiscais, relatórios e automações.

## Visão rápida

| Item | Detalhe |
| --- | --- |
| Tipo | Sistema web/full stack com apoio desktop |
| Domínio | Almoxarifado, estoque, ferramentas e notas fiscais |
| Banco | PostgreSQL/Supabase |
| Automação | OCR, leitura de PDFs e agente Electron |
| Privacidade | Código-fonte principal privado |
| Repositório | Estudo de caso público, sem dados reais |

## Sobre o projeto

O BFA Almoxarifado é um sistema full stack criado para organizar processos operacionais de almoxarifado em obras. O projeto centraliza registros de materiais, requisições, ferramentas, notas fiscais e relatórios em uma aplicação web responsiva, com apoio de banco PostgreSQL/Supabase e agente desktop local com Electron.

Este repositório público é um estudo de caso profissional. O código-fonte principal permanece privado por conter dados, regras internas e integrações sensíveis.

## Problema que o sistema resolve

Em operações de almoxarifado, muitas informações acabam espalhadas em planilhas, mensagens, arquivos PDF e controles manuais. Isso dificulta acompanhar estoque, registrar entradas e saídas, controlar ferramentas, localizar notas fiscais e gerar relatórios confiáveis.

O sistema foi desenvolvido para reduzir retrabalho, melhorar rastreabilidade e tornar os processos mais rápidos e organizados.

## Principais funcionalidades

| Estoque e obras | Processos | Automação e dados |
| --- | --- | --- |
| Controle de estoque | Requisições internas | Leitura de PDFs/OCR |
| Entrada de materiais | Controle de ferramentas | Dashboard |
| Saída de materiais | Empréstimos/devoluções | Relatórios |
| Controle por obra | Notas fiscais | Backup e recuperação |
| PWA responsivo | Agente desktop Electron | PostgreSQL/Supabase |

## Tecnologias utilizadas

| Camada | Tecnologias |
| --- | --- |
| Front-end | HTML5, CSS3, JavaScript, PWA |
| Back-end | Node.js, Express.js, REST API |
| Banco de dados | PostgreSQL, Supabase |
| Desktop | Electron |
| Automação | OCR com Tesseract.js, leitura de PDFs com PDF.js |
| Arquivos e relatórios | SheetJS/XLSX, geração e leitura de documentos |
| Deploy | Render, Vercel, Railway |
| Versionamento | Git, GitHub |

## Arquitetura geral

```mermaid
flowchart TD
  A["Usuário no navegador/PWA"] --> B["Front-end web"]
  B --> C["API Node.js/Express"]
  C --> D["PostgreSQL/Supabase"]
  C --> E["Serviços de backup e recuperação"]
  F["Agente desktop Electron"] --> C
  F --> G["Leitura local de PDFs/OCR"]
  C --> H["Relatórios e exportações"]
```

## Módulos do sistema

- **Estoque:** cadastro, consulta e movimentação de materiais.
- **Entradas:** registro de recebimentos e atualização de saldo.
- **Saídas:** baixa de materiais vinculada a solicitações internas.
- **Requisições:** criação, acompanhamento e histórico de pedidos.
- **Ferramentas:** controle de empréstimos, devoluções e disponibilidade.
- **Notas fiscais:** apoio à leitura, organização e consulta de PDFs.
- **Dashboard:** visão resumida de indicadores operacionais.
- **Backup:** rotinas de exportação, recuperação e validação de dados.
- **Agente desktop:** integração local para automações com Electron.

## Diferenciais técnicos

- Sistema construído a partir de um problema real de operação.
- Integração entre aplicação web, API, banco de dados e agente desktop.
- Uso de OCR e leitura de PDFs para reduzir tarefas manuais.
- Estrutura com rotinas de backup, restauração e validação.
- Aplicação responsiva com suporte a uso como PWA.
- Evolução incremental com versionamento e documentação técnica.

## Demonstração visual

O preview no topo é um mockup público com dados fictícios. Prints reais só devem ser adicionados depois de tratados, sem nomes reais de obras, empresas, fornecedores, usuários, notas fiscais ou informações internas.

## Status do projeto

Projeto privado em evolução, utilizado como base de aprendizado prático em desenvolvimento full stack, automação, banco de dados e organização de processos.

## Observação de privacidade

Este projeto possui código-fonte privado por conter informações internas, dados operacionais e integrações sensíveis. Este repositório apresenta apenas a documentação técnica, estudo de caso, funcionalidades, tecnologias utilizadas e demonstrações visuais sem dados reais.

## O que aprendi desenvolvendo o projeto

- Estruturar uma aplicação full stack com front-end, back-end e banco de dados.
- Criar APIs REST para processos reais de estoque, requisições e ferramentas.
- Trabalhar com persistência, migração e recuperação de dados.
- Integrar PostgreSQL/Supabase em um sistema operacional.
- Automatizar leitura de documentos com OCR e processamento de PDFs.
- Pensar em privacidade, segurança e separação entre código privado e apresentação pública.
- Documentar um projeto real de forma clara para portfólio e recrutadores.
