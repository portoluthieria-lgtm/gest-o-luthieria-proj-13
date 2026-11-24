# Luthieria Pro

Sistema de gestão para oficinas de luthieria e manutenção de instrumentos (sopros, cordas e outros): ordens de serviço, clientes, estoque, financeiro, vendas de instrumentos e acessórios, e relatórios.

## Estrutura

```
luthieria-pro/
├── index.html      página principal
├── css/style.css   visual (tema azul marinho, claro/escuro/auto)
├── js/app.js       toda a lógica do sistema
├── .nojekyll       faz o GitHub Pages servir os arquivos como estão
├── .gitignore
└── README.md
```

## Como publicar no GitHub Pages (grátis)

1. Entre em github.com e crie um repositório novo (ex.: `luthieria-pro`), **público**.
2. Envie o conteúdo desta pasta: em **Add file > Upload files**, arraste `index.html`, `.nojekyll`, `README.md`, `.gitignore` e as pastas `css` e `js`. Clique em **Commit changes**.
3. Vá em **Settings > Pages**. Em **Build and deployment**, escolha **Deploy from a branch**, branch **main** e pasta **/ (root)**, e salve.
4. Aguarde 1 a 2 minutos. O link será `https://SEU-USUARIO.github.io/luthieria-pro/`.

Para atualizar o site depois, envie os arquivos alterados de novo (mesmo nome) e faça outro commit.

## Importante sobre os dados

- Nesta versão os dados (clientes, ordens, financeiro) ficam salvos **no navegador de cada aparelho**. Outro celular ou computador não vê os mesmos dados.
- O login é local (serve para proteger o acesso no mesmo aparelho) e não é segurança de servidor.
- Faça backup com frequência em **Configurações > Dados > Exportar backup**.
- Para acessar os mesmos dados de qualquer lugar, o próximo passo é ligar o sistema a um banco online, como o Supabase, que tem plano gratuito.
- O repositório público mostra o código, mas **nunca** os dados da oficina, que não ficam no GitHub.
