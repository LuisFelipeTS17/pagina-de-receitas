# Pagina de Receitas

Projeto simples de uma pagina de receita (cupcake de cafe com chantilly), feito com HTML e CSS para praticar estrutura, layout e box model.

## Tecnologias

- HTML5
- CSS3

## O que foi praticado neste projeto

- Estrutura semantica com `main`, `section`, `h1`, `h2`, `p` e `ul`.
- Centralizacao de layout com container (`#page`) e `margin: auto`.
- Uso de `box-sizing: border-box` e impacto no calculo de largura.
- Diferenca entre `max-width: 100%` (limita) e `width: 100%` (forca ocupacao).
- Comportamento de imagem com `display: block`.
- Relacao entre `padding` no `#page` e no `main`.
- Ajuste da estrutura HTML para separar melhor os blocos e evitar deslocamento visual da imagem.

## Estrutura do projeto

```text
.
|-- index.html
|-- style.css
`-- assets/
    |-- bg-image.png
    |-- heart.svg
    |-- main-image.png
    `-- Thumbnail.jpg
```

## Como executar localmente

1. Baixe ou clone este repositorio.
2. Abra o arquivo `index.html` no navegador.

## Como publicar no GitHub

1. Inicie o git no projeto (se ainda nao iniciou):

```bash
git init
```

2. Adicione os arquivos:

```bash
git add .
```

3. Crie o commit inicial:

```bash
git commit -m "feat: adiciona pagina de receitas"
```

4. Crie um repositorio no GitHub e copie a URL.
5. Conecte o repositorio local ao remoto:

```bash
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

6. Envie para o GitHub:

```bash
git branch -M main
git push -u origin main
```

## Autor

Projeto desenvolvido por voce como pratica de HTML e CSS.
