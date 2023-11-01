# Colisoes
Aplicação das colisões e triggers no Unity 3D.

Dupla: Gabriel Toledo e Juliana Dantas 

<H1> projeto colisores unity <H1/>

Nosso projeto tem como função demonstrar alguns colisores e suas funcionalidades, utilizando alguns exemplos que deixam mais simples de enxergar isso.
link: https://drive.google.com/file/d/1v5CIhMQCMLzw7xeeaPhZzgMFnT1AGww4/view?usp=sharing

<H2> Jogo de Plataforma com Bolinha </H2>

Uma cena do jogo onde uma bolinha cai em uma plataforma e colide com vários objetos em seu caminho antes de acertar um alvo.

[Imagem do jogo]

<H2> colisores utilizados nos game-objects </H2>

•Bola (Rigidbody Collider):
 A bola principal do jogo é afetada pela física do Unity, graças ao componente Rigidbody. Ela possui um Collider para detectar colisões com outros objetos no ambiente.

[Imagem da bola]

•Barreiras (Static Collider): 
As barreiras no jogo são objetos estáticos e não se movem. Elas são criadas com Colliders para bloquear o caminho da bola impedindo ela de sair da cena.

[Imagem das barreiras]

•Cubos Coloridos (Static Trigger Collider):
Os cubos coloridos também são objetos estáticos, mas usam um Collider do tipo Trigger. Isso significa que quando a bola colide com eles, não impedem seu movimento, mas podem acionar eventos no jogo, como por exemplo rotacionar um pouco o objeto.

[Imagem dos cubos coloridos/obstáculos]

•Alvo (Kinematic Rigidbody Trigger Collider): 
O alvo é o objetivo final do jogo. Ele pode ser criado com um Collider do tipo Kinematic Rigidbody para permitir colisões, ou um Kinematic Rigidbody Trigger Collider para acionar eventos quando a bola o atingir, como por exemplo acionar uma tela escrito "fim de jogo".

[Imagem do alvo]
