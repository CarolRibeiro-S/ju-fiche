# Ju Fiche — novo site (Direção Criativa para Marcas Artesanais)

Site estático, HTML5 + CSS3 puro, sem framework, sem build tool, sem JS — mesma stack do projeto original. Pronto para GitHub Pages, Netlify ou qualquer hospedagem estática.

## Como substituir o projeto atual no seu repositório

1. Na sua pasta local do projeto, apague todo o conteúdo antigo (`index.html`, `receitas.html`, `dia-de-pizza.html`, `torta-de-frango.html`, `redes-sociais.html`, `style.css` e os 4 PNGs soltos na raiz).
2. Copie os arquivos desta pasta para o lugar deles.
3. `git add -A && git commit -m "Reformula site: de blog de receitas para Ju Fiche - Direção Criativa" && git push`

## O que foi criado

- `index.html` — Home (hero + apresentação + estatuto "qualidade sem percepção de valor")
- `sobre.html` — Sobre a Ju Fiche + "Em que eu acredito"
- `servicos.html` — "Como eu posso te ajudar" (observo / organizo / direciono / acompanho / conecto)
- `contato.html` — WhatsApp, site, Instagram, e-mail
- `style.css` — sistema visual compartilhado por todas as páginas

## Pendências para você/Juh revisarem antes de publicar

- **Bio em `sobre.html`**: o parágrafo de apresentação é um rascunho (marcado com comentário `TODO` no HTML) — a Juh precisa confirmar/reescrever com a história real dela.
- **Instagram**: mantive `@jufichehs` (o mesmo do site de receitas). Confirmem se é esse handle mesmo para a nova frente de negócio ou se ela quer outro.
- **WhatsApp/e-mail**: usei os mesmos números/e-mail que apareciam no material de referência que a Juh mandou — confirmem se são os definitivos.
- **Rodapé**: agora traz colunas de contato, navegação, aviso de direitos autorais e crédito "Site criado e desenvolvido por Carol Ribeiro" (linkado para carolribeiros.com.br). Usei © (direitos autorais padrão), não ® — a marca "Ju Fiche" registrada no INPI é a da confeitaria (classe 30); se quiserem reivindicar marca registrada também para essa frente de consultoria, isso precisa de registro próprio antes de usar ®.

## Sistema visual (para referência futura)

- Cores: `--cream #f6ead9`, `--magenta #9c1359` (tom real extraído da logo oficial), `--orange #e8823c`, `--ink #2c2016`
- Tipografia: Fraunces (títulos), Jost (corpo/menu), Caveat (frases manuscritas tipo "Vamos conversar?")
- Logo: `assets/logo.png` — arquivo enviado pela Juh, recortado, ampliado e com nitidez realçada; fundo transparente, pronta para header e rodapé
- Favicon: `assets/favicon.ico` + PNGs em `assets/` — monograma "JF" recortado das letras reais da logo, sobre fundo em cantos arredondados na cor `--magenta`. Já referenciado via `<link rel="icon">` no `<head>` das 4 páginas.
- Assinatura visual: blob ondulado rosa/laranja + post-its inclinados no painel decorativo do hero — ecoam o moodboard que a Juh mandou.
