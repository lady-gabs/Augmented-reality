# Augmented Reality (AR)
Projeto realizado por: Caio de Assis Ribeiro, Diogo Paiva Pereira, Gabriella Alves de Oliveira, Lênin Machado Cruz Ribeiro<br/>
Disciplina: Computação Gráfica - 2023<br/>
Curso: Ciências da Computação<br/>
Unesp - Rio Claro<br/><br/>
## Biblioteca Utilizada:

Para a construção do programa utilizei a biblioteca [A-frame](https://aframe.io/) que é usada para aplicações de Realidade Aumentada (AR) e Realidade Virtual (VR). 
Ela não precisa ser instalada, basta inclui-la na tag `<head>` do seu arquivo HTML.
#### Aframe:
![A-frame](https://img.shields.io/static/v1?label=version&message=1.4.0&color=ff69b4)
![A-frame](https://img.shields.io/static/v1?label=release-date&message=Dec-2022&color=ff69b4)
## Sobre o programa:
Neste projeto busquei desenvolver um programa que utilizasse a câmera do computador/celular e que, por meio de marcadores, exibisse na tela o conteúdo de cada marcador.<br/>
Tendo isso em vista, na pasta :file_folder:**assets** está contido os marcadores (na pasta `markers`) e as mídias que serão exibidas na tela (pastas `video` e `image`). Na pasta 
`markers` há as subpastas **patt** (que contém um marcador personalizado que criei em formato `.patt`) e **png** (que possui os marcadores em formato `.png` usados no projeto - estes arquivos servem para impressão em folha branca).

## Primitivas / Tag's Aframe:
`<a-scene>`: cria a cena que consiste no objeto raiz global o qual contém todas as entidades;
<br/>`<a-assets>`: preloading de conteúdos que serão usados no programa;
<br/>`<a-entity>`: representa a entidade o qual possui espaço reservado no sistema para conectamos componentes a fim de fornecer aparência, comportamento e funcionalidade;
<br/>`<a-marker>`: primitiva que procura uma imagem que tem um tipo de padrão estabelecido no código e direciona para o objeto que será exibido com tal padrão;
<br/>`<a-image>`: exibe imagem em uma superfície plana ;
<br/>`<a-cone>`: projeta a forma de um cone;
<br/>`<a-video>`: exibe vídeo como uma textura em uma superfície plana.
