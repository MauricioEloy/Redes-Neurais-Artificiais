# Redes Neurais Artificiais (RNAs)


Uma rede neural é um processador maciçamente paralelamente distribuído constituíudo de unidades de processamento simples, que têm a propensão natural para armazenar conhecimento experimental e torná-la disponível para o uso. Ela se assemelha ao cérebro em dois aspectos:

1. O conhecimento é adquirido pela rede a partir de seu ambiente através de um processo de aprendizagem.
2. Forças de conexão entre neurônios, conhecidas como pesos sinápticos, são utilizadas para armazenar o conhecimento adquirido.

## Introdução

**As máquinas pensam?**

Antes de responder esta pergunta, devemos fazer uma viagem ao túnel do tempo, esta viagem se passa por volta de 1750, período de ocorrência da Primeira Revolução Industrial. Mas qual o principal objteivo de tal revolução?

A resposta é simples!!! O homem daquela época desenvolveu novas metodologias e tecnologias de modo a aprimorar/otimizar tarefas da indústria. Ele só esqueceu do detalhe mais importante - que seria substituído pelas máquinas.

Trazendo a nossa discussão para os dias de hoje, vemos cotidianamente anúncios sobre Inteligência Artificial e jargões que enfatizam que as máquinas pensam e que em um futuro breve dominarão a humanidade.

**Isso será verdade?**

A verdade ainda não pode ser totalmente declarada, mas o que podemos fazer é entender, mesmo que de maneira superficial, o funcionamento de uma máquina poderosa e pensante, que é o nosso cérebro. O computador, chamado cérebro, supera qualquer máquina digital hoje existente, pois tem uma alta capacidade de  organizar suas "peças" constituintes, conhecidas como neurônios, de forma a realizar certos procedimentos, como reconhecimento de padrões com extrema agilidade e acertidão.

Assim, devemos portanto, entender o funcionamento de um simples neurônio biológico.

-----

## O Neurônio Biológico

<p align="center">
  <img src="https://sites.google.com/site/anatomiasistemanervosocentral/_/rsrc/1401651763408/home/neuronio/EWQEQWR.JPG" >
  https://sites.google.com/site/anatomiasistemanervosocentral/_/rsrc/1401651763408/home/neuronio/EWQEQWR.JPG*
</p>


O sistema nervoso, do qual o nosso cérebro faz parte, é um conjunto complexo de células interligadas chamadas de neurônios. O neurônio é a unidade fundamental que compõe este sistema fascinante, tal estrutura pode ser vista como um processo em três estágios, indo da recepção de um estímulo até a resposta produzida após a computação do mesmo.

Os neurônios individuais podem ser estimulados eletricamente, quimicamente ou mesmo opticamente, permitindo que os relacionamentos neurais de entrada-saída sejam mapeados. 

**Quando um neurônio é ativado?**

Sem os detalhes biológicos, podemos entender o funcionamento de uma rede neural biológica, como um processo de transferência de sinais, sinapses, que flui num emaranhado de células neuronais, esse processo de comunicação passa de um neurônio para o outro até que uma resposta seja emitada.

A obtenção de uma resposta está intresicamente ligada ao encadeamento somativo de estímulos captados, e que após a interação espacial e temporal é comparada com um limear de ativação, que se atingido, gera uma resposta e caso contrário, nada é feito.

Essa é a mágica que ao longo da história os humanos tentam modelar e reproduzir em máquinas.

-----

## Um pouco da história

Um breve histórico das redes neurais e inteligência artificial deve iniciar com o trabalho pioneiro de McCulloch e Pitts (1943), que descreveram de modo unificado estudos de neurifisiologia e da lógica matemática, com o intuito de modelar uma rede neural biológica através de máquinas computacionais.

Com base neste artigo, muitos outros pesquisadores e entusiastas puderam ser indagados e influenciados, uma retrospectiva cronológica pode ser vista abaixo:

* 1943 – McCulloch e Pitts
* 1948 – Wiener
* 1949 – Hebb
* 1952 – Ashby
* 1954 – Minsky
* 1954 – Gabor
* 1955 – Von Neumann
* 1956 – Taylor
* 1958 – Rosenblatt
* 1969 – Minsky e Papert
* Década de 70 – “Dark Age” (1974 – Werbos)
* 1982 – Hopfield
* 1986 – Rumelhart, Hinton e Williams
* 1995 – Vapnik e co-autores
* 2006 – Hinton e Ruslan Salakhutdinov
* 2015/2016 – DeepFace/AlphaGo
* 2017 – adoção em massa do Deep Learning
* 
* 
* 


-----

## O Neurônio Matemático

O modelo de um neurônio artificial proposto por McCulloch e Pitts, figura número dela, pode ser assimilado ao processo natural de uma rede neural biológica, composto por três etapas básicas: 
1. Sinais ponderados de entrada;
2. Processo somativo dos sinais de entrada, por meio de um combinador linear;
3. Resposta de saída gerada através de uma função de ativação.

Existem diversos tipos de função de ativação, cada qual com suas particularidades e aplicabilidades, aqui identificamos alguns tipos básicos:

1. Função Limiar
2. Função Linear por partes
3. Função Sigmóide

Em se falar de treinamento e aprendizado, podemos dizer que o treinamento de uma RNA pode ser por meio de algoritmos supervisionados ou não-supervisionados e por meio de tipos diversos de aprendizagem, como aprendizagem: por correção e erro, baseada em memória, Hebbiana, competitiva, de Boltzmann,...



-----

**Percepetron**

O perceptron de Rosenblatt (1958) é a forma mais simples de uma RNA classificadora de padrões linearmente serapáveis. Basicamente, temos o perceptron como sendo um único neurônio em funcionamento, em que cada nova etapa do treinamento os pesos sinápticos e bias são ajustados, de modo a melhor classificar/separar os elementos. Rosenblatt provou que se as duas classes a serem analisadas forem linearmente separáveis, o algoritmo do perceptron converge e encontra um hiperplano ideal entre as duas classes, esta prova é conhecida como teorema da convergência do perceptron.

Existem algumas formas de ajustar os pesos sinápticos e bias, como técnicas de otimização irrestricas, tais como a utilização do vetor gradiente (método da descida mais íngreme), método de Newton, método de Gauss-Newton, etc.


-----

**Mas como resolver problemas com um único neurônio?**

Como sabemos, raros serão os problemas cotidianos que serão resolvidos por um único e simples perceptron, deste modo se torna eficaz o estudo de dois aspectos básicos das RNAs, a arquitetura e o aprendizado.

Cabe a você avaliar qual é a melhor arquitetura e o melhor tipo de aprendizado para resolver o seu problema.

Não tenha medo!!! Teste e compare diferentes combinações até chegar naquele que considera satisfatória para a solução de seu problema.




-----
*Referências*

1. HAYKIN, S. Meural networks and learning machines. 3rd ed. Hamilton: Pearson, 2008

2. HAYKIN, S. Redes neurais artificiais: fundamentos e aplicações: um texto básico. 4. ed. São Paulo: Livraria da Física, 2006



