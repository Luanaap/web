# NLW Agents

Este projeto foi desenvolvido durante o evento NLW da Rocketseat.

## Tecnologias e Bibliotecas Utilizadas

- **React 19** — Biblioteca principal para construção da interface.
- **Vite** — Ferramenta de build e desenvolvimento rápido.
- **TypeScript** — Tipagem estática para JavaScript.
- **React Router DOM** — Gerenciamento de rotas SPA.
- **@tanstack/react-query** — Gerenciamento de dados assíncronos e cache.
- **Tailwind CSS** — Utilitário para estilização rápida e responsiva.
- **@radix-ui/react-slot** — Composição avançada de componentes.
- **class-variance-authority, clsx, tailwind-merge** — Utilitários para composição de classes CSS.
- **lucide-react** — Ícones SVG.
- **tw-animate-css** — Animações utilitárias.
- **Biome** — Linter e formatter de código.

## Padrões de Projeto e Arquitetura

- **Componentização**: Interface dividida em componentes reutilizáveis.
- **Hooks**: Uso de hooks do React e React Query para lógica de estado e dados.
- **Provider Pattern**: Providers para contexto global (ex: QueryClientProvider).
- **Alias de paths**: Utilização de aliases (`@/`) para facilitar imports.
- **Roteamento SPA**: Estrutura de rotas com React Router.

## Setup e Configuração

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repo>
   cd web
   ```
2. **Instale as dependências:**
   ```bash
   npm install
   # ou
   yarn install
   ```
3. **Rode o projeto em modo desenvolvimento:**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```
4. **Build de produção:**
   ```bash
   npm run build
   # ou
   yarn build
   ```

## Observações

- Certifique-se de ter o Node.js instalado (recomendado versão 18+).
- O projeto utiliza configurações de lint e formatação automáticas com Biome.
- As configurações de estilização estão em `src/index.css` e utilizam Tailwind CSS.
- Os aliases de importação estão definidos em `tsconfig.json` e `vite.config.ts`.

---

Projeto desenvolvido durante o evento NLW da Rocketseat.
