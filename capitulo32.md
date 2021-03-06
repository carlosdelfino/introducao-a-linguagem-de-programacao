Em toda linguagem de programação é possível usar nomes especiais, tanto para chamar comandos, funções/procedimentos. Não veremos ainda em detalhes o que são procedimentos, mas aprenderemos desde cedo como criar nomes de variáveis e funções (se no caso do Portugol Procedimentos também)

## Nomeando Variáveis

Ainda não estudamos o que são variáveis, por hora basta saber que são espaços no computador, onde dados são gravados, e podem ser reutilizados e alterados.

Os nomes das variáveis devem obrigatoriamente começar por uma letra. Após a primeira letra, poderá conter letras, números ou underline ( _ ), até um limite de 30 caracteres. As variáveis podem ser simples ou estruturadas (vetores de uma ou duas dimensões). 

Variáveis não podem ter nomes iguais.

Como já foi dito anteriormente as declarações de variáveis devem obrigatoriamente ser identificadas com o termo `var`, seguir com os nomes das variáveis separados por “,”, colocar o sinal “:” e finalmente informar o tipo daquela variável ou lista de variáveis. Veja o exemplo a seguir:

```
var 
   a: inteiro
   nome_aluno : caractere
   numeroDeMaterias: inteiro
   av1, av2 : real
```

Como pode ver o bloco de declaração das variáveis não precisa ser finalizado, ele termina quando inicia outro bloco, seja de função, procedimento ou do algoritmo principal.

### Notação CamelCase
Uma prática muito importante na programação é o uso da notação CamelCase, com ela podemos acelerar o entendimento do código e a leitura dos nomes usados.

A Notação CamelCase é amplamente utilizada e já virou uma prática comum e há apenas uma pequena controvercia se uma nome deve começar ou não com a primeira letra da primeira palavra em maiúscula ou não.

Até mesmo em C/C++ não há o mal costume de unir práticas de nomeação antigas com Novas, deixando o código pouco elegante, em C++ apenas é percepitvel o constante uso da Notação, já em C puro, é muito pouco usado, mas neste curso iremos usar sempre a notação camel como descrito abaixo.

Usaremos sempre a primeira letra de cada palavra em maiúscula, com as seguintes execessões:

* Quando nome de variáveis a primeira palavra será toda em minúscula
* Quando nome de variáveis, não usaremos traço baixo, a não ser que auxili o entendimento de variáveis com nomes mais complexos, este uso deve ser acordado com a equipe, e clarmente documentado como usar em caso de se precisar criar novas variáveis.
* Quando nome de constantes, todas as palavras serão escritas com todas as letras em maiúsculas, sendo cada palavra separada da outra por traço baixo;
* Quando nome de funções deverá ser adotado o mesmo critério usado para as variáveis;
* Quando nome de procedimentos deverá ser usado cada primeira letra em maiúsculo, mesmo no primeira palavra, podendo quando negociado com a equipe, em caso denomes mais complexos usar o traço baixo para auxiliar na criação do nome;
* Quando nome de classes deverão seguir o mesmo critério para procedimentos;
* Em todos os casos poderão ser usados números;
* Mesmo que a linguagem permita, "nunca" use acentos e simbolos especiais;

para conhecer a história da Notação CamelCase e conhecer melhor como adota-la, visite o link http://c2.com/cgi/wiki?CamelCase, C2 vem de Cunningham and Cunningham, epresa criada por Ward Cunningham e sua filha para consultoria em desenvolvimento de softwares, são os principais influênciadores da engenharia de desenvolvimento de software no mundo, juntamene com Erik Evans (Erik J. Evans) e Martim Fowler.


## Palavras Reservadas

Algumas palavras não podem ser usadas além da forma definina pelo Portugol, sendo assim são consideradas reservadas, no VisuAlg o portugol tem as seguintes palavras como reservadas:

* Algoritmo
* var
* Inicio
* FimAlgoritmo
* Cronometro
* Timer
* On
* Off
* Eco (ECO)
* Aleatorio (ALEATÓRIO)
* Perfil
* Dos (DOS)
* Debug (DEBUG)
* Tipo (TIPO)
* var (VAR)
* const (CONST)

Evite usar nomes de funções e comandos internos como variáveis principalmente.

## Próximo Passo 

Veremos a seguir os tipos de dados que podemos declarar. Durante as nossas práticas discutiremos o conceito prático das variáveis e como isso funciona nos computadores, posteriormente quando estudarmos a linguagem C/C++ veremos como as variáveis são armazenadas em memória, isso é importante para uso com Microcontroladores.

---
Atualizado: 09/07/2016 - 16:25 | Revisado: {{ file.mtime }} | Compilado: {{ gitbook.time }}
