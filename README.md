# Packages
L02 - Lista de exercício Packages

# Como executar
1. Acesse o LiveSQL: https://livesql.oracle.com/ords/f?p=590:1000

2. Após efetuar o login clique em "my scripts" -> "Upload Script" -> "Choose File" -> Escolha o arquivo "Packages.slq" -> Dê um nome e clique em "Upload Script".

# Função dos pacotes
1. Pacote PKG_ALUNO
   
   Procedures:
    exclui_aluno: Exclui um aluno específico e suas matrículas associadas com base no id_aluno.

   Cursores:
   
     maioridade: Lista os alunos maiores de 18 anos com seus nomes e datas de nascimento.
   
     aluno_no_curso: Lista os nomes dos alunos matriculados em um curso específico (filtrando pelo id_curso).

2. Pacote PKG_DISCIPLINA
   
   Procedures:

   cadastrar_disciplina: Cadastra uma nova disciplina no banco de dados com os parâmetros nome, descrição e carga horária.
   
   listar_alunos_disciplina: Lista todos os alunos matriculados em uma disciplina específica com base no id_disciplina.

   Cursores:

   disciplina10: Lista disciplinas com mais de 10 alunos matriculados, exibindo o nome da disciplina e o total de alunos.
   
   idade_media: Calcula a média de idade dos alunos matriculados em uma disciplina específica.

3. Pacote PKG_PROFESSOR

   Cursores:

   professor_turma: Lista os professores que possuem mais de uma turma, mostrando o nome do professor e o total de turmas associadas.
   
   Functions:

   total_turma: Retorna o número total de turmas associadas a um professor, com base no id_professor.
   
   professor_da_disciplina: Retorna o nome do professor responsável por uma disciplina específica, com base no id_disciplina.
