# Processamento simétrico e assimétrico

# **DIFERENÇA ENTRE MULTIPROCESSAMENTO ASSIMÉTRICO E SIMÉTRICO**

**Multiprocessamento** é o uso de duas ou mais unidades centrais de processamento em um único sistema de computador. **Multiprocessamento assimétrico e multiprocessamento simétrico** são dois tipos de multiprocessamento.

**Multiprocessamento assimétrico: o**

sistema de multiprocessamento assimétrico é um sistema de computador multiprocessador em que nem todas as unidades centrais de processamento (CPUs) múltiplas interconectadas são tratadas igualmente. No multiprocessamento assimétrico, apenas um processador mestre executa as tarefas do sistema operacional.

Por exemplo, o AMP pode ser usado para atribuir tarefas específicas à CPU com base na prioridade e na importância da conclusão da tarefa.

![https://media.geeksforgeeks.org/wp-content/uploads/20201117015924/a224.png](https://media.geeksforgeeks.org/wp-content/uploads/20201117015924/a224.png)

**Multiprocessamento simétrico:**

envolve um hardware de computador multiprocessador e arquitetura de software onde dois ou mais processadores idênticos são conectados a uma única memória principal compartilhada, têm acesso total a todos os dispositivos de entrada e saída. Em outras palavras, o multiprocessamento simétrico é um tipo de multiprocessamento onde cada processador é autoprogramado.

Por exemplo, o SMP aplica vários processadores a esse problema, conhecido como programação paralela.

![https://media.geeksforgeeks.org/wp-content/uploads/20201117020235/a137.png](https://media.geeksforgeeks.org/wp-content/uploads/20201117020235/a137.png)

**Diferença entre multiprocessamento assimétrico e simétrico:**

| MULTIPROCESSAMENTO ASSIMÉTRICO | MULTIPROCESSAMENTO SIMÉTRICO |
| --- | --- |
| No multiprocessamento assimétrico, os processadores não são tratados igualmente. | No multiprocessamento simétrico, todos os processadores são tratados igualmente. |
| As tarefas do sistema operacional são feitas pelo processador mestre. | As tarefas do sistema operacional são feitas por processador individual |
| Sem comunicação entre os processadores, pois são controlados pelo processador mestre. | Todos os processadores se comunicam com outro processador por uma memória compartilhada. |
| No multiprocessamento assimétrico, os processos são mestre-escravo. | No multiprocessamento simétrico, o processo é obtido da fila pronta. |
| Os sistemas de multiprocessamento assimétrico são mais baratos. | Os sistemas de multiprocessamento simétrico são mais caros. |
| Sistemas assimétricos de multiprocessamento são mais fáceis de projetar | Sistemas simétricos de multiprocessamento são complexos de projetar |