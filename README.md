# Automação Financeira — Interface Web

Frontend desenvolvido com **Next.js e React** para operar um fluxo de processamento e validação de arquivos por meio de uma API.

## Problema e solução

Scripts de extração e conferência precisam de uma interface que permita ao operador iniciar processos e acompanhar suas etapas. Esta aplicação fornece a camada visual da automação financeira.

## Componentes e funcionalidades identificados

- Tela principal com componente de automação financeira.
- Ações de processamento por chamadas ao backend.
- Estrutura de autenticação e sessão.
- Rota de encaminhamento das solicitações à API.
- Componentes React para interação e apresentação de operações.

O fluxo documentado para a solução inclui organização, extração, consolidação e validação de relatórios. Essas etapas são executadas ou apoiadas pelos módulos de backend.

## Tecnologias

**Next.js 14 · React 18 · JavaScript/TypeScript · Material UI · NextAuth**

A interface está organizada nos diretórios `app/` e `components/`.

**API associada:** [Automação Financeira — Backend](https://github.com/rodri-oliveira/automacao-financeira-api).  
**Versão desktop relacionada:** [Automação Financeira — Desktop](https://github.com/rodri-oliveira/automacao-financeira-desktop).

## Execução local

```bash
npm install
npm run dev
```

Por padrão, o ambiente de desenvolvimento é acessado em `http://localhost:3000`.

**Pré-requisitos para demonstração:** API de processamento, autenticação configurada e arquivos de exemplo. A interface depende desses componentes para executar o fluxo completo.

## Competências demonstradas

Integração frontend/backend, construção de interfaces operacionais e organização de fluxos de processamento.

**Status:** interface documentada; demonstração integral depende dos serviços associados.
