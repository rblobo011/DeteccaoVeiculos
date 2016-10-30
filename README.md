# DeteccaoVeiculos

Este repositório contem o código de um sistema de identificação de veículos e auto aprendizagem.

O intuito deste é disponibilizar para a comunidade um algoritmo desenvolvido para identificar vagas de estacionamentos disponíveis e, além disso, utilizando propriedades da inteligência artificial, se auto aperfeiçoar capturando e selecionando imagens positivas de carros e treinando novos Classificadores Cascade mais robustos.

O sistema se resume a duas frentes, a primeira é o servidor, na qual foi desenvolvida utilizando Visual Studio 2012 com NET framework 4.5 na plataforma x86. Este é responsável pelo gerenciamento das informações, conexão com o servidor, controle do algortimo de detecção, etc. 

*OBS: Um ponto importante a mencionar: este código foi desenvolvido com o intuito de pesquisa, assim este foi projetado para funcionar em um ambiente com um servidor estabelecido e controlado. Este NÃO funcionará em outra máquina já que, a conexão com este servidor foi retirada.

A outra parte do sistema é composta por um algoritmo desenvolvido com a biblioteca de computação visual denominada OpenCV, na versão 2.4. Este possui um grande potencial e está se desenvolvendo intensamente. Para a detecção de veículos, foi utilizado a função "detectMultiScale", na qual, após tratarmos os frames, é realizado esta detecção.

Caso este código seja utilizado em alguma pesquisa, por favor referencie a pesquisa como fonte.

Estou a disposição para ajudar caso necessário. Para mais informações, baixem o PDF.
