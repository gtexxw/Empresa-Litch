# Litch

Litch é um protótipo fictício de plataforma digital voltada ao universo dos jogos. O projeto reúne descoberta de títulos, catálogo, ofertas, assinatura e comunidade em uma interface moderna e responsiva.

## Páginas

- `docs/index.html`: página inicial, Game Store, Litch+ e comunidade
- `docs/sobre.html`: apresentação institucional da plataforma
- `docs/help-me.html`: central de ajuda demonstrativa
- `docs/404.html`: página exibida para endereços inexistentes

## Tecnologias

- HTML5
- CSS3
- Google Fonts
- GitHub Actions e GitHub Pages

## Estrutura

```text
Litch-2408/
├── .github/
│   └── workflows/
│       └── pages.yml
├── docs/
│   ├── images/
│   ├── .nojekyll
│   ├── 404.html
│   ├── help-me.html
│   ├── index.html
│   ├── sobre.html
│   └── style.css
├── .gitignore
└── README.md
```

## Executar localmente

Não é necessário instalar dependências. Na pasta do projeto, execute:

```bash
python -m http.server 8000 --directory docs
```

Depois, abra `http://localhost:8000/` no navegador.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie estes arquivos para a branch `main`.
2. No repositório, acesse **Settings → Pages**.
3. Em **Build and deployment**, selecione **GitHub Actions** como fonte.
4. Aguarde o workflow **Deploy to GitHub Pages** terminar.

O workflow publica somente o conteúdo de `docs/` e mantém este README na página principal do repositório. Ele executa automaticamente a cada envio para a branch `main`.

## Autores

Desenvolvido por Gustavo de Toledo Gomes e Lucas Baldan.

## Observação

Este projeto possui finalidade demonstrativa. Nomes, capas e marcas de jogos pertencem aos seus respectivos proprietários e são utilizados apenas para representar visualmente o conceito da plataforma.
