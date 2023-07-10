# <center>PROJETO PARQUES</center>
![parques](img/municipal1.jpg)



## PROJETO & OBJETIVO:

__Tema do estudo__: Parques de Belo Horizonte-Mg;

__Projeto__:  Contém uma única página;

    Objetivo:  é modificar elementos HTML através do CSS utilizando as seguintes propriedades:
      * Largura (Width);
      * Altura (Height);
      * Espaçamento Interno (Padding);
      * Margem (Margin);
      * Borda (Border)

  __Métodos__:

    * Altura e largura mínima e máxima de um elemento; 
    * Tamanhos relativos;
    * Visibilidade do elemento - Visivel e/ou oculto;
    * Adicionar sombra ao elemento.

 

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
    |   |- 📁 img
    |       |- 📑 imagens diversas
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
