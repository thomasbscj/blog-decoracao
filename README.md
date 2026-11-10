# Casa & Estilo — Blog de Decoração

Trabalho da disciplina **Programação Web - Frontend** — Universidade de Vila Velha (UVV), Ciência da Computação.

**Aluno:** Thomás Lima Braga — matrícula 202634701
**Professor:** Fabrício Ribeiro Ferreira

## Sobre

Blog estático sobre decoração de interiores, desenvolvido apenas com **HTML5 semântico e CSS3**, sem frameworks e sem JavaScript.

## Páginas

| Página | Arquivo | Conteúdo |
| --- | --- | --- |
| Home | `index.html` | Resumo do blog e os três conteúdos de destaque (imagens clicáveis) |
| Estilos | `estilos.html` | Minimalista, boho, industrial e escandinavo |
| Ambientes | `ambientes.html` | Sala, quarto, cozinha e home office |
| Tendências | `tendencias.html` | Cores, materiais naturais, iluminação e paredes-galeria |
| Contatos | `contatos.html` | Formulário, canais de contato e perguntas frequentes |

O elemento `<nav>` com os cinco itens de navegação é repetido em todas as páginas.

## Estrutura

```
.
├── index.html
├── estilos.html
├── ambientes.html
├── tendencias.html
├── contatos.html
├── css/style.css
├── assets/img/        fotografias (Unsplash)
├── assets/favicon.svg
└── entrega/           documento de entrega em PDF (padrão ABNT)
```

## Como executar localmente

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

Ou simplesmente abra o arquivo `index.html` no navegador.

## Publicação

O site está publicado via **GitHub Pages** a partir da branch `main`.

## Créditos das imagens

Fotografias do banco de imagens gratuito [Unsplash](https://unsplash.com), utilizadas sob a licença Unsplash para fins acadêmicos.
