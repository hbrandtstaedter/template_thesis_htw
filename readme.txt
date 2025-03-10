Dies ist die inoffizielle Abschlussarbeitsvorlage von Heide Brandstädter. Sie umfasst eine LaTeX Vorlage welche wie folgt aufgebaut ist.

Diese Vorlage ist bereits sehr stark Modular aufgebaut, daher soll hier zunächst ein minimalaufbau eines LaTeX Dokuments aufgezeigt werden. Die Beschreibung dieser Vorlage ist weiter unten zu finden.

Zusätzlich gibt es diverse Videoreihen welche eine Einführung in LaTeX zeigen, z.B. diese:
--------------------------------------------------------
https://youtube.com/playlist?list=PLHXZ9OQGMqxcWWkx2DMnQmj5os2X5ZR73&si=z8-vbIxXxNkBo1ii
--------------------------------------------------------





---------------------------------------------------------
--------------- Grundlagenbeschreibung ------------------
---------------------------------------------------------
LaTeX Dokument sind in ihrer einfachsten Form wie folgt aufgebaut:

% Startbefehl für ein Dokument, mit zusätzlichen Einstellungen in den eckigen Klammern [] und der Dokumentart in den geschweiften Klammern {}. 
%\documentclass[12pt,a4paper,oneside]{scrartcl}


% Einbindung von Packages für weitere Dokumentfunktionen
\usepackage{amsmath}
\usepackage{amssymb}
\usepackage{amsfonts}

% Beginn des schriftlichen Dokuments
\begin{document}


\end{document}
---------------------------------------------------------
---------------------------------------------------------
---------------------------------------------------------





---------------------------------------------------------
-------------- Vorlage Heide Brandstädter ---------------
---------------------------------------------------------

In LaTeX ist es möglich .tex Files in andere .tex Files einzubinden. Dies ermöglicht einen modularen Aufbau seiner Dokumente. So kann z.B. jedes Kapitel in einem separaten .tex File geschrieben werden und dann durch den \input{} Befehl in ein übergeordnetes .tex File eingebunden werden. Die fördert bei großen Dokumenten die Übersichtlichkeit.

--------------------------------------------------------
Die wichtigsten .tex Files in dieser Vorlage sind hier aufgelistet:
_________________________________________________
00 main_thesis.tex: 
Dieses file ist das Hauptfile. Es bindet andere .tex files ein. Darunter die title.tex welches die Titelseite enthält, sperrvermerk.tex für den Sperrvermerkt, einleitung.tex, ... etc. im 00 main_tesis.tex ist dies durch den Befehl \input{} zu sehen. 
_________________________________________________
format_thesis.tex:
Dieses file enthält zusätzliche Formatierungen für das Dokument darunter z.B. eine Anpassung der Zeilenabstände. 
_________________________________________________
makro_header.tex:
In LaTeX ist es üblich für zusätzliche funktionen sogenannte "packages" einzubinden. Diese erlauben zusätzliche Funktionen in das Dokument zu integrieren. Als Beisiel: ""\usepackage{url, hyperref}" ermöglicht die Integration von Dokumentinternen Verlinkungen von Referenzen sowie die Verlinkung von urls.

---------------------------------------------------------
---------------------------------------------------------
---------------------------------------------------------