# DOM 
- Document Object Model 
- Estrutura de um arquivo na web
- Representa docuemntos HtML e XML
- Interface de programação
- Não é uma linguagem de programação 
- É essencial para o JS entender o modelo de paginas web

## Para que serve?
- Alterar a estrutura 
- Alterar conteúdo
- Alterar o estilo 

## Como?
- Disponibilizando API (aplication programing interface)
- Rotinas e padrões estabelecidos 
- Métodos (funções)
- Árvore de elementos 
- Seletores 
- Objetos (nós / nodes)

## Exemplo html 
```
<html>
    <head></head>
    <body></body>
</html>
```

## Exemplo obj
```
Objeto = {
    html : {
        head : {}
        body : {
            h1 :{

            }
        }
    }
}
```
## DOM x JS
- O DOM pode ser usado por outras linguagens
- Sem o DOM o JS não teria moção da página

### Vantagem de usar JavaScript 
- Código é executado por navegadores
- Tornar as páginas dinâmicas 
- Evitar Requisições desnecessárias (performance)
- Reagir rapidamente a ações dos usuários

### Desvantagens de usar JavaScript
- Código é executado por navegadores 
- O conteúdo não fica visível para indexadores de busca 
- Alterações em tempo de execução não ficam salvas no documento

### Exemplos 
Seleciona o objeto e disponibiliza (métodos / funções).callback
- document.getEkementById(id)
- document.getEkementByTagName('div')
- document.createElement('div')
- parentNode.appendChild(node) // ex: html.appendChild('body')
- element.innerHTML
- element.style
- element.setAttribute()
- element.getAttribute()
- element.addEventListener()
- window.location
- window.onload (en-US)
- console.log()
- window.scrollTo()

### Referências 
- DOM: https://dom.spec.whatwg.org/
- tecnologias JS: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/JavaScript_technologies_overview
- Motores de execuço: https://pt.wikipedia.org/wiki/lista_de_motores_de_renderiza%C3%A7%C3%A3o