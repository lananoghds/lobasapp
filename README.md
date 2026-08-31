# Lobas Fit

MVP do app **Lobas Fit** em React + Vite, preparado para GitHub → Netlify e instalação como PWA.

## O que existe neste pacote

- Código-fonte React + Vite
- Home
- Treinos
- Progresso
- Perfil
- Hábitos interativos
- Navegação mobile
- Manifest e Service Worker para PWA
- Configuração do Netlify
- Identidade visual completa em PNG
- Logos e elementos gráficos separados em `public/brand/`
- Guia de identidade em `BRAND_GUIDE.md`

## Identidade visual

Abra a pasta:

`public/brand/`

O arquivo principal de referência é:

`public/brand/identidade-completa-atual.png`

Os logos, ícones, paleta, tipografia e elementos gráficos também estão separados nessa pasta.

## Rodar no computador

```bash
npm install
npm run dev
```

## Subir no GitHub

1. Extraia este ZIP.
2. Crie um novo repositório no GitHub.
3. Envie **todo o conteúdo da pasta `lobas-fit-app`**, mantendo `src`, `public`, `package.json` e `netlify.toml` na raiz do repositório.
4. Faça o commit na branch `main`.

## Publicar no Netlify

1. Entre no Netlify.
2. Escolha a opção para adicionar/importar um novo projeto.
3. Selecione GitHub como provedor Git.
4. Autorize o Netlify a acessar o repositório, se solicitado.
5. Selecione o repositório do Lobas Fit.
6. Confira as configurações:
   - Build command: `npm run build`
   - Publish directory: `dist`
7. Faça o deploy.

O arquivo `netlify.toml` já inclui a configuração de build e o redirect necessário para a SPA.

## Instalar no celular

Depois que estiver publicado em HTTPS no Netlify:

- iPhone/Safari: Compartilhar → Adicionar à Tela de Início
- Android/Chrome: Menu → Adicionar à tela inicial / Instalar app

## Mensagens da marca

- **Treine como uma loba.**
- **A sua melhor fase começa em você.**
