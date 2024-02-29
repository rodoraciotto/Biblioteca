***
|  | Empréstimo de Livro |
| :---: | :---: |
| Atores | Aluno, Bibliotecário |
| Sumário |  Registrar o processo de empréstimo de um livro por parte de um aluno na biblioteca da faculdade. |
| Pré-Condições | O aluno deve estar matriculado na faculdade. |
| Pós-Condições | O aluno recebe o livro emprestado, devidamente registrado em seu nome.O sistema da biblioteca é atualizado com as informações do empréstimo. |

## Fluxo Principal
<PRE>
1. O aluno se dirige ao balcão de atendimento da biblioteca
2. O bibliotecário pede a identificação do aluno
3. O aluno apresenta sua identificação estudantil ou outro meio de identificação válido.
4. O bibliotecário verifica a identidade do aluno e confirma sua matrícula na faculdade.
5. O aluno informa ao bibliotecário o livro que deseja emprestar.
6. O bibliotecário busca o livro no sistema da biblioteca para verificar a disponibilidade.
7. Se o livro estiver disponível:
	7.1 O bibliotecário registra o empréstimo do livro para o aluno.
	7.2 O aluno recebe o livro emprestado.
8.  Fim do caso de uso

</PRE>

## Fluxo Alternativo 1 (Livro Emprestado)
<PRE>
7. Se o livro não estiver disponível:
	7.1 O bibliotecário informa ao aluno sobre a indisponibilidade do livro.
	7.2 O bibliotecário pode oferecer alternativas, como reservar o livro ou sugerir outro título semelhante.
</PRE>

