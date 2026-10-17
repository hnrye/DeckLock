# Deck do Caos · Deadlock

Site de uma página só (`index.html`), sem instalar nada e sem backend. Abre direto no navegador com dois cliques.

## Publicar no GitHub Pages (grátis)

1. Crie uma conta no GitHub e um repositório novo, por exemplo `deadlock-cartas`, público.
2. Envie o `index.html` para a raiz do repositório (botão **Add file → Upload files**). Opcional: envie também o `decks.json` (veja abaixo).
3. Vá em **Settings → Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`, e salve.
4. Em cerca de um minuto o site fica em `https://SEU-USUARIO.github.io/deadlock-cartas/`.

Para atualizar o site, basta enviar um `index.html` novo no mesmo lugar.

## Como os dados são guardados

- Tudo o que você edita fica **no navegador de quem usa** (localStorage). Cada pessoa tem o próprio deck, e o que você editar não aparece para os outros.
- Troque de navegador ou de computador levando o arquivo: **Editar decks → Salvar tudo em arquivo** e depois **Carregar arquivo**.

## Deck padrão para todo mundo (opcional)

1. No site, monte seus decks, perfis e verso do jeito que quiser.
2. **Editar decks → Salvar tudo em arquivo**.
3. Renomeie o arquivo baixado para `decks.json` e envie para o repositório, ao lado do `index.html`.

Quem abrir o site pela primeira vez, ou que nunca tenha editado nada, verá o seu conteúdo. Quem já editou continua com os próprios dados. Isso só funciona no site publicado, não ao abrir o arquivo direto do computador.

## Atalhos

Espaço sorteia · 1 a 8 quantidade de cartas · F modo stream · E editor · S configurações · C copiar resultado.
