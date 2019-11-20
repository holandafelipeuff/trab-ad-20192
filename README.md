# trab-ad-20192
Trabalho universitário da UFF da matéria avaliação e desempenho feito em 2019.2.

## Como executar

1. Baixe a ferramenta [aqui](http://jmt.sourceforge.net/Download.html).
2. Abra o arquivo `Projeto final - Oficina mecânica.jsimg` na ferramenta e execute.

## Descrição do projeto

O trabalho consiste em modelar uma oficina mecânica como um sistema de fila na ferramenta `Java Modelling Tools - JMT`.

O empreendedor Martchelo sempre foi apaixonado por carros, desde criança seu assunto favorito era carros e conforme foi crescendo, seus pensamentos e conhecimentos sobre esse tipo de automóvel também foram amadurecendo.

Hoje o mesmo tem a vontade de abrir uma oficina automobilística, como Martchelo sabe que não é tão simples começar um negócio, então ele usou de seus conhecimentos sobre simulação de filas para avaliar como que poderia ser seu negócio.

Após algum tempo de estudo, Martchelo chegou à seguinte conclusão: 

A primeira parte do sistema seria o atendimento no balcão, onde os cliente chegariam na oficina e seriam identificados os problemas em seus veículos.

Após essa fase haveria uma ramificação em 3 tipos de "esteiras" de operações, uma dedicada a consertos de suspensão (com probabilidade de 35%), outra de motorização (com probabilidade de 45%) e uma final de parte elétrica (com probabilidade de 20%).

Após o conserto ser realizado, todas as 3 "esteiras" iriam se juntar numa fase de test-drive de avaliação do cliente onde após o teste o automóvel pode voltar para o conserto (caso haja insatisfação do cliente, probabilidade de 5% para voltar ao atendimento de suspensão, 2.5% para motorização e 2.5% para parte elétrica) ou ir para a fase de pagamento (caso esteja tudo correto e de agrado do cliente, probabilidade de 90%). 

