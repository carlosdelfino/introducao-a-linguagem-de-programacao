Vamos começar com a história do C, conhecendo como surgiu o C++, isso aconteceu  em 1979 quando Bjarne Stroustrup foi trabalhar em sua Tese de doutorado, ele iniciou seu trabalho com a linguagem chamada **Simula** designada para simulações, porém Stroustrup, achou Simula muito lento para usos práticos.

Inicialmente **C++** era chamada de **C com Classes**, um conceito da programação orientada a objetos, não iremos ver isso em nossa disciplina, mas entenda que a programação orienta a objetos tenta criar grupos de códigos _classes_ que abstraem o mundo real, por exemplo um carro seria uma classe, que agrega pneus, volante, motor, é capaz de acelerar e freiar, virar a esquerda e a direita, portanto teriam atributos que identificam os pneus, o tipo de motor, e poderia através de funções que são tratadas como mensagens para o objeto para que ele acelere ou freia, vere para um lado ou outro, issa classe chamada Carro, seria então instanciada e neste momento se torna o objeto abstrado que será usado no programa para receber as mensagens de controle através destas funções, e armazenaria seu estado nas propriedades que são variáveis próprias ao seu funcionamento. Já no C as funções são agrupadas em arquivos simplesmentes conforme seu contexto e seus nomes são patronizados para ajudar este agrupamento, o que nos responde qual a diferença básica entre C e C++, já que C++ é um superconjunto da Linguagem C, seu objetivo é adicionar a linguagem C os conceitos de programação orientada a Objetos, se perder o desempenho da linguagem C. mas não para apenas ai, há outros conceitos muito avançados que o C++ trás que estão bem além do escopo deste estudo.

Em 1983, o nome C++ foi adotado então, **++** foi escolhido por ser o operador que faz uma variável ser adicionada de uma unidade (somada do valor um), mas apesar deste pequeno incremento a linguagem C++ traz muitos recursos novos a linguagem C.

A Linguagem C++ passou a ser patronizada em 1998 em seu primeiro padrão internacional através do ISO/IEC 14882:1998, conhecido como C++98, gerando um manual de referência amplamente utilizado para esta padronização, 2003 um novo comitê apresentou diversos problemas no padrão anterior, revisando e gerando um novo padrão então chamado C++03

Já em 2005, um relatório técnico, apelidado de TR1 (Tecnical Report - 1), detalhou diversos recursos que deveriam ser adicionados a linguagem, criando um novo padrão chamado C++0x, porém somente nos meados de 2011 um novo padrão foi gerado o C++11, incluindo neste novo padrão o uso de expressões regulares e também uma proposta para uma nova sintaxe similar à laços do tipo *foreach* existentes em outras linguagens, criando uma maior distância da linguagem C original, mas não se tornando incompátivel. Porém sendo preciso identificar para o compilador quando será usado recursos especificos da Linguagem C++ e C por questões de optimização.

A linguagem C, nosso objetivo neste estudo, foi criada por Dennis Ritchie em 1972 quando este trabalhava nos Laboratórios Bell da AT&T para que fosse uma linguagem padrão do sistema operacional Unix usado então no PDP-11.

A linguagem C, foi baseada tecnicamente na linguagem ALGOL 60, uma linguagem de alto nível que já comentamos aqui quando falamos de algortimo, esta linguagem por ser uma linguagem de alto nível trabalhava longe dos conceitos da máquina, sem ter que se preocupar com aspectos como cada comando ou dado seria armazenado ou processado, o ALGOL não teve sucesso, talvez por tentar ser muito Auto Nível. A Linguagem C foi criada para substituir a linguagem FORTRAN. 

Antes do C, ouve tentativas de criar outras linguagens como a CPL (Combined Programming Language) na univerdadie de Londres e Cambridge, uma linguagem que tentava trazer o ALGOL a uma realidade, porém ainda assim não se teve sucesso, em 1967 tentaram criar a BCPL (Basic CPL), uma tentativa de Martin Richards em Cambridge, e também não frutificou.

Em 1970 o chefe de equipe que projetou o UNIX para PDP-11 criou uma outra versão resumida do CPL chamada simplesmente **B**, mas tanto **B** quando BCPL ainda eram muito limitados, e **B** também se mostrou lenta, ainda mais para escrever softwares operacionais e de alto desempenho.

Então  Dennis Ritchie ficou encarregado de criar uma nova linguagem, que seria o sucessor de **B**, nada mais original que chama-la de **C**.

A linguagem C buscou manter o "contato com o computador real" e ainda sim dar ao programador novas condições para o desenvolvimento de programas em áreas diversas, como comercial, científica e de engenharia.

Por muitos anos (aproximadamente 10) a sintaxe (formato) tida como padrão da linguagem C  foi aquela fornecida com o UNIX versão 5.0 do Bell Labs.   A principal documentação deste padrão encontra-se na publicação "The C Programming Language", de Brian Kernighan e Dennis Ritchie (K&R), tida como a "bíblia da linguagem C".

O mais interessante desta versão de C era que os programas-fonte criados para rodar em um tipo de computador podiam ser transportados e recompilados em outros sem grandes problemas. A esta característica dá-se o nome de portabilidade. Com ela, uma empresa que desenvolve um programa pode fazê-lo rodar em diferentes computadores sem ter um elevado custo a cada vez que isto for feito.

Em 1985, ANSI (American National Standards Institute) estabeleceu um padrão oficial de C o chamado "C ANSI", e o usuaremos apartir de agora. nestes estudos, mas também usaremos mais a frente o C++11, apesar de não usarmos classes, isso se dá pelo uso da IDE do Arduino que por trás tem uma ferramenta de compiação muita avançada e que já usa este padrão mais atual e consolidado no mercado.

## Próximos Passos
Iremos no [próximo capítulo]({{ page.next }}) identificar e instalar qual ferramenta iremos usar para aprendermos o C, e quais as opções que temos para isso.


---

Revisado: {{ file.mtime }} | Compilado: {{ gitbook.time }}

---
Referencias: 

 * http://www.cpluplus.com
 * http://www.inf.pucrs.br/~pinho/LaproI/Historico/Historico.htm
 * C Completo e Total, Coleção Osborne, Editora Makron Books, Autor Herbert Schildt.
 * Outras Fontes na Internet.