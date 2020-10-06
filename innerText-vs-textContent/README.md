# innerText-vs-textContent
Die beiden Javascript Funktionen innerText und textContent werden oft fälschlicherweise äquivalent verwendet. In diesem kleinen Repo werden die Unterschiede erläutert. 

Alle Beispiele sind im Dokument "innerText-vs-textContent-javascript-tests.html" abgelegt und kommentiert.

## Zusammenfassung
innerText enthält nur was im Browser sichtbar ist. Beim Schreiben werden LineBreaks zu br-Tags umgewandelt.
textContent enthält alles was tatsächlich vorhanden ist (ausser HTML-Tags selbst). Beim Schreiben wird der Inhalt genau so eingefüt wie er ist.

## Fazit
Wenn mit LineBreaks gearbeitet oder der rein sichtbare Text gebraucht wird, ist innerText einfacher, da es die Arbeit bereits macht.
Möchte man den Text genau so wie er ist oder es handelt sich nur um einzelne Wörter (ohne LineBreaks oder WhiteSpaces) ist textContent besser geeignet und schneller.
