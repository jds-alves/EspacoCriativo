# EspacoCriativo

### CARREGAR NOVAS FIGURAS 3D

Passo 1: Verificar o próximo código disponível (EX.: EC_3D001)

Passo 2: Ajustar a figura 3D no 3D Builder
	 :Altura entre 18cm e 30cm
	 :Cor como material #808080 e fosco
	 :Salvar como .obj e .gltf, com o código da figura como nome
	 :Salvar os arquivos .mtl e .bin sem acentos e espaços e com o nome da figura separado por "_" quando necessário

Passo 3: Colocar todos os arquivos e suas dependências em uma pasta com o nome igual ao código da figura (.obj, .mtl, .gltf, .bin,...)

Passo 4: Fazer upload da pasta para EspacoCriativo/3D/Modelos

Passo 5: Referenciar no arquivo EspacoCriativo/3D/Modelos/Index/Componentes todas as dependências (figuras e arquivo .mtl). Não é necessário referenciar os arquivos .obj, .gltf e .bin

Passo 6: Colocar uma figura (imagem do arquivo em 3D) na pasta EspacoCriativo/3D/Figuras, com o nome igual ao código da figura e extensão .jpg.

Passo 7: Colocar uma figura (ícone em desenho referenciando o arquivo 3D) na pasta EspacoCriativo/3D/Ícones, com o nome igual ao código da figura e extensão .jpg

Passo 8: Criar um arquivo na pasta EspacoCriativo/3D/Info, onde o nome será igual ao código da figura
	:Linha 1 - Nome da figura que será exibida
	:Linha 2 - Descrição da figura e do personagem
	:Linha 3 - Tamanho padrão aproximado da impressão, altura x largura x profundidade, em cm (EX.: 15 x 5 x 6.8)
	:Linha 4 - Nome e autor da figura
	:Linha 5 - Site onde a figura foi extraída
	
Passo 9: Referenciar no arquivo EspacoCriativo/3D/Modelos/Index/Index o código e o nome da figura, ordenando pelo nome
