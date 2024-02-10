# Java

---

quando uma classe não possui um construtor declarado, um construtor padrão é fornecido pelo compilador JAVA.

I. Um atributo de classe estático compartilha o mesmo espaço de memória em todos os objetos e pode ser utilizado mesmo que nenhum objeto de sua classe tenha sido alocado.

II. Caso um atributo em uma classe seja criado sem indicação de sua visibilidade, por padrão, este atributo assume uma visibilidade de pacote.

III. Um método em uma classe filha sobrescreve um método da classe mãe se possuir o mesmo nome E assinatura (parametros). Se for apenas o nome igual, será uma sobrecarga.

IV. Um método em uma classe filha sobrecarrega um método da classe mãe caso possua o mesmo nome e parâmetros de entrada diferentes que este método na classe mãe.

V. é obrigatório implementar um método construtor em uma classe, independentemente se a classe mãe possui ou não construtores com ou sem argumentos.

VI. Um atributo privado de uma superclasse não existe nas subclasses. Porém, se os getter e setter deste atributo forem públicos, eles poderão ser utilizados pelas classes filhas.

---

Plataforma JAVA

JMX:

 **é um framework que fornece uma maneira padrão de expor recursos Java.** *A tecnologia JMX fornece uma maneira simples e padrão de gerenciar recursos como aplicativos, dispositivos e serviços.* 

- *Pode monitorar e gerenciar a JVM.*
    - responde quanto e qual recurso o sistema está consumindo.
- *Criado para responder a algumas dúvidas nos sistemas de produção*
- monitorar todas as configurações dos sistemas que estão sendo desenvolvidos.
- para monitorar aplicações e servidores de aplicação.
- **para monitorar acesso padronizado às informações da máquina virtual.**

(JME) **Java Platform Micro Edition = Java para embarcados e móveis.**

Java Message Service (JMS):

- específico para aplicações distribuídas se comunicarem por mensagens.

---

Em JAVA podemos criar variáveis:

*CaseSensitive

Não:

- Iniciar com números
- Iniciar com caracteres especiais, exceto _ ou $.
- Usar espaço
- utilizar palavras reservadas

---

APPLETS

é uma interface gráfica com o usuário em que se pode desenhar ou colocar componentes GUI.

applets são uma pequena aplicação desenvolvida no lado do cliente, em que ele pode manusear uma pequena página dentro de uma página WEB. São aquelas pequenas janelas que se abrem após o browser carregar. Ela só funciona enquanto está na página que lhe dá vida.

Ciclo de vida:

Init, Start, Stop, Destroy

Obs.: Não tem main()

---

Threads

As threads são alocadas por prioridade (necessidade do usuário) e executada aleatoriamente. Não existe fila de thread.

wait : faz a thread esperar por um notify() ou notifyAll() por outra thread.

notify(): acorda uma thread

notifyAll(): acorda todas as threads de um objeto

sleep(): a thread nao fica bloqueada. apenas interrompe sua execução.

---

Ciclo de vida 

![Untitled](Java%20eff99d8c608f437bb9cea403d6e7c39d/Untitled.png)

yield() -:> de running para runnable

runnable só tem o metodo run()

threads podem ter o mesmo nome

---

Caiu muito:

O método scanner nextint **NÃO** é utilizado para se obter um número inteiro que será utilizado numa classe do programa.

---

No Java, um número prefixado com 0 é interpretado como um número octal (base 8)

017 = 15