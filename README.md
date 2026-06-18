# Livia Fazolato - Currículo e Portfólio

Mini site estático de currículo e portfólio, criado em HTML, CSS e JavaScript puro, sem frameworks.

## Arquivos

- `index.html`: estrutura semântica do site, metatags SEO/Open Graph e conteúdo bilíngue.
- `styles.css`: layout responsivo, estilos visuais e regras de impressão A4.
- `script.js`: alternância PT/EN, abas e botão `window.print()`.
- `CV_Livia_Fazolato_202606_PT.pdf`: currículo em português para download no site.
- `Resume_Livia_Fazolato_202606_EN.pdf`: resume em inglês para download no site.

## Como rodar localmente

Abra o arquivo `index.html` diretamente no navegador.

Também é possível servir a pasta com qualquer servidor estático, mas isso não é obrigatório.

## Publicar no Vercel via GitHub

1. Crie um repositório no GitHub e envie estes arquivos para a branch principal.
2. Acesse [vercel.com](https://vercel.com) e clique em **Add New Project**.
3. Importe o repositório do GitHub.
4. Em **Framework Preset**, selecione **Other**.
5. Deixe **Build Command** vazio.
6. Deixe **Output Directory** como `.`.
7. Clique em **Deploy**.

## Publicar no Vercel via CLI

Instale e autentique a Vercel CLI:

```bash
npm i -g vercel
vercel login
```

Dentro da pasta do projeto, publique:

```bash
vercel
```

Para publicar em produção:

```bash
vercel --prod
```

## Download, impressão e PDF

O botão de download troca automaticamente conforme o idioma ativo:

- PT: `CV_Livia_Fazolato_202606_PT.pdf`
- EN: `Resume_Livia_Fazolato_202606_EN.pdf`

Use o botão **Imprimir / Salvar PDF** no site. O navegador abrirá a janela de impressão, onde é possível imprimir ou salvar em PDF.

No modo de impressão, a navegação, botões e portfólio ficam ocultos, imprimindo apenas o currículo em formato A4.
