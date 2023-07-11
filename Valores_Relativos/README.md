# <center>PROJETO PARQUES</center>
![parques](img/municipal1.jpg)



## PROJETO & OBJETIVO:

__Tema do estudo__: Parques de Belo Horizonte-Mg;

__Projeto__:  Contém  01 página principal e demais páginas extras;

    Objetivo:  é modificar elementos HTML através do CSS utilizando as seguintes propriedades:
      * Largura (Width) - Min-Width & Max-Width;
      * Altura (Height) Min- Height & Max-Height;
      * Espaçamento Interno (Padding);
      * Margem (Margin);
      * Borda (Border);
      * Overflow - overflow-x e overflow-y;
      * Display - Inline, Block e none;
      * Opacity: Opaco, semi-transparente e Invisível

  __Métodos__:

    * Altura e largura mínima e máxima de um elemento; 
    * Tamanhos relativos;
    * Visibilidade do elemento - Visivel e/ou oculto;
    * Adicionar sombra ao elemento.

 __Pages extras__:

__MinMax:__ aborda a utilização das propriedades min-width e max-width & min-height e max-height;

__Overflow:__ aborda a utilização das propriedades do Overflow.

__display:__ aborda a utilização das propriedade do display, estilizando os elementos  dos links lado a lado.


### Problema estudado:
Após a análise  observou-se que a  página  exibia uma imagem com largura fixa causando os problemas listado abaixo:
img {
    width: 1440px;
}

        Problema: Quebra ao ser exibida em tela menores ganhando uma barra de rolagem na horizontal;
        Solução possiveis que podem ser aplicadas: 
        1 - Largura relativa em percentual para que a imagem tenha sempre o tamanho da tela;

        2 - Utilizar largura mínima e máxima;

        3 - CALC para cálculo de tamanho.

---
## Arquitetura:

<center>Estrutura de Pasta:</center>


    📁 Projeto-Parques Belo Horizonte
    |
    |- 📁 VALORES_RELATIVOS
    |   |
    |   |- 📁 css
    |       |- 📑 style.css
    |       |- 📑 style1.css
    |       |- 📑 style2.css
    |       |- 📑 style3.css
    |       |- 📑 style4.css
    |   |- 📁 img
    |       |- 📑 imagens diversas
    |   |- 📁 pages
    |       |- 📑 display.html
    |       |- 📑 minmax.html
    |       |- 📑 overflow.html
    |
    |- 📑 index.html
    |- 📑 readme.md
  
## Tecnologia:
![](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
![](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)  

---

### Anotações Gerais:
__VALOR RELATIVO__ = É definido com base em outro elemento (elemento pai);


__VALORES PERCENTUAIS__ % tem o mesmo peso de valores em pixel.
Sintaxe: 

__vm__ = é uma medida de valor relativo que se refere a LARGURA da tela, cada 1vw corresponde a 1% da largura da tela.
Sintaxe:

__vh__ = é uma medida de valor relativo que se refere a ALTURA  da tela.
Sintaxe:

__calc__ = faz cálculo utilizando vlaores relativos(%, vw e vh) e fixos.
Sintaxe:

            img {
                width: calc(100vw - 40px);
            }
                           para calculo mais complexos
            img {
                width:  calc(100vw - 30px);
                height: calc((100vw - 40px) / 3);
                margin: calc(3% - 40px);
            }
  OBS: Através de valores relativos e do calc podemos construir visuais mais dinâmicos, capazes de se adaptar aos mais diversos tipos de página e tela sem problemas. O uso de valores relativos é essencial para quem deseja construir páginas que funcionem em uma grande variedade de dispositivos.

  Overflow - garante que o conteúdo respeite as dimensões do elemento. Criando uma barra de rolagem que permite a leitura do texto sem ultrapassar o tamanho.
       .area {
        overflow: scroll;
       }
       ou
       .area {
        overflow: auto; (exibirá barra de rolagem somente se o conteudo ultrapassar o tamanho determindado)
       }

      
       .area {
        overflow-x: scroll; (adiciona uma barra de rolagem horizontal)
       }
       .area {
        overflow-y: scroll; (adiciona uma barra de rolagem vertical)
       }
__OBS:__ estas propriedades podem ser simplificadas através do overflow.

        .area {
        oferflow: auto scroll;
        }
        auto = horizontal
        scroll = vertical
## Contato:

<center><img src="https://gifmania.com.br/wp-content/uploads/2020/12/fala_comigo.gif" width="100px" height="100px"></center>


<widht><a href="https://www.linkedin.com/in/nilva-pires" target="_blank">
<img text-align="left"  src="img/linkedin.png" alt="linkedin" width="40px" height="40px"></a></widht>  

<br>


 <left><a href="mailto:piresnilva@gmail.com" target="_blank">
<img text-align="right" src="img/email.png" alt="e-mail"  width="50px" height="50px"></a>  </left>

<br>  

___

<center>🔸<img src="img/mpnf.png" width="20px" height="20px"> 🔸 Developer 🔸 Nilva Pires🔸 2023</center>
