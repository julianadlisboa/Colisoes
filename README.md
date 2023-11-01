# Colisoes
Aplicação das colisões e triggers no Unity 3D.

Dupla: Gabriel Toledo e Juliana Dantas 

<H1> projeto colisores unity <H1/>

Nosso projeto tem como função demonstrar alguns colisores e suas funcionalidades, utilizando alguns exemplos que deixam mais simples de enxergar isso.
link: https://drive.google.com/file/d/1v5CIhMQCMLzw7xeeaPhZzgMFnT1AGww4/view?usp=sharing

<H2> Jogo de Plataforma com Bolinha </H2>

Uma cena do jogo onde uma bolinha cai em uma plataforma e colide com vários objetos em seu caminho antes de acertar um alvo.

[Imagem do jogo]![jogo](https://github.com/julianadlisboa/Colisoes/assets/128002239/fbaba5d6-686a-46d9-b6b8-2d944690d125)


<H2> colisores utilizados nos game-objects </H2>

•Bola (Rigidbody Collider):
 A bola principal do jogo é afetada pela física do Unity, graças ao componente Rigidbody. Ela possui um Collider para detectar colisões com outros objetos no ambiente.

[Imagem da bola]![ball](https://github.com/julianadlisboa/Colisoes/assets/128002239/bb1e1b3c-504d-40b6-8db7-f9111b5a16dc)


•Barreiras (Static Collider): 
As barreiras no jogo são objetos estáticos e não se movem. Elas são criadas com Colliders para bloquear o caminho da bola impedindo ela de sair da cena.

[Imagem das barreiras]![barreiras](https://github.com/julianadlisboa/Colisoes/assets/128002239/db8946d7-e942-453a-9296-a3462b69b514)


•Cubos Coloridos (Static Trigger Collider):
Os cubos coloridos também são objetos estáticos, mas usam um Collider do tipo Trigger. Isso significa que quando a bola colide com eles, não impedem seu movimento, mas podem acionar eventos no jogo, como por exemplo rotacionar um pouco o objeto.

[Imagem dos cubos coloridos/obstáculos]![cuboscoloridos](https://github.com/julianadlisboa/Colisoes/assets/128002239/59e122e8-f5dd-4ca0-917d-09724bd7c0df)


•Alvo (Kinematic Rigidbody Trigger Collider): 
O alvo é o objetivo final do jogo. Ele pode ser criado com um Collider do tipo Kinematic Rigidbody para permitir colisões, ou um Kinematic Rigidbody Trigger Collider para acionar eventos quando a bola o atingir.

[Imagem do alvo]![alvo](https://github.com/julianadlisboa/Colisoes/assets/128002239/d7e340b2-c9fb-4acf-b302-2f6e48690b33)

