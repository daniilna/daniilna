\documentclass[14pt,a4paper,report]{ncc}
\usepackage[a4paper, mag=1000, left=2.5cm, right=1cm, top=2cm, bottom=2cm, headsep=0.7cm, footskip=1cm]{geometry}
\usepackage[utf8]{inputenc}
\usepackage[english,russian]{babel}
\usepackage{indentfirst}
\usepackage[dvipsnames]{xcolor}
\usepackage[colorlinks]{hyperref}
\usepackage{listings} 
\usepackage{caption}
\DeclareCaptionFont{white}{\color{white}} 
\DeclareCaptionFormat{listing}{\colorbox{gray}{\parbox{\textwidth}{#1#2#3}}}
\captionsetup[lstlisting]{format=listing,labelfont=white,textfont=white}
\lstset{% Собственно настройки вида листинга
inputencoding=utf8, extendedchars=\true, keepspaces = true, % поддержка кириллицы и пробелов в комментариях
language=Pascal,            % выбор языка для подсветки (здесь это Pascal)
basicstyle=\small\sffamily, % размер и начертание шрифта для подсветки кода
numbers=left,               % где поставить нумерацию строк (слева\справа)
numberstyle=\tiny,          % размер шрифта для номеров строк
stepnumber=1,               % размер шага между двумя номерами строк
numbersep=5pt,              % как далеко отстоят номера строк от подсвечиваемого кода
backgroundcolor=\color{white}, % цвет фона подсветки - используем \usepackage{color}
showspaces=false,           % показывать или нет пробелы специальными отступами
showstringspaces=false,     % показывать или нет пробелы в строках
showtabs=false,             % показывать или нет табуляцию в строках
frame=single,               % рисовать рамку вокруг кода
tabsize=2,                  % размер табуляции по умолчанию равен 2 пробелам
captionpos=t,               % позиция заголовка вверху [t] или внизу [b] 
breaklines=true,            % автоматически переносить строки (да\нет)
breakatwhitespace=false,    % переносить строки только если есть пробел
escapeinside={\%*}{*)}      % если нужно добавить комментарии в коде
}
\begin{document}

% Оформление титульного листа
\begin{titlepage}
\begin{center}
\textsc « МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ
РОССИЙСКОЙ ФЕДЕРАЦИИ»\\[5mm]
Федеральное государственное бюджетное образовательное учреждение высшего образования
АДЫГЕЙСКИЙГОСУДАРСТВЕННЫЙУНИВЕРСИТЕТ\\[2mm]
Инженерно-физический факультет

Кафедра автоматизированных систем обработки информации и управления}

\vfill

\textbf{Отчет по практике\\[3mm]
«Программаная реализация численного метода»\\[6mm]
Вариант 6
\\[20mm]
}
\end{center}

\hfill
\begin{minipage}{.5\textwidth}
1 курс, группа 1ИВТ2\\[2mm] 
Выполнил:\\
Д.В. Васильев  2023 г\\[5mm]

Руководитель:\\[2mm] 
С.В. Теплоухов   2023 г\\

\end{minipage}%
\vfill
\begin{center}
 Майкоп, \theyear\ г.
\end{center}
\end{titlepage}

\end{document}
