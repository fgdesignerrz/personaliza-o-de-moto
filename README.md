# Configurador GRIFFT Gráficos

Configurador visual de kits de adesivos para motos de trilha / motocross — cores por camada,
nome e número do piloto, fontes, logos e templates, com envio do orçamento direto no WhatsApp.

## Conteúdo

- `index.html` — a aplicação completa, num único arquivo (HTML + CSS + JS + fontes + SVGs embutidos).
  Não precisa de servidor, build nem instalação.
- `.nojekyll` — evita que o GitHub Pages processe os arquivos.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `configurador-grifft`).
2. Envie **todo o conteúdo desta pasta** para a raiz do repositório
   (pelo site: *Add file → Upload files*, arraste `index.html` e `.nojekyll`).
3. No repositório: **Settings → Pages**.
4. Em *Source*, escolha **Deploy from a branch**; branch `main`, pasta `/ (root)`. Salve.
5. Em 1–2 minutos o configurador estará em
   `https://SEU-USUARIO.github.io/configurador-grifft/`.

Para usar num domínio próprio, adicione um arquivo `CNAME` com o domínio e aponte o DNS
conforme a documentação do GitHub Pages.

## Uso local

Abra `index.html` com dois cliques em qualquer navegador — funciona offline.

## Observações

- O gráfico gerado é **ilustrativo**: a arte final é refinada pelo designer. O aviso já aparece na tela.
- O botão de WhatsApp abre a conversa com a mensagem pronta (41 99582-5119). No celular as imagens
  vão junto; no computador elas são baixadas para você anexar.
- Para trocar o número do WhatsApp, a moto ou os templates, edite o projeto de origem e gere
  um novo `index.html` — o arquivo publicado é compilado.
