# Projeto-Modulo4
Projeto modelo de Banco de Dados

Aviso: Não consegui utilizar o Mysql pois o mesmo encontra-se em conflito com meu computador pessoal, espero que entendam!

Existem entidades além dessas 3?
Para mim nesse tipo de modelagem proposto no projeto requer muito mais entidades principais, por isso considero as cinco que criei pois todas elas estão ligadas umas nas outras. Entidades: Cursos, matrículas, alunos, professores, turmas.


Quais são os principais campos e tipos?

id -  Tipo inteiro
valor do tipo Double (armazena números)
email do tipo Varchar(campo de caracteres)
cpf do tipo Varchar(campo de caracteres)
datainicio/datafim do tipo Date (armazena hora e data)
carga horária do tipo Smallint (armazena pequenos números)
ps: Menção honrosa a pesquisa que fiz para determinar os tipos e para que eles servem!

Como essas entidades estão relacionadas?

Iniciei criando as entidades curso e seus atributos, depois criei alunos, turmas, matrículas, professores, turmas e os atributos.

Iniciei com a relação dos alunos no curso de 1 para muitos no curso e 1 para cada um uma  matrícula no curso escolhido. Assim mantendo a lógica do banco de dados. Depois estabeleci a relação entre turmas, alunos e cursos de 1 para muitos pois a Resilia tem muito cursos e muitos alunos e turmas. Finalizando criei relação entre professores, turmas, e cursos numa relação que cada turma possui um professor, cada curso tem um professor e assim encerrei meu projeto e fiz o modelo no br modelo!
