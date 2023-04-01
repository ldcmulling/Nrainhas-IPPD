Luan Mark da Silva Borela, Vítor de Melo Mandowski, João Antonio Neves Soares, Lourenço da Cruz Mülling

Problema das N rainhas
Como rodar:

Para a versão sem openMP:
    No termial, asseguresse de estar na pasta do programa nrainhassingle.c e digite:
        gcc nrainhassingle.c -o nrainhassingle 
    Com o programa compilado digite:
        ./nrainhassingle n
    Com n sendo o número N(número de rainhas e tamanho do tabuleiro).
 
Para a versão sem openMP:
    No termial, asseguresse de estar na pasta do programa nrainhas.c e digite:
        gcc -fopenmp nrainhas.c -pthread  -o nrainhas 
    Com o programa compilado digite:
        ./nrainhas n t
    Com n sendo o número N(número de rainhas e tamanho do tabuleiro) e t o número de threads.


Para ambas as versões, o programa mostrará o tabuleiro com a resposta e o seu tempo de execução.
