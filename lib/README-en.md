<!-- Title -->
<div align="center">
    <h1><b>Template of Exercise List of UNICHRISTUS</b></h1>
</div>

<!-- Table of Contents -->
<p align="center">
    <a href="#description">Description</a> •
    <a href="#commands">Commands</a> •
    <a href="#tips">Tips</a> •
    <a href="#changelog">Changelog</a> •
    <a href="#author">Author</a>
</p>

<p align="center"><button href="README.md">README in Portuguese</button></p>

<!-- section -->
## Description
<hr/>
<p> This project aims to develop a template for exercise list in LaTeX for UNICHRISTUS. It was created a class file called **unichristusdoc** to reach this goal. This class file has a set of environment and commands relation to the document.

This document is intended for professor at UNICHRISTUS who wish use a LaTeX template for their exercise list.</p>


## Commands
<hr/>
<b>To insert a new question:</b> use the command *\problem* to insert a new question in your list.

```tex
\problem First question of the exercise list.

\problem Second question of exercise list.
```

<b>To insert a subquestion (items of the question):</b> use the command *\subproblem* after the command *\problem*.

```tex
\problem First question of exercise list.
    \subproblem First subitem
    \subproblem Second subitem.
    \subproblem Third subitem.
...
```

<b>To insert a pontuation:</b> use the command *\points{}* to insert the pontuation.

```tex
\problem First question of the exercise list. \points{3.5}
```

## Tips
<hr/>
<p> The instructions can be adjusted by the user of the template. For this, it must go to *main.tex* file and modify the items between the commands *\begin{instlis}* and *\end{instlist}*.</p>

<p>The user must to change the content of information table (table located in the top of template). The fields are adaptable to the user data. </p>

## Changelog
<hr/>
[Changelog File](/CHANGELOG.md)

## Author
<hr/>

Developed by <b>Maurício Moreira Neto</b> :shipit: 

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mauricio.moreira@unichristus.edu.br)[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/maumneto)[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maumneto/)[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@maumneto)[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/profmauricioneto)