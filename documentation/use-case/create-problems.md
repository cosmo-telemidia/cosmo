# Criação de Questões

> ## Dados
* Titulo da questão
* Descrição da questão
* Exemplos de entrada/saída
* Declaração Da Função
* Função de teste
* Restrição da Questão
* Dificuldade da questão

> ## Fluxo primário
1.  O Administrador acessa o tópico previamente criado e seleciona a opção de adicionar uma nova questão.
2.  O Administrador insere o enunciado da questão, exemplos de entrada/saída, função de teste, declaração da função, restrição da questão e define a dificuldade.
3.  O sistema valida as informações inseridas.      
4.  O sistema cria a questão e a associa ao tópico.
5.  Retornar uma confirmação da criação da questão.

> ## Fluxo alternativo: Dados inválidos ou incompletos
3.  O sistema exibe uma mensagem de erro solicitando a correção dos dados.
4.  O Administrador corrige os dados e tenta novamente.

> ## Fluxo de exceção: Falha na criação da questão
1.  O sistema exibe uma mensagem de erro e não cria a questão.