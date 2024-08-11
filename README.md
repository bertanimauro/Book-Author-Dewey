# Book-Author-Dewey
relation between Dewey numbers of the same author

Un esempio di inferenza sui dati può essere la seguente:

Database:

<table>
<tr></tr><td>Author</td> <td>ex:write</td> <td>book</td><tr>
<tr></tr><td>book</td> <td>ex:hasDewey</td> <td>number</td></tr>
</table>

E' possibile fare un'inferenza tale:

<table>
<tr></tr><td>Author1</td> <td>ex:write</td> <td>book1</td><tr>
<tr></tr><td>book1</td> <td>ex:hasDewey</td> <td>number1</td></tr>
<tr></tr><td>Author1</td> <td>ex:write</td> <td>book2</td><tr>
<tr></tr><td>book2</td> <td>ex:hasDewey</td> <td>number2</td></tr>
</table>

number1 and number2 sono correlati. Molto spesso, non sempre, ma nei libri successivi un autore parla di cose correlate con i libri precedenti. Molto spessso i libri successivi sono la continuazione dei precedenti.

Nel file authorAB1970-Author-Dewey.cvs gli autori con il relativo numero dewey dei loro libri.
Nel file authorAB1970-reletionMaterie.cvs le relazioni tra le classi Dewey
