# Regicida
O Regicida é um projeto de programação em C, que foi criado durante a disciplina de Introdução à Programação no curso de Ciência da Computação da UFCA. Foi realizado em grupo com meus amigos Arthur Lôbo e Guido Xenofonte, e idealizado pelo professor Roberto Pinheiro, ministrante da disciplina.

As Casas estão disputando ferozmente pelo Trono. Resta você, dono de todos os segredos, manipular vassalos e nobres para chegar num resultado que, apesar de não agradar a todos, trará paz. Entretanto, o tempo é escasso e algumas das suas preciosas informações tardam a chegar. Você precisará trabalhar com incertezas por um momento. E quando as informações chegarem, talvez seja tarde demais para reverter a situação. A guerra pode estar mais perto do que nunca e a única pessoa capaz de evitá-la é você.

I) Visão Geral
>Você representa o Titereiro, figura enigmática e muito influente. Após quatro Fases (Preparação, Expansão, Corvo e Intriga) você vencerá a partida se conseguir colocar cada Casa na pontuação definida no começo da partida. Evitando, assim, a guerra.

II) Preparação
>Escolha o modo de jogo e a dificuldade, que é quem define a quantidade de peças que poderão ter sua pontuação revelada.

III) Fase de Expansão
>Nessa fase, você irá preencher o tabuleiro 11x11, por meio das coordenadas, com as peças que forem entregues pelo sistema, de modo que o tabuleiro fique preenchido no formato 6x6 ao final. Você deve inserir as peças em casas adjacentes às que já possuem alguma peça inserida.

IV) Fase do Corvo e da Intriga
>Após o preenchimento do tabuleiro, as pontuações de todas as peças serão reveladas. Você terá a oportunidade de realizar seis intrigas, que significa manipular a posição das peças, para que o tabuleiro fique com a pontuação correta de cada peça, de acordo com os seguintes modos:

           [#][#][#][#][#][#]           [ ][ ][ ][ ][ ][ ]
           [#][ ][ ][ ][ ][#]           [ ][#][#][#][#][ ]
           [#][ ][ ][ ][ ][#]           [ ][#][#][#][#][ ]
           [#][ ][ ][ ][ ][#]           [ ][#][#][#][#][ ]
           [#][ ][ ][ ][ ][#]           [ ][#][#][#][#][ ]
           [#][#][#][#][#][#]           [ ][ ][ ][ ][ ][ ]
         Controle das Fronteiras       Concentração Central

>Você deve escolher duas fichas adjacentes para trocá-las de lugar. Em seguida deve trancar uma das duas peças selecionadas, e por último trancar uma das cores que as duas peças possuem. Após trancar a peça no tabuleiro, esta não poderá mais ser mexida de forma alguma. Após trancar a cor, você somente não poderá mais mexer em peças daquela cor se tentar mexer com outra peça na qual sua cor também está trancada.
>O trancamento de uma peça é representado com os ':' nas laterais da peça.

V) Fim da Partida
>Após realizar as seis intrigas (ou menos, caso consiga chegar à quantidade correta antes), você vence a partida se todas as peças estiverem com a pontuação correta dentro do tabuleiro 4x4, e assim consegue evitar a guerra e a paz irá reinar por mais algum tempo. Caso contrário, você falhou e muitas vidas serão perdidas.
