# Book-Author-Dewey
relation between Dewey numbers of the same author

Un esempio di inferenza sui dati può essere la seguente:

Database:
<table>
<td>Author</td> <td>ex:write</td> <td>book</td> .
<td>book</td> <td>ex:hasDewey</td> <td>number</td>
</table>
E' possibile fare un'inferenza tale:
Author1 ex:write book1.
book1 ex:hasDewey number1
Author 1 ex:write book2
book2 ex:hasDewey number2

number1 and number2 sono correlati. Molto spesso, non sempre, ma nei libri successivi un autore parla di cose correlate con i libri precedenti. Molto spessso i libri successivi sono la continuazione dei precedenti.
