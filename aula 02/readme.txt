Infra TI - anotações 

Qual a diferença de bit e byte?

bit é a menor unidade de informações em sistemas digitais, já o byte é o conjunto de 8 bits


Arquiteturas de computadores é o ramo da computação que define como o hardware e o software interagem.


A Arquitetura de processadores é um subconjunto da arquitetura de computadores, voltado
exclusivamente para o processador (CPU).


ARQUITETURA” X “ORGANIZAÇÃO


Arquitetura (o “o quê”): aspectos visíveis ao programador (conjunto de instruções, registradores,
modos de endereçamento).

Organização (o “como”): como a arquitetura é implementada (pipeline, caches, interconexões,
microarquitetura).


ESPECIFICAÇÕES


•Conjunto de Instruções (ISA): instruções que a CPU reconhece (ADD, LOAD, STORE, JMP).
•Largura de palavra: número de bits processados simultaneamente (ex.: 32 bits, 64 bits).
•Modos de endereçamento: como acessar dados (imediato, direto, indireto, relativo).
•Número de registradores: impacta em desempenho (arquiteturas RISC usam muitos registradores).
•Organização da memória: endereçamento por byte ou por palavra.
•Pipeline e paralelismo: execução de múltiplas instruções ao mesmo tempo.
•Hierarquia de memória: uso de caches, RAM e armazenamento secundário.



TIPOS ARQUITETURAS

Computadores:
•Von Neumann -> Base dos Pc's atuais 
•Harvard

Processadores:
•RISC (Reduced Instruction Set Computer)
•CISC (Complex Instruction Set Computer)
•MIMD / SIMD / VLIW

Arquiteturas Especiais
•GPU (Graphics Processing Unit): especializada em paralelismo massivo.
•Arquiteturas Quânticas: emergentes, baseadas em qubits.
•Arquiteturas Neuromórficas: inspiradas no cérebro humano.


PROCESSADORES

Termos Importantes
•CPI (Cycles per Instruction): ciclos necessários para executar uma instrução.
•IPC (Instructions per Cycle): instruções executadas por ciclo.
•Pipeline: divide a execução em estágios (Fetch, Decode, Execute, Memory, Writeback).
•Superscalar: permite múltiplas instruções por ciclo.
•Out-of-order Execution: CPU reorganiza a execução para não “ficar parada”.
•RISC x CISC:
• RISC → poucas instruções simples (ARM, RISC-V).
• CISC → muitas instruções complexas (x86).



O que é x86
•É o nome da arquitetura de conjunto de instruções (ISA) criada pela Intel.
•O nome vem do Intel 8086 (de 1978) e seus sucessores (80186, 80286, 80386, 80486).
•Por isso, x86 se tornou sinônimo de processadores compatíveis com essa família de instruções.
•Originalmente, era uma arquitetura de 16 bits (8086/8088).
•Evoluiu para 32 bits (80386) e depois para 64 bits (x86-64 ou AMD64).


O que é x32 (32 bits)
•Refere-se a processadores e sistemas operacionais que usam endereços de 32 bits.
•Significa que podem endereçar até 4 GB de memória RAM diretamente (2³² endereços =
4.294.967.296 bytes).
•Baseada nos processadores Intel 80386 em diante.
•Hoje, já é considerada limitada, pois não aproveita memórias maiores.


O que é x64 (64 bits)
•Refere-se a processadores e sistemas operacionais que usam endereços de 64 bits.
•Teoricamente, podem endereçar 16 exabytes de memória (2⁶⁴), mas na prática os processadores
limitam a valores menores (ex.: 256 TB).
•Introduzida pela AMD como AMD64 e adotada pela Intel como Intel 64.
•É a arquitetura padrão atual em PCs, notebooks e servidores.
•Permite:
• Mais registradores.
• Endereçamento de memórias maiores.
• Melhor desempenho em algumas aplicações.


