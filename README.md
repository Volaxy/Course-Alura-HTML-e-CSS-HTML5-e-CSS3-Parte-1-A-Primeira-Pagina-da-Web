# HTML5 e CSS3 parte 1: A Primeira Página da Web

Curso da Alura sobre HTML e CSS

URL do curso -> [HTML5 e CSS3 parte 1: A Primeira Página da Web](https://www.alura.com.br/curso-online-html5-css3-primeiros-passos)
![HTML5 e CSS3 parte 1: A Primeira Página da Web](https://www.alura.com.br/assets/api/share/curso-html5-css3-primeiros-passos.png)

## Links Úteis
* [Texto Base](https://caelum-online-public.s3.amazonaws.com/1179-html5-css3/01/texto-base.zip) - Texto base para a criação da primeira página.
* [Sublime Text](https://www.sublimetext.com/) - Editor de código.
* [Atom](https://atom.io/) - Editor de código.
* [Visual Studio Code](https://code.visualstudio.com/) - Editor de código recomendado para HTML e CSS.

## Siglas
*

## Atalhos
* Para envolver um conjunto de texto entre tags:
    * 1º: Selecionar o texto;
    * 2º: Apertar ***F1*** (no caso do Visual Studio Code);
    * 3º: Digitar *Wrap with Abbreviation*;
    * 4º: Apertar ***ENTER***;
    * 5º: Digitar a *tag* que será utilizada para envolver o texto;
    * 6º: Apertar ***ENTER***;
* **`F12`** no navegador para abrir o **Development Tools**.

## 01 - Marcação do Primeiro Texto
* Uma introdução ao HTML e às suas ***tags***.
* Como definir o título e os parágrafos de um texto.
    * Utilizando as *tags* `<h1>` e `<p>`, respectivamente.
* Como dar destaque para algumas informações do texto, deixando-as em **negrito**, utilizando a *tag* `<strong>`.
* Como dar ênfase para algumas informações do texto, deixando-as em *itálico*, utilizando a *tag* `<em>`.

## 02 - Separando o Conteúdo e Informações
* A definir a estrutura básica do HTML.
    * Com a *tag* `DOCTYPE`, definimos qual versão do HTML estamos utilizando.
    * A *tag* **`<html>`**, que marca o conteúdo a ser renderizado no navegador.
        * Dentro desta *tag*, podemos definir a linguagem da página, através da propriedade **lang**.
* Como passar as informações do encoding da nossa página para o navegador, através da *tag* **`<meta>`** e da propriedade charset.
* Como definir o título de uma página, através da *tag* **`<title>`**.
* Como separar as informações que estão sendo passadas para o navegador, utilizando a *tag* **`<head>`**.
* Como separar o conteúdo da página, utilizando a *tag* **`<body>`**.

## 03 - Trabalhando com CSS
* A mexer na apresentação dos textos.
    * No alinhamento deles (`text-align`).
    * No tamanho da fonte (`font-size`).
    * Na cor de fundo (`background`).
    * Na cor do texto (`color`).
* CSS *inline*.
    * Na linha onde temos a nossa *tag*, adicionamos a propriedade do CSS.
* A tag **`<style>`**.
    * Dentro da tag, podemos colocar marcações de CSS referentes aos elementos que temos no nosso HTML.
* A apresentação do CSS com um arquivo externo.
* Como funciona o estilo em cascata do CSS.
* Como importar um arquivo externo de CSS dentro da nossa página HTML.
* Como representar cores no CSS.
    * Através do nome da cor.
    * Através do seu hexadecimal.
    * Através do seu RGB.

## 04 - Estilizando Imagens
* Como reestruturar o nosso código, removendo os CSS *inline* e colocando-os no arquivo CSS externo.
* Como criar um identificador para marcar especificamente um elemento.
    * Como fazer referência a esse identificador no CSS.
* Como adicionar uma imagem à nossa página.
* Como ajustar a altura do elemento, através da propriedade `height`.
* Como ajustar a largura do elemento, através da propriedade `width`.
* Como ajustar o espaçamento interno do elemento, através da propriedade `padding`.
* Como ajustar o espaçamento externo do elemento, através da propriedade `margin`.
* Como se comporta um time de front-end hoje em dia.

## 05 - Listas e Divisões de Conteúdo
* A trabalhar com listas não-ordenadas e listas ordenadas.
    * Para cada um dos itens da lista, utilizamos a *tag* <li>.
* O conceito das **classes** no CSS.
    * Elas servem para marcar itens, que são repetíveis.
* Como referenciar uma classe no CSS.
* Divisões de conteúdo, utilizando a *tag* <div>.
* Os comportamentos ***inline*** e ***block***.

## 06 - Finalizando a Página
* O conceito de cabeçalho da página e como criá-lo.
* Que o cabeçalho da página deve ter mais destaque.
* Que não é recomendado criar estilos usando tags.
    * O ideal é usarmos classes para tudo.