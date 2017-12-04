# Soturno
Jogo _Point & Click_
-----------------------

#### Organização

* /css
	- main.css     
		+ *Arquivo .css com os estilos*
	- /fonts       
		+ *Arquivos .ttf ou .otf das fonts e o fonts.css importando as fonts. O fonts.css será importado no começo do main.css*

* /js
	- /classes      
		+ *Arquivos .js com a estrutura das classes.*
	- /shared     
		+ *Arquivos das bibliotecas que usamos*
	- classe.js       
		+ *Arquivo que irá importar as classes da pasta /classes*
	- app.js     
		+ *Arquivo com as interações*



#### User Stories

O jogo contará com 4 (quatro) áreas, a Tela, onde terá imagens para situar onde o personagem está; o Comunicador, principal forma de interação do jogador; Gerenciador, onde os status e inventário do personagem estará; e as Anotações, uma forma de situar o jogador do que já aconteceu e os principais objetivos. Cada área tem suas respectivas funcionalidades:

* Tela:
	- Mostrar imagem;
		O jogo deverá mostrar uma imagem para cada local que o jogador estiver. Essa imagem será estática e se atualizará quando mudar o local.
	- Carregar imagem;
		Cada vez que o jogador mudar de local o jogo deverá carregar a imagem do respectivo local.
	- Clique;
		Poderá haver algumas interações por clique, onde o jogador pode pegar, interagir, abrir algum objeto.
	- Animação;
		Alguns objetos ou partes do cenário podem ter animação, dando uma estética meio anime.
* Comunicador:
	- Mostrar texto;
		O jogo contará a história principalmente por texto. Logo, o texto tem que ser mostrado na tela.
	- Carregar texto;
		Quando houver alguma interação o texto deve ser atualizado de acordo com aquela interação, dando ao jogador uma resposta dos seus atos.
	- Identificar escolha;
		O jogo deve ser capaz de identificar as escolhas do jogador, alterando a história de acordo com as escolhas.
* Gerenciador:
	- Verificar status;
        O jogo mostrará status do personagem principal, assim como do jogo em si, como andar que ele está, o que o personagem está carregando. O jogo deverá ter acesso a esses dados e mostrar na tela
	- Mostrar status;
         
* Anotações:
	- Mostrar anotações;
        De acordo com algumas interações, o jogo mostrará algumas anotações, que serve para lembrar o jogador do que aconteceu e mostrar o pensamento do personagem. 