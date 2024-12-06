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
