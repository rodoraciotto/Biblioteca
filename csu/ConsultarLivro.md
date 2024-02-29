***
|  | Consultar Livro |
| :---: | :---: |
| Atores | Aluno, Bibliotecário |
| Sumário |  Permitir que os autores verifiquem a disponibilidade de um livro específico na biblioteca da faculdade. |
| Pré-Condições | Ter livro cadastrado. O Aluno deve estar matriculado na faculdade |
| Pós-Condições | O aluno recebe o livro emprestado, devidamente registrado em seu nome.O sistema da biblioteca é atualizado com as informações do empréstimo. |

## Fluxo Principale
<PRE>
1. O Autor acessa o sistema por meio de suas credenciais
2. O Autor pede ao sistema para consultar livros.
3. O Sistema apresenta um formulário para preencher com as informações do livro
4. O Autor insere o título, autor ou outra informação relevante do livro que deseja consultar.
5. O sistema da biblioteca realiza a busca pelo livro no catálogo.
6. Se o livro estiver disponível:
	6.1 O sistema exibe as informações sobre o livro, como título, autor, edição, disponibilidade e cópias.
	6.2 O Autor pode verificar a localização física do livro na biblioteca, se disponível no sistema.
7. Fim do Caso de uso
</PRE>

## Fluxo Alternativo 1 (Livro não Encontrado)
<PRE>
5. Se o sistema não encontrar o livro procurado:
	5.1 O sistema informa o autor sobre o não encontrar o livro
    5.2 O sistema pede para o autor preencher mais campos do formulário para melhorar a busca
</PRE>

## Fluxo Alternativo 2 (Livro não Disponível)
<PRE>
6. Se o livro não estiver disponível:
	6.1 O sistema informa ao aluno sobre a indisponibilidade do livro
</PRE>


