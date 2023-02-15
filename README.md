# landing-page-rachi
Landing Page Rachi - Desafios Codelândia

[<img src="./\src\imagens/tela02-readme.gif">](https://vandesonsantos.github.io/landing-page-rachi/)

## Tecnologias Utilizadas
- HTML
- CSS
- JS

## Quer utiliar o script usado no projeto?
```
function escrita(tag) {
    tituloArray = tag.innerHTML.split('')
    tag.innerHTML = ''

    tituloArray.forEach((letra, i) => {
        setTimeout(() => {
            tag.innerHTML += letra
        }, i * 75)
    })
}

const titulo = document.querySelector('[data-titulo]')

escrita(titulo);
```

## Deploy Do Projeto
- [GitHub Pages](https://vandesonsantos.github.io/landing-page-rachi/)



**Divirta-se!** 🚀
