Fatias de um Domingo — Site de Receitas






Site de receitas artesanais da Ju Fiche — foco em preparo simples, ingredientes frescos e apresentação elegante.

🔗 Produção

Domínio: https://www.jufiche.com.br

Fallback Vercel: ju-fiche.vercel.app

✨ Principais recursos

Página de receitas com descrição curta e lista de ingredientes

Layout responsivo (mobile-first)

Paleta e tipografia pensadas para leitura confortável

🎨 Identidade visual

Fontes sugeridas:

Títulos: Playfair Display

Corpo: Lato

Paleta (hex): #8C39BC (roxo), #E93C77 (magenta), #FF6B1C (laranja), #00B7C3 (azul-piscina), #FCF2E3 (bege), #261E40 (texto principal), #DAA900 (destaque)

🧱 Estrutura (exemplo)
/
├─ public/
│  ├─ favicon.ico
│  └─ images/
├─ styles/
│  └─ main.css
├─ scripts/
│  └─ app.js
├─ index.html
└─ README.md

🛠️ Como rodar localmente
Opção A — Projeto estático (HTML/CSS/JS)

Clone o repo:

git clone https://github.com/SEU-USUARIO/SEU-REPO.git
cd SEU-REPO


Abra o index.html no navegador
ou use alguma extensão “Live Server” no VS Code.

Opção B — Next.js / React

Instale dependências:

npm install


Rode em dev:

npm run dev


Acesse: http://localhost:3000

Se seu projeto for Next.js, ajuste os scripts no package.json conforme necessário.

🚀 Deploy (Vercel)

Conecte o repositório na Vercel: Add New Project → Import from GitHub

A cada git push na branch principal, um deploy é feito automaticamente.

Domínio personalizado:

jufiche.com.br → A para o IP indicado no painel da Vercel

www.jufiche.com.br → CNAME para cname.vercel-dns.com.

Verifique o domínio em: Project → Settings → Domains

📦 Scripts úteis (exemplos)
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  }
}


Remova/ajuste esta seção se o projeto for estático.

🧾 Conteúdo de exemplo (pizza artesanal)
<section class="receita">
  <h2>Pizza Artesanal</h2>
  <p>Pizza feita à mão, massa leve e ingredientes frescos — perfeita para qualquer ocasião.</p>
  <h3>Ingredientes</h3>
  <ul>
    <li>300g de farinha</li>
    <li>5g de fermento biológico seco</li>
    <li>180ml de água</li>
    <li>Sal, azeite e molho de tomate</li>
  </ul>
</section>

🤝 Contribuição

Abra uma issue para sugestões/bugs

Para PRs: crie uma branch a partir de main e descreva claramente as mudanças

🔒 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e adaptar.

📬 Contato

Autoria/Brand: Ju Fiche

Dev/Operação: Carol Ribeiro (Codara)

Site: https://www.jufiche.com.br
