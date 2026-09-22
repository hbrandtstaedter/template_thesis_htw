Dies ist die inoffizielle Abschlussarbeitsvorlage von Heide Brandstädter. Sie umfasst eine LaTeX Vorlage.


---------------------------------------------------------
-------------- Vorlage Heide Brandstädter ---------------
---------------------------------------------------------

In LaTeX ist es möglich .tex Files in andere .tex Files einzubinden. Dies ermöglicht einen modularen Aufbau seiner Dokumente. So kann z.B. jedes Kapitel in einem separaten .tex File geschrieben werden und dann durch den \input{} Befehl in ein übergeordnetes .tex File eingebunden werden. Die fördert bei großen Dokumenten die Übersichtlichkeit.

--------------------------------------------------------
Die wichtigsten .tex Files in dieser Vorlage sind hier aufgelistet:
_________________________________________________
00 main_thesis.tex: 
Dieses file ist das Hauptfile. Es bindet andere .tex files ein. Darunter die title.tex welches die Titelseite enthält, sperrvermerk.tex für den Sperrvermerkt, einleitung.tex, ... etc. im 00 main_tesis.tex ist dies durch den Befehl \input{} zu sehen. 
_hb.tex sind Dateien, die Inhalte von HB enthalten. (Leitaden zum ERstellen einer Abschlussarbeit)
_student.tex sollen vom Nutzenden anstelle der _hbtex Dateien gefült und eingebunden werden. 

_________________________________________________
format_thesis.tex:
Dieses file enthält zusätzliche Formatierungen für das Dokument darunter z.B. eine Anpassung der Zeilenabstände. 
_________________________________________________
makro_header.tex:
In LaTeX ist es üblich für zusätzliche funktionen sogenannte "packages" einzubinden. Diese erlauben zusätzliche Funktionen in das Dokument zu integrieren. Als Beisiel: ""\usepackage{url, hyperref}" ermöglicht die Integration von Dokumentinternen Verlinkungen von Referenzen sowie die Verlinkung von urls.

_________________________________________________
makro_style.tex:
In LaTeX ist es möglich, individuelle Kurzbefehle und Styles zu definieren.


---------------------------------------------------------
---------------------------------------------------------
---------------------------------------------------------
