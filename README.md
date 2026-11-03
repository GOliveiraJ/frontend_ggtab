# 🇧🇷 GGTAB / ANVISA — Plataforma Front-end (Next.js)

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

Repositório exclusivo da camada de interface (Front-end) da plataforma de fiscalização sanitária da **GGTAB/ANVISA**. Arquitetura construída em **Next.js 16 (App Router)** e **Tailwind CSS**, focada em altíssima performance para dispositivos móveis (Mobile-First / PWA Ready).

---

## 🎯 Funcionalidades Principais

- **📊 BI Executivo (SVG Vetorial):** Gráficos de rosca (Donut) e rankings horizontais de empresas e produtos autuados, renderizados nativamente no React sem bibliotecas pesadas.
- **📱 Câmera Integrada (`capture="environment"`):** O fiscal pode acionar a câmera nativa do smartphone diretamente pelo navegador web para registrar infrações e ler CNPJs (via OCR no back-end).
- **📋 Formulários de Fiscalização em Cascata:** Mapeamento inteligente de categorias de infrações (DEF, Tabaco, Propaganda, Apreensão) e busca automática do portfólio oficial.
- **📁 Edição de Histórico em Tempo Real:** Permite ao fiscal adicionar lojas ou remover produtos de operações já finalizadas antes de baixar o Auto de Inspeção em PDF.

---

## 🚀 Como Executar Localmente

### 1. Pré-requisitos
- Node.js (v18+)
- Ter a API do **Back-end em FastAPI** (Python) rodando localmente na porta `8000`.

### 2. Instalação
Clone este repositório e instale as dependências:
```bash
npm install
npm install lucide-react