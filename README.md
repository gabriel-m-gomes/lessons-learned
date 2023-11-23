### Descrição

Este projeto foi desenvolvido durante o período de Curso da Trybe 🚀

O projeto tem por objetivo a avaliação e prática dos conhecimentos adquiridos na Trybe, visando o cumprimento do requisitos solicitados pela mesma.

### ATENÇÃO: Para utilizar a aplicação acesse o link no canto direito em "About".

---

## SUMÁRIO

- [Habilidades](#habilidades-requeridas)
  - [O que foi desenvolvido](#o-que-foi-desenvolvido)
  - [Tecnologias usadas](#tecnologias-usadas)
  - [Antes de inicializar a página na máquina local](#antes-de-inicializar-a-página-na-máquina-local)
  - [Instruções de desenvolvimento](#instruções-de-desenvolvimento)
    - [Como desenvolver](#como-desenvolver)
      - [Linter](#linter)
      - [Avaliador Automático](#avaliador-automático)
    - [Requisitos](#requisitos)
      - [Dicas](#dicas)
      - [Lista de requisitos](#lista-de-requisitos)
        - [1. Adicione uma cor de fundo específica para a página](#1-adicione-uma-cor-de-fundo-específica-para-a-página)
        - [2. Adicione uma barra superior com um título](#2-adicione-uma-barra-superior-com-um-título)
        - [3. Adicione uma foto sua à página](#3-adicione-uma-foto-sua-à-página)
        - [4. Adicione uma lista de lições aprendidas à página](#4-adicione-uma-lista-de-lições-aprendidas-à-página)
        - [5. Crie uma lista de lições que ainda deseja aprender para a página](#5-crie-uma-lista-de-lições-que-ainda-deseja-aprender-para-a-página)
        - [6. Adicione um rodapé para a página](#6-adicione-um-rodapé-para-a-página)
        - [7. Insira pelo menos um link externo na página](#7-insira-pelo-menos-um-link-externo-na-página)
        - [8. Crie um artigo sobre seu aprendizado](#8-crie-um-artigo-sobre-seu-aprendizado)
        - [9. Crie uma seção que conta uma passagem sobre seu aprendizado](#9-crie-uma-seção-que-conta-uma-passagem-sobre-seu-aprendizado)
        - [10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles](#10-aplique-elementos-html-de-acordo-com-o-sentido-e-propósito-de-cada-um-deles)
      - [Bônus](#bônus)
        - [11. Teste a semântica da sua página está aprovada pelo site CodeSniffer](#11-teste-a-semântica-da-sua-página-está-aprovada-pelo-site-codesniffer)
        - [12. Adicione uma tabela à página](#12-adicione-uma-tabela-à-página)
        - [13. Utilize o Box model](#13-utilize-o-box-model)
        - [14. Altere atributos relacionados as fontes](#14-altere-atributos-relacionados-as-fontes)
        - [15. Posicione o seu artigo e a seção sobre aprendizados um ao lado do outro](#15-posicione-o-seu-artigo-e-a-seção-sobre-aprendizados-um-ao-lado-do-outro)
  - [Demonstração do Projeto](#demonstração-do-projeto)

## Habilidades requeridas

* Utilizar _HTML_ para construir páginas WEB.
* Utilizar _HTML_ semântico para tornar sua página mais acessível e melhor ranqueada.
* Utilizar _CSS_ para adicionar estilo e posicionar elementos.

---

## O que foi desenvolvido

Foi desenvolvido um site básico, que contém uma série de informações sobre o que eu aprendi aqui na Trybe ao longo dos últimos 3 blocos iniciais do curso.

O site está com os elementos posicionados e estilizados, além de conter a semântica apropriada para que seja acessível e melhor ranqueado.

## Tecnologias usadas

- `HTML`, `CSS`

---

### Antes de inicializar a página na máquina local

1. Clone o repositório
  * `git clone git@github.com:THIAGOMARTINS367/Trybe-project-lessons-learned.git`
  * Entre na pasta do repositório na sua máquina:
    * `cd Trybe-project-lessons-learned`

2. Instale as dependências usando seu terminal
   * `npm install`

3.  Inicialize o projeto
    * Utilize uma extenção do VsCode (Live Server) ou inicie um servidor local para rodar o projeto em sua máquina.

--- 

### Instruções de desenvolvimento 

* Faça `commits` das alterações que você fizer no código regularmente

* Lembre-se de sempre após um (ou alguns) `commits` atualizar o repositório remoto

* Os comandos que você utilizará com mais frequência são:
  1. `git status` _(para verificar o que está em vermelho - fora do stage - e o que está em verde - no stage)_
  2. `git add` _(para adicionar arquivos ao stage do Git)_
  3. `git commit` _(para criar um commit com os arquivos que estão no stage do Git)_
  5. `git push -u nome-da-branch` _(para enviar o commit para o repositório remoto na primeira vez que fizer o `push` de uma nova branch)_
  4. `git push` _(para enviar o commit para o repositório remoto após o passo anterior)_

---

## Como desenvolver

### Linter

Para garantir a qualidade do seu código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento nós utilizamos neste projeto o linter `ESLint`. Para rodar o linter localmente no seu projeto, execute o comando abaixo:

```bash
npm run lint:styles
```

⚠ **NESTE PROJETO O STYLELINT NÃO SERÁ AVALIADO. VOCÊ PODE RODAR O TESTE LOCALMENTE E FAZER AS CORREÇÕES SE DESEJAR!** ⚠

Após clonar o projeto, você deverá criar os arquivos **index.html** e **style.css** que conterão seu código HTML e CSS, respectivamente. Observe que seus arquivos **devem** possuir estes nomes para que seu projeto seja testado corretamente pelo avaliador automático.

Você é livre para adicionar outros arquivos se julgar necessário.

Lembre-se que sua página deverá conter semântica adequada e para isso verifique se sua página está aprovada no [CodeSniffer](https://squizlabs.github.io/HTML_CodeSniffer/).


### Avaliador automático

* Os requisitos do seu projeto são avaliados automaticamente, sendo utilizada a resolução de tela de `1366 x 768` (1366 pixels de largura por 768 pixels de altura).

* ⚠️ Recomenda-se desenvolver seu projeto usando a mesma resolução, via instalação [deste plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) do `Chrome` para facilitar a configuração da resolução. ⚠️

* Atente-se para o tamanho das imagens que você utilizará neste projeto. **Não utilize imagens com um tamanho maior que _500Kb_.**

* ⚠️ Utilize uma ferramenta [como esta](https://picresize.com/pt) para redimensionar as imagens. ⚠️

* Caso a avaliação falhe com alguma mensagem de erro parecida com `[409:0326/130838.878602:FATAL:memory.cc(22)] Out of memory. size=4194304`, provavelmente as imagens que você está utilizando estão muito grandes. Tente redimensiona-las para um tamanho menor.

Para verificar se a sua avaliação foi computada com sucesso, você pode verificar os **detalhes da execução do avaliador**.

* Na página do seu _Pull Request_, acima do "botão de merge", procure por _**"Evaluator job"**_ e clique no link _**"Details"**_;

* Na página que se abrirá, procure pela linha _**"Cypress evaluator step"**_ e clique nela;

* Analise os resultados a partir da mensagem _**"(Run Starting)"**_;

* Caso tenha dúvidas, consulte [este vídeo](https://vimeo.com/420861252) ou procure as pessoas instrutoras.

Para rodar o avaliador automático localmente no seu projeto, execute um dos comandos abaixo:

```bash
npm test
```

***ou***

```bash
npm run cypress:open
```

Após executar o comando acima, será aberta uma janela de navegador e então basta clicar no nome do arquivo de teste que quiser executar (*project.spec.js*, ou *bonus.spec.js*), ou para executar todos os testes clique em *Run 2 integration specs*

Você tem liberdade para adicionar novos comportamentos ao seu projeto, seja na forma de aperfeiçoamentos em requisitos propostos ou novas funcionalidades, **desde que tais comportamentos adicionais não conflitem com os requisitos propostos**.

* Você pode fazer mais do que for pedido, mas nunca menos.

* **Nada além do que for pedido nos requisitos será avaliado**. _Esta é uma oportunidade de você exercitar sua criatividade e experimentar com os conhecimentos adquiridos._

---

## Requisitos

### Dicas

Para fazer este projeto você deverá atribuir a barra superior o `position: fixed;`.

### Lista de requisitos

⚠️ Leia-os atentamente e siga à risca o que for pedido. Em particular, **atente-se para os nomes de _ids_ que alguns elementos de seu projeto devem possuir**. ⚠️

O não cumprimento de um requisito, total ou parcialmente, impactará em sua avaliação.

---

### 👀Observações importantes:

* Lembrem-se que como pessoas desenvolvedoras devemos fazer pesquisas e garimpar resultados para auxiliar no entendimento do assunto. Assim, para solucionar os requisitos do projeto é inevitável e estimulado que pesquisas sejam feitas nas mais variadas fontes (course, vídeos do course, google, youtube, etc) sempre tomando cuidado para utilizar fontes "confiáveis" nas pesquisas da Internet, como por exemplo:
  
  * [Javascript.com](http://javascript.com/)
  
  * [W3Schools](https://www.w3schools.com/js/default.asp)
  
  * [MDN](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
  
  * [StackOverflow](https://pt.stackoverflow.com/questions/tagged/javascript)
  

### 1. Adicione uma cor de fundo específica para a página

Possuir cor de fundo: rgb(253, 251, 251)

**O que será verificado:**

- Possuir cor de fundo: rgb(253, 251, 251)

### 2. Adicione uma barra superior com um título

A barra deve possuir o ID "cabecalho" e deve ser fixa no topo da página com a propriedade top tendo **0**. O título deve estar dentro da barra e ser um elemento **h1** com ID "titulo".

**O que será verificado:**

- A barra possui o ID "cabecalho"
- A barra superior deve ser fixa no topo da página, com a propriedade top tendo o valor `0`
- O título deve estar dentro da barra e possuir o ID "titulo", além de ser uma tag "h1"

### 3. Adicione uma foto sua à página

A foto deve ser inserida utilizando uma tag **img** com o ID "minha_foto".

**O que será verificado:**

- A foto deve ser inserida utilizando uma tag img com o ID "minha_foto"

### 4. Adicione uma lista de lições aprendidas à página

A lista deve possuir **10** itens, ser numerada e possuir o ID "licoes_aprendidas".

**O que será verificado:**

- A lista deve ser numerada e possuir o ID "licoes_aprendidas"
- A lista deve possuir 10 itens

### 5. Crie uma lista de lições que ainda deseja aprender para a página

A lista deve possuir **10** itens, não ser numerada e possuir o ID "licoes_a_aprender".

**O que será verificado:**

- A lista não deve ser numerada e deve possuir o ID "licoes_a_aprender"
- A lista deve possuir 10 itens

### 6. Adicione um rodapé para a página

O rodapé deve utilizar a tag **footer** e possuir o ID "rodape".

**O que será verificado:**

- O rodapé deve possuir o ID "rodape"

### 7. Insira pelo menos um link externo na página

A configuração desse link deve ser feita para abrir em uma nova aba do navegador

**O que será verificado:**

- A configuração desse link deve ser feita para abrir em uma nova aba do navegador

### 8. Crie um artigo sobre seu aprendizado

O artigo deverá possuir mais de 300 **caracteres** e menos de 600, além disto deve possuir a tag **article**.

**O que será verificado:**

- A `tag` `article` devem ser utilizadas
- O artigo deve ter mais de 300 caracteres e menos de 600

### 9. Crie uma seção que conta uma passagem sobre seu aprendizado

A seção deverá possuir mais de 100 **caracteres** e menos de 300, além disto deve possuir a tag **aside**.

**O que será verificado:**

- A `tag` `aside` deve ser utilizada
- A seção deve ter mais que 100 caracteres e menos que 300

### 10. Aplique elementos HTML de acordo com o sentido e propósito de cada um deles

Para tornar o seu site mais acessível e melhorar seu ranqueamento em mecanismos de busca na Web, sua página deve conter os seguintes elementos: article, header, nav, section, aside e footer.

**O que será verificado:**

- Validar se a página possui um elemento "article"
- Validar se a página possui um elemento "header"
- Validar se a página possui um elemento "nav"
- Validar se a página possui um elemento "section"
- Validar se a página possui um elemento "aside"
- Validar se a página possui um elemento "footer"

### 11. Teste a semântica da sua página está aprovada pelo site CodeSniffer

Teste a semântica da sua página está aprovada pelo site CodeSniffer

**O que será verificado:**

- Seu site deve passar sem problemas na verificação de semântica do site CodeSniffer

### BÔNUS

### 12. Adicione uma tabela à página

**O que será verificado:**

- A página deve possuir uma tabela

### 13. Utilize o Box model

Altere **margin**, **padding** e **border** dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes.

**O que será verificado:**

- Altere `margin`, `padding` e `border` dos elementos para ver, na prática, como esses atributos influenciam e melhoram a visualização dos componentes

### 14. Altere atributos relacionados as fontes
Modifique o estilo da sua tipografia alterando o tamanho de letra, a cor, o espaçamento entre as linhas e a **font-family**.

**O que será verificado:**

- Altere o tamanho da letra
- Altere a cor da letra
- Altere o espaçamento entre as linhas
- Altere o `font-family`

### 15. Posicione o seu artigo e a seção sobre aprendizados um ao lado do outro

Adicione ao elemento posicionado no lado esquerdo a classe "lado-esquerdo" e ao elemento posicionado no lado direito a classe "lado-direito"

**O que será verificado:**

- Utilizar a classe "lado-esquerdo"
- Utilizar a classe "lado-direito"
- Verificar se os elementos com as classes lado-direito e lado-esquerdo estão posicionados corretamente

---

## Demonstração do Projeto

### *Em produção*...
