# O  guia estelar de html 🚀 🧑‍🚀

## Regras de nomeação de arquivos html e sua extensão

Para começo de coversa todos os arquivos HTML tem como extensão o **.html**.

- nomeando:

  - Não deve se ter espaço em nome de arquivos HTML.
  - Você pode usar um nome de sua escolha.

- evitando
  - espaçamentos

## O que é o HTML?

HTML quer dizer ***Hypertext Markup Language***.

## Anatomia das tags HTML

Uma tag tem sua abertura e seu fechamento. Após a abertura e antes do fechamento vem o conteudo presente na mesma.

```html
  <h1> conteudo entre a abertura eo fechamento da tag </h1>
```

## Atributo das tags HTML

São informações extras das tags, ou configurações das mesmas.

- Atributos booleanos: atributos sem conteudo.

- Aspas:
  - omissão (Não recomendado);
  - Simples;
  - duplas.

- Atributos Globais mais utilizados (usados por todas as tags HTML):
  - class;
  - contenteditable;
  - data-*;
  - hidden;
  - id;
  - style;
  - tabindex;
  - title.

- Aninhamento de tags:
  - Hierarquia;
  - Fluxo;
  - Posicionamento dos elementos.

## Vamos praticar

Escrever 2 paragrafos, dando ênfase 
e importância para algumas palavras, 
e adicione um link de saiba mais.
  - Use tag para ênfase;
  - Use a tag strong para inportancia;
  - O link, pode levar para o google 

## Caracteres reservados

São palavras/simbolos especiais 
utilizadas no HTML5.

```html
<p>Paragrafo com um emoji &#x1F978;</p>
```

## Anatomia do documento HTML5

```html
<!DOCTYPE html>
<html lang="pt-br">
   <head>
        <meta charset="utf-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>&#x1F5FA; Web HTML5 -  anatomia do documento</title>
   </head>
   <body>
      <h1>Hello World! &#x1F5A5;</h1>
   </body>
</html>
```

## Semântica

- Dar significado;
- Elementos semânticos;

## Listas 

- ordenadas
- não ordenadas

## Citações

Avisar que estamos citando conteudos de terceiros.

## Abreviações

> Essa é uma novidade da HTML5 e que ajuda muito em áreas como a de Tecnologia,
> que usa muitas siglas e abreviações. Sempre que você quiser escrever uma sigla, mas
> deixar claro ao usuário (e aos mecanismos de busca) o significado dela, use a tag
`<abbr>`.
> ***[Prof. Guanabara](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/08%20-%20Formata%C3%A7%C3%A3o%20de%20Textos.pdf)***

## Address

Detalhar contatos pessoais, pode ser de alguem que criou a pagina da web. Usa-se a tag `<address>`.

## Lista de descrição

Listas que descrevem um conjunto de itens marcados pela mesma. Usamos a tag `<dl>`.

```html
<h2>Glossário</h2>

<dl>
      <dt>
          Chrome
      </dt>
      <dd>Browser criado pelo Google. Muito usado atualmente.</dd>
      <dt>HTML</dt>
      <dd>
          Linguagem de marcação de hypertexto usada nas páginas da web.
      </dd>
      <dt>VS Code</dt>
      <dd>Editor de código da Microsoft, muito poderozo para codar bastante.</dd>
      <dt>MacOS</dt>
      <dd>Sistgema operacional dos computadores da apple.</dd>
      <dt>Macbook</dt>
      <dd>Note da apple usado por muitos devs.</dd>
 </dl>
```

## Representação de código

>Nós somos (ou seremos) programadores, e por isso compartilhamos muito código-
>fonte em diversas linguagens. Para isso, existe a tag `<code>` da HTML onde você pode
>delimitar seu código. A principal vantagem no uso dessa tag é a o valor semântico que
>ela representa, indicando ao navegador que se trata de um código de computador.
>Porém, existe também um efeito visual, pois as >letras ficam no modo mono-espaçadas
>(monospace), o que facilita bastante a leitura do código. ***[Prof. Guanabara](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/08%20-%20Formata%C3%A7%C3%A3o%20de%20Textos.pdf)***

`<code>`
    partes genéricas de um código
    
`<pre>`
    blocos de código, pois essa tag mantem espaços en branco
    e recuos que eu colocar no código.     

## Elementos genéricos

>Existem dois elementos genéricos que não têm significado semântico nem produzem nenhum efeito, mas permitem definir secções/blocos e são muito usados com CSS.
>Permitem agrupar conteúdo em unidades lógicas:
> - div (division): quebra o fluxo normal do documento.
> - span: mantém o fluxo normal do conteúdo.
> ***[web.fe.up.pt](https://web.fe.up.pt/~ssn/disciplinas/cdi/css/18.html#:~:text=8.,s%C3%A3o%20muito%20usados%20com%20CSS)***

## Hyperlinks - elementos Âncora

>Os hyperlinks são um dos conceitos mais antigos da história da linguagem
>HTML. Eles permitem que você ligue um ponto a outro na World Wide
>Web. Toda vez que você está acessando um site e clica em um local para
>ir para outra página, outro site ou até para baixar um arquivo, você está
>interagindo com um hyperlink. ***[Prof. Guanabara](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/10%20-%20Liga%C3%A7%C3%B5es%20em%20toda%20parte.pdf)***

- hyperlink -  elementos Âncora: `<a>`
    - Anatomia  
    - Atributos
      - global
      - href
        - para onde iremos, quando clicamos no link?
          - url completa
          - email
          - telefone
          - e outros
      - download
      - target
        - _self
        - _blank

## URL e caminho de arquivos

- *[URL]: Uniform Resource Locator
  - https://google.com
  - sequencia de textos que define onde algo esta localizado na web
- URL usam caminhos para encontrar arquivos

- **Caminho de arquivos** 
  - Onde no explorador de arquivos, um recurso está localizado  
  
## Como navegar pelos caminhos?

- mesmo diretório (nome do file)
- entrando em diretórios (subpasta/)
- saindo do diretório (../starter-html/)
- diretório raiz (root ou pai)

## URLs absolutas vs relativas
- Absolutos
  - inclui todo o protocolo e nome de domínio
     - https://app.rocketseat.com.br/node/o-guia-estelar-de-html/
     - Sempre apontará para o mesmo local, pois é absoluto   
- Relativos
  - relativo a página aberta no momento
  - apontará para lugares diferentes  

## Vamos praticar (projeto de hyperlink)

Crie uma pasta por nome "html-simples-projeto" no lugar de sua preferência, contendo 3 páginas, sendo elas:
 - index.html (página principal)
   - coloque um menu na página, contendo o seginte
     - nav  
       - ul 
         - li (3x)
           - a
   - Crie um titulo `<h1>` como o nome "Home Page"
   - Adicione um parágrafo `<p>`, contendo um pequeno texto
- contacts.html
   - coloque um menu na página, contendo o seginte
     - nav  
       - ul 
         - li (3x)
           - a
   - Utilize a tag `<address>` contendo:
      - uma tag `<h2>` com seu nome
      - um paragrafo com um link `<a href="mailto:....">` com seu email
      - um paragrafo com um link `<a href="tel:....">` com seu telefone
- images.html
  - coloque um menu na página, contendo o seginte
    - nav  
      - ul 
        - li (3x)
          - a  
  - Crie um titulo `<h1>` como o nome "Minhas imagens"
  - crie dois parágrafo com uma tag `<img src="..." alt="..." />` cada

- Para utilizart as imagens vá no site [unsplash](https://source.unsplash.com) e baixe 2 imagens de sua escolha.

- Dentro da pasta do seu projeto crie outra pasta chamada "assets" com mais uma pasta chamada de "img", salve nesta as imagens baixadas por você.

- Lembre-se de linkar todas as páginas (index, contacts, images)!

## Tabelas
 
Prós
  - Visualização de dados via linhas e colunas
  - Boa acessibilidade para leitura de dados

Contras
  - Pouco flexivel
  - precisa de estilização para melhor visualização

**🛑 Não usar 🛑**
  - Para criar layout

## Head mais a fundo

- `<head>`
   - possui um titulo para a guia do navegador `<title></title>`
   - possui as meta tags como: 
     - `<meta charset="UTF-8">` caracteres especiais
     - `<meta name="viewport" content="width=device-width, initial-scale=1.0" >` portabilidade para disp. móveis
  - `<link>` para icones personalizados 

## Se preocupando com SEO

SEO (SEARCH ENGINE OPTMIZATION = MOTORES DE BUSCA = GOOGLE)

```html
<meta name="author" content="João Theodoro" />
<meta name="description" content="Usando a head"> 
<meta name="robots" content="noindex, follow">
```

## Open Graph

```html
 <!-- Open Graph: facebook -->
<meta name="og:image" content="http://tny.im/goh" />
 <meta name="og:description" content="lorem ipsum" />
 <meta name="og:title" content="The Rock" />
```