![Maquete urbana 3d em poucos minutos com ferramentas livres](https://github.com/arquiteturalivre/maqueteurbana3d/blob/master/imagens/teaser.gif?raw=true)

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

![Video instalando o complemento](http://i.giphy.com/l0Ex8HwtpA9M2LdwA.gif)

## Gerando o as curvas de nível com elevação

Como complemento [Blender Gis](https://github.com/domlysz/BlenderGIS) instalado é possível importar Shapefiles de curvas de nível com a sua elevação em relação ao nível do mar
[O arquivos usados aqui no exemplo podem ser baixados aqui](https://github.com/arquiteturalivre/maqueteurbana3d/tree/master/arquivos)

![Video importar curvas de nivel com elevação](https://github.com/arquiteturalivre/maqueteurbana3d/blob/master/imagens/curvas_de_nivel_com_elevacao.gif?raw=true)

## Gerando a mesh do terreno

Ainda é possivel a partir das curvas, devidamente elevadas, criar uma mesh 3D com triangulação delaunay

![Video da criação de mesh](https://raw.githubusercontent.com/arquiteturalivre/maqueteurbana3d/master/imagens/criacao_de_mesh_triangulado.gif)

## Exportando a mesh to terreno

![Video exportanto a mesh](https://raw.githubusercontent.com/arquiteturalivre/maqueteurbana3d/master/imagens/exportando_mesh.gif)

## OSM (Open Street MAP)

[OSM ou Open Street Map](https://www.openstreetmap.org/about) é uma comunidade de mapeadores voluntária que provê informações ampeadas de maneira atualizadas e colaborativas.
Vários mapas estão disponíveis no Blender, para localizar mais rapidamente o que procura e posicionar na tela basta apertar a tecla G.

![Video OSM Blender](https://raw.githubusercontent.com/arquiteturalivre/maqueteurbana3d/master/imagens/osm.gif)

## Obtendo dados de edificações 3d OSM (Open Street MAP)

Muitos desses dados, como por exemplo edificações em 3d, podem ser baixadas diretamente para o Blender.
Bastta posicionar a sua viewport de forma ortogonal e vista superior e a região que está visualizando será importada como no vídeo a seguir.

![Video OSM Blender](https://github.com/arquiteturalivre/maqueteurbana3d/blob/master/imagens/edificacoes_osm.gif?raw=true)

## Extrudando ShapeFile de edificações do GeoSampa

Os dados de edificações, assim como diversos outros dados podem ser baixados diretamente do site da Prefeitura Municipal de São Paulo, através do [Geosampa]http://geosampa.prefeitura.sp.gov.br/PaginasPublicas/_SBC.aspx
Como os dados das edificações possuem a altura do edifício é possível extruda-los no momento da importação do ShapeFile

![video dos edificios extrudados](https://github.com/arquiteturalivre/maqueteurbana3d/blob/master/imagens/import_edificacoes_shp.gif?raw=true)

## Exportando o modelo 3D

É possível exportar o modelo 3d para diversos formatos compatível com outros softwares, mas pra que fazer isso se o Blender pode suprir suas demandas de maneira livre, segura e gratuita?

## Próximos estudos

* Posicionar os edifícios sobre o terreno
* Renderização da maquete

## Esse tutorial é livre

Portanto, fique a vontade para alterar, copiar, distribuir.



