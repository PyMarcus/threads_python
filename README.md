<h1>Concorrência e paralelismo</h1>
<h2>Threads</h2>
<br>
&nbsp Threads são <b>linhas de execução</b>,isto é, o sistema operacional divide o programa em pequenas processos para serem executados por uma thread.<br>
&nbsp No entanto,o python puro é considerado lento, devido ao Global Interpreter Lock, mas,com o uso desse artifício,pode-se fazer a programação concorrente,e, dessa forma, executar
várias partes do código em mais de um core do processador.Desse modo, obtém-se um considerável ganho de desempenho desta tecnologia, além de aproveitar melhor a máquina.<br>
<br>
&nbsp Enfim,as threads podem ser simples ou múltiplas, dependendo de sua quantidade e aplicação, e,no que tange ao python, elas podem ser utilizadas por meio do pacote <b>threading<b>.<br>
  <br>
OBS: Isto é apenas um estudo inicial da parte de concorrência e paralelismo.
  <br>
DOC: https://docs.python.org/3/library/threading.html
