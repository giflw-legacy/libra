Libra
=====

Projeto de software para ações educativas voltadas à reciclagem e coleta de 
resíduos recicláveis (latinhas de alumínio, PETs, etc).

Histórico (breve)
-----------------

Este projeto iniciou-se em 2013, após o arrombamento de um caixa eletrônico da Caixa Econômica Federal.
Utilizando-se do equipamento vandalizado, foi criado, em parceria com a Perto, o Porjeto Pescar,
a ONG Moradia e Cidadania, entre outros parceiros, um cash captador de latinhas de alumínio.
Utilizando um detector de latinhas criado pela Azanonatec, o equipamento é capaz de coletar
aproximadamente 700 latinhas. Com um software desenvolvido por ITQuasar, utilizando-se tecnologias
open-source, surgiu a versão conceito hoje instalada no equipamento, chamada de C2Al.

Devido a incompatibilidades de licenças entre algumas bibliotecas, bem como a problemas de API que deverá
ser refatorada, e buscando um nome melhor para o programa, ele foi rebatizado para **Libra**, a constelação
da balança, representando a avaliação crítica, o pesar, que deve ser feito sobre nossos atos e suas consequências
tantos sociais como ambientais.

Para acompanhar notícias sobre o projeto piloto, bem como outras referentes ao projeto, acesse http://itquasar.com.

Especificações
--------------

Plataforma
:   Ubuntu
Linguagem
:   Java
Interface
:   Web, HTML5
Recursos a serem utilizados
:   Vídeos, áudios, imagens e textos

### Estrutura

Módulos
:   iniciam automaticamente com a apliação
:   podem ser ativados/desativados
:   dependem da API do núcleo da aplicação
Plugins
:   adicionam funcionalidades aos módulos
:   podem ser ativados/desativados
:   dependem das APIs dos módulos

### Formatos

Vídeos
:   Ogg/Theora (HTML5, webkit linux)
Áudios
:   Ogg (HTML5, webkit linux)
Imagens
:   PNG, JPG
Textos
:   html, markdown (conversão em tempo de execução para html)