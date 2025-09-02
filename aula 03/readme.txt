Anotações Infra TI Aula 03


Registradores

Os registradores são o tipo de memória mais rápido e caro que existe em um computador. Eles são
áreas de armazenamento minúsculas localizadas dentro da própria CPU. Sua função é armazenar
temporariamente as instruções e os dados que a CPU está processando ativamente, um de cada
vez. Por serem o primeiro ponto de contato para a execução de tarefas, o acesso a eles é
praticamente instantâneo


Cache L1, L2 e L3

A memória cacheé dividida em uma hierarquia de três níveis, cada um com características diferentes:

• Cache L1: É a menor e mais rápida . Fica dentro de cada núcleo do processador. Armazena os dados que estão sendo usados
neste exato momento. O acessoé quase tão rápido quanto o dos registradores.

• Cache L2: É maior e um pouco mais lenta que a L1. Fica geralmente em cada núcleo ou próximo a ele. Atua como um segundo
filtro, armazenando dados que não couberam na L1.

• Cache L3: É a maior e a mais lenta das caches (mas ainda muito mais rápida que a RAM). É compartilhada entre todos os
núcleos do processador e armazena os dados que são usados com frequência por todos eles.

LOCALIDADE TEMPORAL

A localidade temporal se refere à tendência de um programa em reutilizar os mesmos dados ou
instruções que foram usados recentemente.

LOCALIDADE ESPACIAL

A localidade espacial se refere à tendência de um programa em acessar posições de memória
que estão próximas umas das outras.

BARRAMENTO

Um barramento é um conjunto de "fios" ou "caminhos" eletrônicos que permitem a comunicação e a transferência de dados
entre os diferentes componentes de um computador, como o processador, a memória RAM, a placa de vídeo e o
armazenamento. Pense nele como as vias de uma cidade: sem as ruas e avenidas, os carros (dados) não conseguiriam ir
de um lugar a outro.

