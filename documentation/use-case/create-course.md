# Criação de Curso

> ## Dados
* Nome do curso
* Descrição do curso
* Administrador 

> ## Fluxo primário
1.  O administrador acessa a plataforma e seleciona a opção de criar um novo curso.
2.  O administrador insere o nome, descrição.
3.  O sistema valida as informações inseridas.
4.  O sistema cria o curso.
5.  Retornar uma confirmação da criação do curso.

> ## Fluxo alternativo: Dados inválidos ou incompletos
3.  O sistema exibe uma mensagem de erro solicitando a correção dos dados.
4.  O administrador corrige os dados e tenta novamente.

> ## Fluxo de exceção: Falha na criação do curso
1.  O sistema exibe uma mensagem de erro e não cria o curso.
