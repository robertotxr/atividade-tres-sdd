Nomes:
Joao Victor Cabral (22204113)
Pedro Alfeu Lemos (22200373)

Nessa atividade foram feitos 2 projetos: 
-> A sad_v1
-> A sad_v3

Comentando sobre cada um dos projetos:
-> A sad_v1 e a sad_v3 são circuitos que realizam o calculo da SAD(Sum of Absolute Differences). A função dele é determinar a semelhança de 2 imagens. 
-> As portas de entrada a e b, cujo sao a entrada, vao ser os valores comparados.  A porta de saida resultado armazena o vetor que mostra o resultado da SAD calculada.
-> A arquitetura principal da sad, tem 2 componentes: 
	-> A sad_bo (O bloco operativo da sad com os outros componentes como o mux registrador somador e etc), responsavel peles as operacaoes aritmeticas. 
	-> A sad_controle (Que serve para trocar os estados), que inicia a sad e sinaliza a mesma quando acabou e o resultado esta pronto.
-> A diferenca principal das sad sao seus tempos para ficarem prontas e quao custosas elas sao.
	-> A sad_v1, e menos custosa e mais lenta pois ela opera em menos de ciclos e possui menor quantidade de funcoes logicas.
	-> A sad_v3 por sua vez, e mais custosa e mais rapida, pois todos os seus registradores funcionam em paralelo, tornando o projeto muito mais rapido (2 vezes quase), mas aumento o seu custo (4 vezes aproxidamente) por ter mais operacoes dentro do seu codigo. 