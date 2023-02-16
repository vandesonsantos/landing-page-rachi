# Landing-Page-Rachi
Landing Page Rachi - Desafios Codelândia

[<img src="./\src\imagens/tela02-readme.gif">](https://vandesonsantos.github.io/landing-page-rachi/)

## Tecnologias Utilizadas
- HTML
- CSS
- JS

## Quer Utilizar o Script Usado No Projeto?
```
const titulo = document.querySelector('[data-titulo]')

function escrita() {
    tituloArray = titulo.innerHTML.split('')
    titulo.innerHTML = ''

    tituloArray.forEach((letra, i) => {
        setTimeout(() => {
            titulo.innerHTML += letra
        }, i * 75)
    })
}

escrita();
```

## Deploy Do Projeto
- [GitHub Pages](https://vandesonsantos.github.io/landing-page-rachi/)



**Divirta-se!** 🚀
