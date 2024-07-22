# Tripleten web_project_homeland
O projeto "De Pátria para Pátria" exibido na galeria de arte Tripletein é uma jornada visual que conecta diferentes localidades ao redor do mundo, ilustrando a diversidade cultural e histórica de cada lugar. O projeto destaca quatro localidades: Criccieth no País de Gales, Berea nos EUA, Muramvya no Burundi e Lídice no Brasil.



font.css: utilizado para armazenar e importar fontes para os arquivos CSS.

index.css: utilizado para importar e organizar todas as classes do CSS.

Estrutura CSS:
Geral
.page: define a cor das fontes, o tamanho máximo de resolução e o background do body.

Logo
.logo: alinha o bloco, tornando-o flexível e em coluna. O @media screen ajusta para diversas resoluções.
.logo__icon: define o tamanho e a imagem do logo.
.logo__title: define a imagem e o tamanho do título.

Cabeçalho
.header: alinha o bloco, tornando-o flexível e em coluna. O @media screen ajusta para diversas resoluções.
.header__title: define o título principal da página e seu tamanho.
.header__subtitle: define o subtítulo principal da página e seu tamanho.
.header__image: ajusta o tamanho, tornando responsiva a imagem do Castelo de Criccieth, Reino Unido.

Introdução
.intro: alinha o bloco, tornando-o flexível e em coluna, alter e ajusta a estrutura responsiva das classes. O @media screen ajusta para diversas resoluções.
.intro__title: define o título e seu tamanho de forma responsiva.
.intro__subtitle: define o subtítulo e o tamanho da fonte.
.intro__artist: define o autor do subtítulo.
.intro__paragraph: define o parágrafo e o tamanho da fonte.

Galeria de Fotos
.photo: define o tamanho de todas as imagens e as mantém em grade.
.photo__item: torna as imagens responsivas.

Destino
.destination__info: define o tamanho máximo, organiza os itens em grade (grid area) e define as separações de colunas e linhas.
.destination__title: define o tamanho da fonte e sua posição na área de grade.
.destination__image: define a posição na área de grade e a responsividade.
.destination__button: define a estrutura do botão, altura, largura, cor e ações de pointer.
.destination__button:hover: define o efeito do botão ao passar o mouse por cima.
.destination__container__authors: container separado para colocar os autores em coluna.
.destination__artist: define tamanho, cor e margem da primeira frase do .destination__container__authors.
.destination__author: define tamanho, cor e margem da segunda frase do .destination__container__authors.
.destination__container: define sua posição na área de grade e usa flexbox para as descrições ficarem em coluna.
.destination__description: define o tamanho de todas as descrições do .destination__container.

Rodapé
.footer: o rodapé contém apenas o copyright.
.footer__copyright: define o rodapé, o tamanho da fonte e o alinhamento. O @media screen ajusta para diversas resoluções.

https://vensdev.github.io/web_project_homeland/