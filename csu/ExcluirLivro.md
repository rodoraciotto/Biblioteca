Aluno: Rodrigo Moreira Doraciotto  
RA: 22.221.022-1
***
|  | Excluir Livro |
| :---: | :---: |
| Atores | Bibliotecário |
| Sumário |  Bibliotecário excluir um livro cadastrado |
| Pré-Condições | Possuir livro cadastrado |
| Pós-Condições | Exclui um livro do acervo |

## Fluxo Principal
<PRE>
1. O Bíbliotecário acessa o sistema
2. O Bíbliotecário pede ao sistema uma lista dos livros cadastrados
3. O sistema apresenta uma lista de livros cadastrados.
4. O Bibliotecário seleciona um livro que queria excluir
5. O sistema exibe as informações do livro selecionado.
6. O sistema pergunta se o bibliotecário quer excluir o livro.
7. O Bibliotecário confirma a exclusão do livro
8. O sistema verifica se o livro está sendo emprestado
9. Se o livro não estiver sendo emprestado o sistema exclui o livro
10. O sistema informa o bibliotecário do sucesso 
11. Fim do caso de uso

</PRE>
## Fluxo Alternativo 1 (Livro Emprestado)
<PRE>
8.1 O sistema informa sobre a não exclusão do livro pois está sendo emprestado no momento
8.2 Fim do caso de uso
</PRE>

## Fluxo de Exceção
<PRE>

</PRE>