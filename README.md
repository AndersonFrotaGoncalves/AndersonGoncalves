# Landing page — Anderson Frota, Desenvolvedor Web

Site estático (HTML, CSS e JS puros — sem framework, sem build).

## Estrutura

```
site/
├── index.html        página principal
├── css/
│   └── styles.css    todo o visual do site
├── js/
│   └── main.js        animação de entrada dos cards de projeto
├── assets/            pasta vazia — coloque aqui screenshots dos projetos, se quiser trocar os ícones por imagens reais
└── README.md
```

## Antes de publicar, troque:

1. **WhatsApp e e-mail** — em `index.html`, procure por `wa.me/5500000000000` e `contato@andersonfrota.dev` e troque pelos seus reais (aparecem em 2 lugares: no botão do hero e na seção de contato final).
2. **Novos projetos** — dentro de `index.html`, procure o comentário:
   `<!-- Para adicionar um novo projeto... -->`
   Copie um bloco `<div class="vitrine">...</div>` inteiro (de qualquer projeto existente), cole antes ou depois desse comentário, e troque título, descrição, tags e o link `href`.
3. **Projetos com link genérico** — "Site Institucional — Agência", "Conversor de Moedas" e "Jogo em JavaScript" ainda apontam pra `andersonfrota.netlify.app`. Troque pelo link real de cada um quando tiver.

## Como publicar (Netlify — grátis)

1. Acesse [app.netlify.com](https://app.netlify.com) e crie uma conta (ou entre na já existente).
2. Na tela inicial, arraste a pasta `site` inteira para a área de deploy manual ("Deploy manually" / "drag and drop").
3. Pronto — a Netlify gera um link tipo `nome-aleatorio.netlify.app`. Você pode trocar esse nome nas configurações do site.
4. Se quiser um domínio próprio (ex: andersonfrota.dev), configure em Site settings → Domain management.

## Como testar localmente

Não precisa de servidor — é só abrir o arquivo `index.html` direto no navegador (duplo clique) que já funciona.
