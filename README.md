# landing-page-rachi
Landing Page Rachi - Desafios Codelândia

[<img src="./\src\imagens/tela-readme.gif">](https://vandesonsantos.github.io/landing-page-rachi/)

## Tecnologias Utilizadas
- HTML
- CSS
- JS

## Quer utiliar a animação usada no projeto?
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
