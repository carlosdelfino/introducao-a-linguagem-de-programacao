Este material foi retirado na integra do arquivo "RELAÇÃO DE COMANDOS DO VISUALG 3.0.txt", e no decorrer do desenvolvimento desta apostila será amadurecido para melhorar a fluência e consolidação com o restante do texto.

Dentro do VISUALG 3.0 tem esta lista acessivel através da sequencia de teclas [CTRL]+[J], diz o autor: "mas acho que também está incompleta, é que são tantas coisas, que eu estou ainda me organizando".

A maioria deles estão dentro do HELP.CHM 

Segue a relação dos comandos, funções, variáveis, constantes e dados:

## Funções pré definidas no visualg 3.0 (pseudo-linguagem em portugol) 

### Funções matemáticas

Veja no capítulo [Operações e Funções Matemáticas](capitulo38.md)

### Funções relativas ao teclado

##### Leia 

Lê do teclado e coloca em uma variável 'nomeVariavel':


```
leia(nomeVariavel)
```



### Funções especiais de conversões

##### Pos( )

##### Asc( )

##### Carac( )

##### Copia ( )

##### Int( )

##### Compr( )

##### Maiusc( )

##### Minusc( )

##### NumPCarac( )

##### CaracPNum( )

### Funções especiais que não retornam valores para variáveis só com os PERIFÉRICO (MONITOR)

##### Escreva

Escreve na tela do monitor do computador fica na linha


```
escreva("texto entre aspas, ou variável que terá o conteudo impresso na tela")
```


Abaixo exemplo com varíável:


```
escreva(variavel)
```


##### Escreval

Escreve na tela do monitor do computador mas pulando um linha.


```
escreval("texto entre aspas, ou variável que terá o conteudo impresso na tela com um salto de linha")
```

E a seguir usando apenas uma variável


```
escreval(variavel)
```


##### MudaCor

Muda a cor dos caracteres(letras) e do fundo (tela) 


```
mudacor("nome da cor")
```


Nome de cores possíveis:
* Amarelo
* Branco
* Preto
* Azul
* Verde
* Vermelho



#####Mudacor(Cor, posição) 

Muda a cor dos caracteres (letras) ou do fundo (tela) conforme a posição informada


```
mudacor("nome da cor","posição")
```


Nome de cores possíveis:
* Amarelo
* Branco
* Preto
* Azul
* Verde
* Vermelho

Posição pode ser entre "aspas" ou:
* FRENTE
* FUNDOS


## Extras (ainda não criadas)

##### Posicionar

##### Tecla

##### Etrim

##### Dtrim

##### Esquerda

##### Direita

##### Replicar


## Comandos do Visualg 3.0 (pseudo-linguagem em portugol) 

##### Limpatela

Limpa a tela do monitor do computador

##### Pausa

##### Arquivo

#### Desvios multiplos condicionais 

só use variáveis e controles do tipo caracter


```
Escolha  xvar(caracter)
Caso "texto"
   Outrocaso 
Fimescolha (FIMESCOLHA)
```


#### Desvios simples e compostos


```
Se (condição) então 
     comandos
senão 
     comandos
FimSe
```


```
SE Entao Então (ENTÃO) 
Senao, Senão (SENÃO)
FimSe
```

#### Controle de Laços sequenciais e finitos 


    PARA variável(inteira) DE inicio ATÉ fim FAÇA
       comandos
    FIMPARA


Com passo maior que um:

 
    Para De (DE) Ate (ATE) Até (ATÉ) Passo Faca (FACA) Faça (FAÇA)
       comandos
    FimPara (FIMPARA)


#### Controle de Laços sequenciais e infinitos 

Controla quando um bloco de código deve ser executado.

##### Enquanto 

"Enquanto" uma determinada condição for verdadeira executa o bloco de código.

    Enquanto condição FAÇA
        comandos
    FimEnquanto

##### Repita

Repete o bloco de código infinitamente;

    Repita
       comandos
    Fimrepita (FIMREPITA)

##### Interrompa

Quando usado dentro de um bloco de código dentro de laço (loop), interrompe o laço;

```Interrompa```

##### Retorne

Retorna ao inicio do laço, começando novamente o bloco.

```Retorne ```

## Operadores lógicos

##### e

Conjunção logica, verdadeiro apenas se ambos as condições forem verdadeiras.

``` e (E) ```

##### ou

Conjunção logica, verdadeiro  se uma das condições forem verdadeiras.

``` ou (OU) ```


##### não

Inversor lógico, inverte a condição, se verdadeira passa a ser falsa e vice versa.

``` Não (NÃO) ```

##### Xou

Conjunção lógica, equivalente a ``` ou ``` porém apenas retorna verdadeiro se uma das condições forem verdaeiras, se ambas forem verdadeiras ou falsas retorna falso.

``` Xou (XOU) ```


## Declaração de UDFs (FUNÇÕES DEFINIDAS PELOS USUÁRIOS)


##### Funcao

    Função (FUNÇÃO)
        comandos
    Fimfuncao (FIMFUNÇÃO)


##### Mensagem 


    Procedimento (PROCEDIMENTO)
        comandos
    Fimprocedimento (FIMPROCEDIMENTO)


## Palavras reservadas Especiais

##### Algoritmo

Começo de todos os algoritmos 

````Algoritmo```

##### var

Declaração dos tipos das variáveis   

##### Inicio

Início do programa(Algoritmo) ou função ou procedimento

##### FimAlgoritmo

Termino do algoritmo e fim do programa

#### Cronometro

```Timer```


```On```


```Off```


```Eco (ECO)```


```Aleatorio (ALEATÓRIO)```


```Perfil```


```Dos (DOS)```


```Debug (DEBUG)```


```Tipo (TIPO)```


```var (VAR)```


```const (CONST)```

 
#### Declaração de constantes padrão

const (CONST)
Lista
Pi (PI)
 
#### Declaradores de Variáveis no cabeçalho do programa (área de declarações)

Var (VAR) 
Variável  (VARIÁVEL)
Variavel  (VARIAVEL)


---

Atualizado: 15/01/2018 - 16:30 | Gravado: {{ file.mtime }} | Compilado: {{ gitbook.time }}
