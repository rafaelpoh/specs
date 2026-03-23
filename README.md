# Specs & Instruções de Desenvolvimento

Este repositório contém as especificações técnicas, padrões de projeto e diretrizes de desenvolvimento utilizadas em meus projetos pessoais e profissionais. Ele foi estruturado como parte de uma entrega para a **DIO (Digital Innovation One)**, consolidando as melhores práticas para o desenvolvimento de aplicações Web e Extensões de Navegador.

## 🚀 Objetivo

Centralizar as "regras do jogo" para garantir que tanto desenvolvedores humanos quanto assistentes de IA (como o Gemini/Jarvis) produzam código limpo, seguro e performático, seguindo uma arquitetura consistente.

## 📁 Estrutura do Repositório

O repositório está organizado nos seguintes arquivos principais:

### 🤖 [gems-instrucoes.md](./gems-instrucoes.md)
Define a persona **Jarvis**, um Product Owner e Arquiteto de Software. Contém instruções detalhadas de como a IA deve se comportar, diagnosticar lacunas em requisitos e estruturar o documento final de especificações (`AGENTS.MD`).

### 🌐 [spec.md](./spec.md)
Conjunto de regras fundamentais para o desenvolvimento de **Aplicações Web e Sites**. 
- **Stack:** JavaScript Vanilla (ES6+), HTML5 Semântico e CSS3.
- **Destaques:** Proibição de frameworks pesados, foco em acessibilidade (A11y), segurança contra XSS e performance via DOM Caching.

### 🧩 [ext.md](./ext.md)
Especificações exclusivas para o desenvolvimento de **Extensões de Navegador (Manifest V3)**.
- **Estrutura:** Define a organização de diretórios para popups, background scripts e content scripts.
- **Comunicação:** Padrões para troca de mensagens entre componentes da extensão.

## 🛠️ Como Utilizar

Estas specs são projetadas para serem fornecidas como contexto inicial em conversas com IAs generativas. Ao carregar estes arquivos, o assistente passará a seguir rigorosamente os padrões de:
1. **Clean Code:** Nomenclatura camelCase, princípio DRY e modularização.
2. **Segurança:** Uso obrigatório de `textContent` em vez de `innerHTML`.
3. **Estilização:** Sistema de tokens via variáveis CSS (`var.css`).
4. **Estrutura:** Organização de arquivos padronizada.

---
*Repositório mantido como referência técnica para evolução contínua.*
