# Maquete urbana 3d em poucos minutos com ferramentas livres

Fazer uma maquete urbana virtual em 3d é uma tarefa muito entediosa para um estudante de arquitetura.
Portanto, esse breve tutorial pretende deixar essa tarefa menos cansativa e ainda assim apresentar o software livre Blender como uma importante ferramenta para alunos e professores de arquitetura e urbanismo.

## Instalando o Blender

Blender é um software livre e de código aberto desnvolvido para modelagem, animação, texturização, composição, renderização, edição de vídeo e criação de aplicações interativas em 3D.
O Blender está disponível para sistemas operacionais Windows, Mac e Linux

> https://www.blender.org/

## Blender e GIS

Além de todos os poderosos recursos do Blender, uma série de complementos freeware para diversas finalidades. O complemento que necessário para trabalhar com GIS no Blender é o [Blender Gis](https://github.com/domlysz/BlenderGIS)

Primeiramente baixe o arquivo do complemento na página do projeto https://github.com/domlysz/BlenderGIS ou clicando diretamente no link abaixo

> https://github.com/domlysz/BlenderGIS

Para instalar o complemento é necessário seguir o procedimento abaixo:

1. Menu arquivo -> Preferências do usário
2. Vá até a aba complementos
3. Clique no botão "Instalar a partir do arquivo ..." que está na parte inferior da janela
4. Selecione o arquivo .zip que foi baixado e clique em "Instalar a partir do arquivo..."
5. Clicando em "Salvar preferência do usuário" o seu complemento sempre estará ativo e esse procedimento não precisará ser realizado novamente

[Video instalando o complemento]

## Gerando o as curvas de nível com elevação

Como complemento [Blender Gis](https://github.com/domlysz/BlenderGIS) instalado é possível importar Shapefiles de curvas de nível com a sua elevação em relação ao nível do mar

[Video importar curvas de nivel com elevação]

## Gerando a mesh do terreno

Ainda é possivel a partir das curvas nas devidadas elevações criar uma mesh 3D com triangulação voronoy

[Video da criação de mesh]

## Exportando a mesh to terreno

[Video exportanto a mesh]

## Obtendo dados de edificações 3d OSM (Open Street MAP)

[OSM ou Open Street Map](https://www.openstreetmap.org/about) é uma comunidade de mapeadores voluntária que provê informações ampeadas de maneira atualizadas e colaborativas.
Muitos desses dados como, por exemplo, edificações em 3d podem ser baixadas diretamente para o Blender

[Video OSM Blender]

## Extrudando ShapeFile de edificações do GeoSampa

Os dados de edificações, assim como diversos outros dados podem ser baixados diretamente do site da [Prefeitura Municipal de São Paulo, atravéz do Geosampa]http://geosampa.prefeitura.sp.gov.br/PaginasPublicas/_SBC.aspx
Como os dados das edificações possuem a altura do edifício é possível extruda-los no momento da importação do ShapeFile

[video dos edificios extrudados]

## Exportando o modelo 3D

É possível exportar o modelo 3d para diversos formatos compatível com outros softwares, mas pra que fazer isso se o Blender pode suprir suas demandas de maneira livre, segura e gratuita?

[Video com opções de exportação]

## Próximos estudos

* Posicionar os edifícios sobre o terreno
* Renderização da maquete



