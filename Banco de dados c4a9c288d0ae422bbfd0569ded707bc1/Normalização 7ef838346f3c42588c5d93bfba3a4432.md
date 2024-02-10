# Normalização

![Untitled](Normalizac%CC%A7a%CC%83o%207ef838346f3c42588c5d93bfba3a4432/Untitled.png)

Objetivo:  é **minimizar redundâncias no armazenamento de dados.**

[https://pt.stackoverflow.com/questions/151323/o-que-é-normalização-de-banco-de-dados](https://pt.stackoverflow.com/questions/151323/o-que-%c3%a9-normaliza%c3%a7%c3%a3o-de-banco-de-dados)

![Untitled](Normalizac%CC%A7a%CC%83o%207ef838346f3c42588c5d93bfba3a4432/Untitled%201.png)

Obs.:

Existe uma dependência funcional quando um campo pode ser alcançado a partir de outros campos. Chegar no nome pelo CPF(CPF→ nome), sendo CPF uma PK necessariamente.

CPF ou RG+ESTADO são chaves candidatas. Ambas possuem características de PK (únicas e exclusivas).

Para avançar nas FN, é preciso estar na FN anterior.

1FN

Não devem existir colunas multivaloradas. Criar uma nova tabela e relacionar.

2FN

Todas as chaves devem ter dependência total/funcional com a PK. Se a PK for composta, então pode haver dependência parcial.

Uma dependência funcional pode ser dita estar na totalidade da chave primária quando todos os campos da chave primária são necessários para estabelecer-se a relação de dependência.

Importante para ter total dependência da PK: Se alguma chave não depender da PK totalmente, então deve ser gerada uma nova tabela com as chaves. Ex.: Nome do cliente (PK), Nome Funcionario (PK), endereço cliente, valor_contrato. A chave endereço não depende do nome do funcionário, então deve ser criada uma nova tabela com o nome do cliente e seu endereço, removendo a última da tabela antiga.

A 2FN só é aplicável para tabelas que possuam uma chave primária composta e que, além disso, tenham outros atributos que não façam parte da chave primária.

3FN 

Campos dependentes de forma total e somente com as chaves candidatas ou primárias (dependência funcional)

RG → Nome (Nome depende de RG para existir)

Data Nasc x→ Nome (Data NÃO chega no nome, pois nao é unico)

Superchave ≠ chave candidata

Boice Codd (BCNFF) 3.5FN

Nao chegar nas chaves candidatas por meio de outra chave candidata por meio de dependência funcional (x→r)

1fn : nao existir atributos multivalorados

2fn : os campos da entidade devem ter dependência total das chaves primária (candidatas)

Resumidamente, a respeito das formas normais, temos que:

- **Primeira forma normal (1FN)** = diz que uma tabela está na primeira forma normal quando ela contêm atributos atômicos (**indivisíveis**).
    - exige que cada coluna de uma tabela contenha apenas um tipo de informação
    - que exige que cada célula de uma tabela contenha um único valor.
- **Segunda Forma Normal (2FN) = uma tabela encontra-se na segunda forma normal, quando, além de estar na 1FN, não contem dependências parciais (depende de toda a chave primária, e não de parte dela).**
- **Terceira Forma Normal (3FN)** = uma tabela encontra-se na terceira forma normal, quando, além de estar na 2FN, não contém dependências transitivas (**depende somente da chave primária, e de nenhum outro atributo**)
    - Garantir que todas as dependências funcionais estejam satisfeitas em uma tabela.
    - 
- **Forma Normal de Boyce-Codd:** Uma relação está em FNBC se para toda dependência funcional X → Z, X é uma super-chave (**os atributos contêm dependência somente da super-chave, é mais restritiva que a 3FN**)
- **Quarta Forma Normal (4FN)** = Uma relação está na quarta Forma Normal (4FN) se estiver na 3FN e **não contiver dependências multivaloradas.**
- **Quinta Forma Normal (5FN)** = Uma relação está na quarta Forma Normal (5FN) se estiver na 4FN e não contiver **dependências de junção.**

Nota sobre dependência funcional:

Uma coluna determinante tem valores únicos que apontam para a sua dependência (como uma função afim, em que cada valor x aponta para um valor y. y pode ter valores repetidos, mas x não.)