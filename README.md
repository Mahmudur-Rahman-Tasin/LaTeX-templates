# LaTeX-templates

Great introduction.

Some tip: If you want to use \LaTeX{} to write a documentation in some other language then English, you actually also want to use package babel. So this is for Swedish:

\documentclass[sv,a4paper]{article} % swedish and A4 paper format for the article
\usepackage[utf8]{inputenc}               % use UTF-8, as you all should do nowdays
\usepackage[T1]{fontenc}                    % Adjust fonts in result so it will show you the right characters
\usepackage[swedish]{babel}              % And set \LaTeX{} to use Swedish language.\


\begin{equation}\begin{aligned} is very useful for making multi-line aligned equations (use '&' to align, and \\ to break the lines)


