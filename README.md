# EspacoCriativo

### CARREGAR NOVAS FIGURAS 3D
.
.
.
Passo 1: Verificar o próximo código disponível (EX.: EC_3D001)

Passo 2: Renomear os arquivos .obj e .gltf com o código da figura

Passo 3: Colocar todos os arquivos e suas dependências em uma pasta com o nome igual ao código da figura (.obj, .mtl, .gltf, .bin,...)

Passo 4: Fazer upload da pasta para EspacoCriativo/3D/Modelos

Passo 5: Referenciar no arquivo EspacoCriativo/3D/Modelos/Index/Componentes todas as dependências (figuras e arquivo .mtl). Não é necessário referenciar os arquivos .obj, .gltf e .bin

Passo 6: Colocar uma figura (imagem do arquivo em 3D) na pasta EspacoCriativo/3D/Figuras, com o nome igual ao código da figura e extensão .jpg

Passo 7: Colocar uma figura (ícone em desenho referenciando o arquivo 3D) na pasta EspacoCriativo/3D/Ícones, com o nome igual ao código da figura e extensão .jpg

Passo 8: Criar um arquivo na pasta EspacoCriativo/3D/Info, onde o nome será igual ao código da figura
	:Linha 1 - Nome da figura que será exibida
	:Linha 2 - Descrição da figura e do personagem
	:Linha 3 - Tamanho padrão aproximado da impressão, altura x largura, em cm (EX.: 15cm x 5cm)
	
Passo 9: Referenciar no arquivo EspacoCriativo/3D/Modelos/Index/Index o código e o nome da figura, ordenando pelo nome
