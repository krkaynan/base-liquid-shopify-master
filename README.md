# base-liquid-shopify-master

> Tema base em **Liquid** para Shopify — ponto de partida avançado e modular criado por **Kaynan Raikkonen**.  
> Email: `raikkonenkaynan@gmail.com`

---

<!-- TOC -->
## Sumário
- [Visão geral](#visão-geral)
- [Badges](#badges)
- [Recursos principais](#recursos-principais)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Pré-requisitos](#pré-requisitos)
- [Instalação & Quick Start](#instalação--quick-start)
- [Fluxo de desenvolvimento local](#fluxo-de-desenvolvimento-local)
- [Build & Deploy (opções)](#build--deploy-opções)
- [Integração contínua (exemplo GitHub Actions)](#integração-contínua-exemplo-github-actions)
- [Configurações importantes (`config/`)](#configurações-importantes-config)
- [Sections, Snippets e Templates — boas práticas](#sections-snippets-e-templates---boas-práticas)
- [Localização / Tradução](#localização--tradução)
- [Estilo e Assets](#estilo-e-assets)
- [Performance & SEO & Acessibilidade](#performance--seo--acessibilidade)
- [Testes & QA](#testes--qa)
- [Dicas de troubleshooting comuns](#dicas-de-troubleshooting-comuns)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Changelog resumido](#changelog-resumido)
- [Contato](#contato)
<!-- /TOC -->

---

## Visão geral
`base-liquid-shopify-master` é uma base robusta de tema em Liquid pensada para acelerar desenvolvimento de lojas Shopify (Online Store 2.0). Fornece estrutura mínima necessária (layout, sections, snippets, templates, config, locales, assets) e convenções para facilitar extensões e deploy em workflows reais.

---

## Badges
> (adicione estes badges no GitHub conforme desejar — aqui apenas sugestão textual)
- Build: `GitHub Actions`
- License: `MIT`
- Issues: `Good first issue`
- Shopify CLI: `Requer Shopify CLI v3+`

---

## Recursos principais
- Arquitetura modular (sections + snippets)
- Compatível com JSON templates do Online Store 2.0
- Estrutura preparada para internacionalização (PT-BR)
- Configurações via `config/settings_schema.json`
- Exemplo de fluxo para desenvolvimento local com `shopify theme dev` / `shopify theme serve`
- Regras de formatação via `.editorconfig` e `.prettierrc`

---

## Estrutura do projeto (conforme enviado)
