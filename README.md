# Cena no Unity
 >[!Important]
 > Sobre: Esse repositório tem o intuito de apresentar uma cena criada no Unity pelos alunos e desenvolvido na aula de LP. Contém informações sobre o contexto da cena, materiais, terrenos, entre outros.
 > Dupla: Alex Campos de Oliveira e Gabriel Barbosa Soares.
 > Curso: 2° Mtec Jogos Digitais.

## Contexto da Cena
 * A cena foi criada inspirando-se na ideia de um deslizamento de terras (a qual carrega junto a si outros objetos menores) em uma região elevada em direção a costa. No intuito de deixar mais imersivo, foi-se adicionado um carro Sedan da Asset Store no intuito de simular que alguém estava ali. Utilizamos bastante de modelos 3D já prontos, principalmente para a composição da floresta na parte de trás da montanha e também da floresta abaixo da câmera posicionada, mas algumas partes do projeto foram feitos pegando do 3D Game Object, como por exemplo: O que está caindo da montanha, a montanha e todo o solo.
   
 ![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/b643b91b-97dd-421c-9d3e-6136b3fbfeca)
 
* Abaixo está uma imagem da cena concluida.
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/e346f499-088c-4692-8a62-f5faebb447f9)


________________________________________________________________________________________________________________________________________


## Materiais utilizados
* Como dito anteriormente, todo o solo do cenário foi feito utilizando-se de, em sua maioria, objetos Cube (a grama, a montanha, entre outros, foram feitos utilizando do mesmo), tendo somente algumas formas que utilizem do Quad (estrada). Alguns objetos os quais foram pegos na AssetStore foram: Sedam (carro) e as árvores que estão presentes abaixo e a frente do usuário que estiver visualizando, o que sobrou falar foram as imagens de fundo que simulam o céu e as nuvens (duas imagens separadas), que foi pego na AssetStore e utilizado para a simulação de um belo céu atrás da montanha.

### Árvores:
* Foram utilizadas para a composição do cenário abaixo e ao redor da câmera e da montanha.
  
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/36bfbd26-d696-490e-8e67-fa53dedb8343)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/8b3cf904-4387-4855-a847-d87ddc4e89d4)

### Sedan:
* Foi inserido para deixar a cena mais imersiva
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/5ff43963-902b-4fff-b7c4-8184efb0dea7)


### Estrada: 
* Foi construída por nós mesmos para melhor imersão e também composição do cenário. Não faria sentido ter um carro e não ter uma estrada.
  
 ![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/b1442d63-fd81-4503-bfe0-86f359c57e16)

### Solo:
* O solo, como já é de se imaginar, foi feito no intuito de compor o cenário, não permitir que os objetos passassem ou caíssem no puro nada e também para deixar bonito visualmente.

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/763b1f05-2797-4aaa-999f-469e1c1ebe90)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/49d8aeb5-04ba-400e-b599-7f2a454b9f91)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/ec987770-e061-495c-82ac-d3deae083532)



### Céu:
* Utilizado para composição do cenário e pela questão estética e realista.

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/98edb36f-0276-4d8e-9595-3343fd4c3efc)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/9c9ac96b-61e8-4138-b182-d8122e2ba6ad)


### Pedras: 

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/2dcf2d59-3e16-4157-a7be-208dbc95818d)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/7409428b-1ee0-4834-9da7-40c4706116dc)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/4def9a3f-6e68-4f1d-8784-0a607419b2b9)


### Troncos:
* Pego do 3D Game Object para fazer parte da avalanche, foi inserida uma textura no intuito de simular o que deveria ser: um tronco.

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/ce3de838-8a27-44d7-a0ba-aa43faa1c842)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/021d1544-7a4c-4734-87c2-8f42a089cfe9)


________________________________________________________________________________________________________________________________________

## Fisica

### Materiais Utilizados:
 Foram criados 3 Physic Material para adicionar variedade nos impactos de cada objeto: cada um de seus valores se difere do outro, o que permite resultados variados e diferentes entre si, pulando muito ao impacto ou menos.
 
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/78d2c55a-11d3-4652-a0fd-f6e92392c977)

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/d9b6bc9e-ce17-43e8-a01e-e07e39fe288b)


 ### Physic Material:
* O Physic Materia permite modificarmos a real força de impacto do objeto, determinando assim se ele irá quicar ao colidir com o chão e a altura do mesmo, ou se ele não será tão afetado e não subirá muito. Também é possível modificar a fricção do objeto, o que determina a força que se opõe ao objeto.
  
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/18904bb6-e721-4bd6-9fcd-fc1fc8c03ebb)


 ### Rigidbbody:
 * O Rigidbody, como é possível observar abaixo, permite ao usuário transformar um objeto específico em algo realmente material, tendo assim a sua massa, centro de massa, angulação, entre outras opções, como por exemplo se o objeto terá realmente um centro de massa predefinido (tem como alterar por conta própria a região do centro de massa) ou se ele respeitará a gravidade.

![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/63e28b39-f2ad-46d5-a2a4-e015403a873f)


## Câmera
 * A câmera foi estrategicamente posicionada para providenciar uma visão de toda a montanha e dos objetos que cairão, que inclusive, foram pegos do Game Object 3D.
   
![image](https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/353abd81-1d3e-4907-81d9-5709293a875d)


## Video
https://github.com/Alex2024Campos/Cena-no-Unity/assets/160960774/8871fe59-735e-4cb7-ae46-622b2640d9ab
