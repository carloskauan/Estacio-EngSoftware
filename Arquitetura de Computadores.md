# Tema 1
## Maquina de turing

Final do selculo 19 inicio do seculo 20, ja existiam maquinas eletro mecanicas para realizar diversas tarefas e na decada de 1930 o matematico ingles Alan Turing estudava como maquinas podiam ser programaveis para resolver problemas e nesse estudo surgiu o conceito de maquina de Turing, precursor matematico do computador

### Composta por 4 elementos

1. Fita infinita dividada em celulas que pode ser lida e escrita
2. Cabeçote capaz de ler ou escrever e escrever em uma celula da fita e se mover da direita para a esquerda
3. Um registrado que mantem um estado atual da maquina
4. Função de transição que calcula a partir do estado atual da maquina e do simbolo lido qual o novo estado e se o cabeçote deve se mover para a direita ou esquerda ou escrever na fita

Turing tbm iniciou os estudos para formalizar o que hj conheçemos por Algoritimo, conjunto finito de passos capaz de resolver um determinado problema. 
Por conta disso e conciderado o pai da ciencia da computação e por isso foi chamado pelo governo ingles para trabalhar na quebra dos criptogramas alemães dutrante a segunda Gunda guerra mundial
Usavam uma maquina eletromecanica chamada enygma para cifrar suas mensagens, usando essa maquina a equipe de turing foi capaz de quebrar a chave diaria e entender as mensagens.
Projeto que foi base para o surgimento do primeiro computador.

## Claude Elwood Shanno

Ainda na segunda guerra Claude Elwood Shannon que trabalhava na Bell Labs desenvolveu estudos para comunicação entre equipamentos.
Seu principal artigo chamado A Mathematical Theory of Communication que foi publicado no fim da segunda guerra , introduziu o conceito de unidade minima para se armazenar informação o digito binario, BIT binary digit.

### BIT

Unidade minima de informação que pode ter os seguintes valores

bit|valor
----|-----
0 | false ou desligado
1 | true ou ligado

Com essa simples diferença podemos representar qualquer numero e qualquer informação que leva o nome de representação digital binaria.

Shannon e conhecido pela criação do que hj chamamos de teoria da informção devido a publicação desse artigo.

## Gerações de computadores

### Primeira geração: Valvulas termionicas

Ainda durante a segunda guerra mundial, nos estados unidos , foi desenvolvido o primeiro computador eletronico da historia, Trata-se do Eniac, um computador integrador numerico eletronico, cujos numeros impressionam

Componentes: 170000 valvulas
Peso: 30 toneladas
Espaço utilizado: Salade 150m2
Capacidade de procesamento: 1 bilhão de vezes menor que a dos celulares hoje em dia

### Segunda geração: Transistores

Os primeiros transistores ocupava apenas milimetros, precisando de bem menos energia que as valvulas. Assim, foi possivel reduzir o tamanho de radios, equipamentos eletronicos em geral e computadores

### Terceira geração: Circuitos integrados

Na decada de 1960, o proximo salto de evolução foi dado com a criação de circuitos integrados : pastilhas de silicio que contem um circuito enetronico miniaturizado. É o que de forma comum chamamos de chip de computador

#### PCs
Com o uso dos transistores e CI, os computadores ficaram menores e cada vez mais baratos.
Em meados da decada de 1970, houve a eclosão dos computadores pessoais(denominados pcs)
Duas famosas empresasdo setor, alias, surgiram nesse periodo

##### Microsoft Corporation

Empresa de maior faturamento em programas de computador, conhecida pelo sistema operacional Windows e pelo conjunto de ferramentas chamado de Office. Fundada em 1975, nos Estados Unidos, por Bill Gates (um dos homens mais ricos do mundo) e Paul Allen.

##### Apple Inc.

Em 1976, vendeu 200 unidades do seu primeiro PC, o Apple I. No ano seguinte, contudo, o Apple II vendeu milhares de unidades. A organização, então, abriu seu capital na bolsa de Nova York. 

### Quarta geração:  Microprocessadores.

A decada de 1980 presenciou a proliferação de PCs cada vez mais potentes, baratos e conectados ´por meio  do surgimento da internet: a rede mundial.

Alemd disso, um novo equipamento aparecia nos lares: o video game, um tipo de computador especilizados, cujo programas são jogos eletronicos com enfase nos graficos e na interação com os usuarios.

Apos o fim do seculo XX, os computadores ja eram tão pequenos e potentes que se encontravam embarcados em diversos equipamentos cotidianos, como automoveis, aviões e videogames, alem de se tornar mais comum a presença de laptops(microcomputadores pessoais portateis) nas casas das pessoas

Não tardou muito para serem integrados a televisões e celulares. Nos anos 2010, essa integração passou a ser feita por intermedio de smartphones e smart Tvs

## Hardware e Software

Hardware: Componentes fisicos, ou seja, o que pode ser visto e tocado.

Software: Programas executados no computador

 ## Principais componentes de Hardware

 ### Processador

Tambem conhecido como CPU(Central Processing Unit), processador é o cerebro do computador, pois recebe as instruções e as executa sequencialmente. Seu principal componente e a unidade logica aritimetica, responsavel por operações como adicionar e subtrair

#### Clock

A execução das instruções de um processador é regulada pela presença de um pulso de frequencia constanate denominado clock, que é medido em Hertz(hz)- numeros de pulos por segundo

 Uma das principais caracteristicas de um processador é a velocidade com que consegue executar instruções. Isso depende diretamente da frequencia do clock

#### MultiCore

Ao longo do tempo por conta da interferencia fisica entre seus componentes, ficou inviavel a continuação do aumento de clockk a cada geração. A solução dada pelos projestista foi colocar diversos microprocessadores(chamados nucleos) dentro de um mesmo chip de processador. Tecnica conhecida como multicore.

Assim foram criados processadores com como por exemplo Dual core(dois nuclueos) e Quad core(quatro nucleos)

> Atualmente , a maioria dos processadores de mercado (inclusive celulares) utiliza ao menos quatro core e frequencias de clock de alguns bilhões de pulsos ghz

###  Memoria RAM

A memoria principal é parte fundamental do computador, pois se trata do espaço onde são armazenados os dados e os programas executados no processador. Ela funciona com uma serie de celulas em cada uma armazena um conjunto de 8bits (chamado de bytes). essas celulas funcionam como caixas de correio: cada uma tem seu endereço, embora so armazene uma carta por vez.

A memoria tamebem conhecida como RAM( EM SEU FORMATO MAIS COMUM) por permitir o acesso a qualquer endereço em qualquer ordem

Disso o nome de Memori de Acesso Aleatorio(Random Acess Memory), nomrmalmente essas memorias são vendidas em pentes de memoria.

Esse tipo de memoria é volatil, ou seja, seus daddos são apagados quando o sistema fica sem energia


#### Principais caracteristicas

##### Capacidade de armazenamento

Se possui 4gb de armazenamento, a memoria conta com 4 bilhoes dessas celulas, podendo armazenar ate 32 bilhoes de bits de dados

##### Velocidade de comunicação com barramento

Trata-se da velocidade com que a memoria consegue transferir os dados para o processador

Por exemplo, uma memoria de 400mhz consegue transferir dados para o procesador com uma taxa de ed 3200mps (3bilhoes e 200 milhoes de bits por segundo)

### Placa-mãe

A placa mãe consiste em um circuito eletrico impresso e uma serie de componentes conectados nela.

Os principais componentes são:

* So quente de do processador
* Soquente de encaixe dos pentes de memoria
* Barramentos de perifericos (PCIx, por exemplo)

A função basica da placa-mãe é conectar o processador, a memoria e os perifericos. Essas conexões são chamadas de barramentos.
Conforme a tecnologia se desenvolve, a placa-mãe começa a integrar em si perifericos que ate então precisavam ser encaixados nela, como placas de video, placas de rede, placas constroladoras de portas seriais e paralelas.

> Placas mães dos celulares são circuitos altamente complexos, contando com processador, memoria, controladora de video, controladora de video toutchscreen, acelerometro, gps e plca de rede sem fio e celulcar. Todos eles estão integrados a sua placa-mãe

### Perifericos

Por se conectarem a parte central do computador, seus demais componentes são chamados, em geral de perifericos. Muitos mostram ser tão relevantes que não seriam capazes de imaginar sistemas computacionais sem eles.

#### Dispositivos de entrada

* Tela touchscreen: permite a seleção de elementos sem precisar do mouse
* Teclado: segue um padrão ja definido das maquinas de escrever, facilitando seu uso e sua aceitação
* Mouse: abre novos rumos por permitir a indicação de pontosna tela e a seleção deles, o que gerou um grande impacto no desenvolvimento de interface graficas
* Microfone: capta o audio
* Camera: capta audio com video
* Placa de rede: recebe os dados transmitidos pela rede

#### Dispositivos de saida

* Sistema de video: Composto geralmente por uma placa de video e um monitor ou uma tela
* Alto-falantes ou caixas de som: Emite sons e sinais sonoros
* Impressora: imprime documentos elaborados no computador
* Placa de rede: Envia dados pela rede

### Memoria secundaria

Mais conhecidas como HD(Hard Disk ou Disco Rigirdo) elas possuem essa nomenclatura porque sua tecnologia predominante envolve discos magneticos lidos e escritos por uma cabeçote

Atualmente, essa tecnologia tem sido substituida por discos de estado solido SSD, que são muito raidos e menos propensos a falhas e desgastes por não haver partes moveis mecanicas neles

#### Princiapais caracteristicas da memoria secundaria

* Normalmente medida em GB ou TB
* Velocidade de transmissão que depende do barramento da placamãe
