# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 13/04/2026, 17:27:17
> **119 arquivo(s)** | **~23.881 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── .bugs/
│   └── bug-2026-04-13T20-06-26.md
├── .sk/
│   └── memoria.json
├── api-server/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── src/
│   │   ├── lib/
│   │   │   └── logger.ts
│   │   ├── routes/
│   │   │   ├── ai-chat.ts
│   │   │   ├── exec.ts
│   │   │   ├── github.ts
│   │   │   ├── health.ts
│   │   │   ├── index.ts
│   │   │   ├── proxy.ts
│   │   │   ├── search.ts
│   │   │   └── voice.ts
│   │   ├── app.ts
│   │   └── index.ts
│   ├── build.mjs
│   ├── package.json
│   ├── pty_helper
│   ├── pty_helper.c
│   └── tsconfig.json
├── code-editor/
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── public/
│   │   ├── favicon.svg
│   │   ├── icon-192.png
│   │   ├── icon-512.png
│   │   ├── manifest.json
│   │   ├── opengraph.jpg
│   │   └── sw.js
│   ├── src/
│   │   ├── components/
│   │   │   ├── ui/
│   │   │   │   ├── accordion.tsx
│   │   │   │   ├── alert-dialog.tsx
│   │   │   │   ├── alert.tsx
│   │   │   │   ├── aspect-ratio.tsx
│   │   │   │   ├── avatar.tsx
│   │   │   │   ├── badge.tsx
│   │   │   │   ├── breadcrumb.tsx
│   │   │   │   ├── button-group.tsx
│   │   │   │   ├── button.tsx
│   │   │   │   ├── calendar.tsx
│   │   │   │   ├── card.tsx
│   │   │   │   ├── carousel.tsx
│   │   │   │   ├── chart.tsx
│   │   │   │   ├── checkbox.tsx
│   │   │   │   ├── collapsible.tsx
│   │   │   │   ├── command.tsx
│   │   │   │   ├── context-menu.tsx
│   │   │   │   ├── dialog.tsx
│   │   │   │   ├── drawer.tsx
│   │   │   │   ├── dropdown-menu.tsx
│   │   │   │   ├── empty.tsx
│   │   │   │   ├── field.tsx
│   │   │   │   ├── form.tsx
│   │   │   │   ├── hover-card.tsx
│   │   │   │   ├── input-group.tsx
│   │   │   │   ├── input-otp.tsx
│   │   │   │   ├── input.tsx
│   │   │   │   ├── item.tsx
│   │   │   │   ├── kbd.tsx
│   │   │   │   ├── label.tsx
│   │   │   │   ├── menubar.tsx
│   │   │   │   ├── navigation-menu.tsx
│   │   │   │   ├── pagination.tsx
│   │   │   │   ├── popover.tsx
│   │   │   │   ├── progress.tsx
│   │   │   │   ├── radio-group.tsx
│   │   │   │   ├── resizable.tsx
│   │   │   │   ├── scroll-area.tsx
│   │   │   │   ├── select.tsx
│   │   │   │   ├── separator.tsx
│   │   │   │   ├── sheet.tsx
│   │   │   │   ├── sidebar.tsx
│   │   │   │   ├── skeleton.tsx
│   │   │   │   ├── slider.tsx
│   │   │   │   ├── sonner.tsx
│   │   │   │   ├── spinner.tsx
│   │   │   │   ├── switch.tsx
│   │   │   │   ├── table.tsx
│   │   │   │   ├── tabs.tsx
│   │   │   │   ├── textarea.tsx
│   │   │   │   ├── toast.tsx
│   │   │   │   ├── toaster.tsx
│   │   │   │   ├── toggle-group.tsx
│   │   │   │   ├── toggle.tsx
│   │   │   │   └── tooltip.tsx
│   │   │   ├── AIChat.tsx
│   │   │   ├── AssistenteJuridico.tsx
│   │   │   ├── CampoLivre.tsx
│   │   │   ├── CodeEditor.tsx
│   │   │   ├── EditorLayout.tsx
│   │   │   ├── FileTree.tsx
│   │   │   ├── GitHubPanel.tsx
│   │   │   ├── PackageSearch.tsx
│   │   │   ├── Preview.tsx
│   │   │   ├── QuickPrompt.tsx
│   │   │   ├── RealTerminal.tsx
│   │   │   ├── TemplateSelector.tsx
│   │   │   ├── Terminal.tsx
│   │   │   ├── VoiceCard.tsx
│   │   │   └── VoiceMode.tsx
│   │   ├── hooks/
│   │   │   ├── use-mobile.tsx
│   │   │   └── use-toast.ts
│   │   ├── lib/
│   │   │   ├── ai-service.ts
│   │   │   ├── github-service.ts
│   │   │   ├── projects.ts
│   │   │   ├── store.ts
│   │   │   ├── templates.ts
│   │   │   ├── tts-service.ts
│   │   │   ├── utils.ts
│   │   │   ├── virtual-fs.ts
│   │   │   └── zip-service.ts
│   │   ├── App.tsx
│   │   ├── index.css
│   │   └── main.tsx
│   ├── components.json
│   ├── index.html
│   ├── package.json
│   ├── SYSTEM_DOCS.md
│   ├── tsconfig.json
│   └── vite.config.ts
├── MANUAL.md
├── PLANO.md
└── README.md
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript

---

## ROTAS DA API (endpoints detectados automaticamente)

```
USE    /api  (em api-server/src/app.ts)
POST   /ai/chat  (em api-server/src/routes/ai-chat.ts)
POST   /exec/npm-install  (em api-server/src/routes/exec.ts)
POST   /exec/run-node  (em api-server/src/routes/exec.ts)
POST   /exec/run-node-vfs  (em api-server/src/routes/exec.ts)
POST   /db/query  (em api-server/src/routes/exec.ts)
GET    /github/user  (em api-server/src/routes/github.ts)
GET    /github/repos  (em api-server/src/routes/github.ts)
POST   /github/repos  (em api-server/src/routes/github.ts)
POST   /github/push  (em api-server/src/routes/github.ts)
DELETE /github/repos/:owner/:repo  (em api-server/src/routes/github.ts)
GET    /healthz  (em api-server/src/routes/health.ts)
USE    /voice  (em api-server/src/routes/index.ts)
GET    /search  (em api-server/src/routes/search.ts)
GET    /npm-search  (em api-server/src/routes/search.ts)
POST   /transcribe  (em api-server/src/routes/voice.ts)
POST   /speak  (em api-server/src/routes/voice.ts)
GET    /api/items  (em code-editor/src/lib/templates.ts)
GET    /api/items/:id  (em code-editor/src/lib/templates.ts)
POST   /api/items  (em code-editor/src/lib/templates.ts)
GET    /api/health  (em code-editor/src/lib/templates.ts)
USE    /api/auth  (em code-editor/src/lib/templates.ts)
USE    /api/usuarios  (em code-editor/src/lib/templates.ts)
POST   /register  (em code-editor/src/lib/templates.ts)
POST   /login  (em code-editor/src/lib/templates.ts)
GET    /perfil  (em code-editor/src/lib/templates.ts)
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
LOG_LEVEL=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_BASE_URL=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_API_KEY=seu_valor_aqui
PORT=seu_valor_aqui
ALLOWED_ORIGINS=seu_valor_aqui
JWT_SECRET=seu_valor_aqui
JWT_EXPIRES_IN=seu_valor_aqui
DATABASE_URL=seu_valor_aqui
BASE_PATH=seu_valor_aqui
REPL_ID=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `api-server/src/app.ts` — Ponto de entrada do backend
- `api-server/src/index.ts` — Ponto de entrada do backend
- `api-server/src/routes/index.ts` — Ponto de entrada do backend
- `code-editor/index.html` — Arquivo principal
- `code-editor/src/App.tsx` — Componente raiz do frontend
- `code-editor/src/main.tsx` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`MANUAL.md`** _(151 linhas)_
Manual explicativo em linguagem simples, feito para entender o projeto sem precisar de conhecimento tecnico profundo.

**`PLANO.md`** _(673 linhas)_
Este documento! Gerado automaticamente pelo SK Code Editor com toda a estrutura do projeto.

**`README.md`** _(1 linha)_
Documentacao principal do projeto. Explica o que o projeto faz e como rodar.

---

### 📁 `.bugs/`
> Pasta '.bugs' — agrupamento de arquivos relacionados.

**`bug-2026-04-13T20-06-26.md`** _(27 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

---

### 📁 `.sk/`
> Pasta '.sk' — agrupamento de arquivos relacionados.

**`memoria.json`** _(1 linha)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

---

### 📁 `api-server/`
> Pasta 'api-server' — agrupamento de arquivos relacionados.

**`build.mjs`** _(159 linhas)_
Arquivo MJS — parte do projeto.

**`package.json`** _(39 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`pty_helper`** _(18 linhas)_
Arquivo PTY_HELPER — parte do projeto.

**`pty_helper.c`** _(138 linhas)_
Arquivo C — parte do projeto.

**`tsconfig.json`** _(18 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `code-editor/`
> Pasta 'code-editor' — agrupamento de arquivos relacionados.

**`SYSTEM_DOCS.md`** _(292 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(36 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package.json`** _(92 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.ts`** _(83 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `api-server/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(33 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `api-server/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`app.ts`** _(35 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(185 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `code-editor/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `code-editor/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`icon-192.png`** _(55 linhas)_
Arquivo de imagem.

**`icon-512.png`** _(132 linhas)_
Arquivo de imagem.

**`manifest.json`** _(49 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`opengraph.jpg`** _(63 linhas)_
Arquivo de imagem.

**`sw.js`** _(41 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `code-editor/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(210 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(167 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `api-server/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`logger.ts`** _(21 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `api-server/src/routes/`
> Definicao das URLs e navegacao do app.

**`ai-chat.ts`** _(75 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`exec.ts`** _(206 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(107 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`health.ts`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(21 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`proxy.ts`** _(62 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search.ts`** _(63 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`voice.ts`** _(89 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `code-editor/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(2068 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AssistenteJuridico.tsx`** _(822 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CampoLivre.tsx`** _(499 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CodeEditor.tsx`** _(154 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`EditorLayout.tsx`** _(2434 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`FileTree.tsx`** _(400 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubPanel.tsx`** _(632 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`PackageSearch.tsx`** _(395 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`Preview.tsx`** _(496 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`QuickPrompt.tsx`** _(274 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`RealTerminal.tsx`** _(573 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TemplateSelector.tsx`** _(501 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1516 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VoiceCard.tsx`** _(378 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`VoiceMode.tsx`** _(277 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `code-editor/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `code-editor/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(392 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`github-service.ts`** _(197 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`projects.ts`** _(73 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`store.ts`** _(38 linhas)_
STORE de estado — gerencia o estado global do app (dados compartilhados entre telas).

**`templates.ts`** _(1629 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(294 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`virtual-fs.ts`** _(200 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zip-service.ts`** _(147 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `code-editor/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript
Arquivos: 119 | Linhas: ~23.881
Rotas API: 26 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: LOG_LEVEL, AI_INTEGRATIONS_OPENAI_BASE_URL, AI_INTEGRATIONS_OPENAI_API_KEY, PORT, ALLOWED_ORIGINS, JWT_SECRET, JWT_EXPIRES_IN, DATABASE_URL, BASE_PATH, REPL_ID

Estrutura principal:
  .bugs/bug-2026-04-13T20-06-26.md
  .sk/memoria.json
  MANUAL.md
  PLANO.md
  README.md
  api-server/.replit-artifact/artifact.toml
  api-server/build.mjs
  api-server/package.json
  api-server/pty_helper
  api-server/pty_helper.c
  api-server/src/app.ts
  api-server/src/index.ts
  api-server/src/lib/logger.ts
  api-server/src/routes/ai-chat.ts
  api-server/src/routes/exec.ts
  api-server/src/routes/github.ts
  api-server/src/routes/health.ts
  api-server/src/routes/index.ts
  api-server/src/routes/proxy.ts
  api-server/src/routes/search.ts
  ... e mais 99 arquivo(s)
```

---

*Plano gerado pelo SK Code Editor — 13/04/2026, 17:27:17*