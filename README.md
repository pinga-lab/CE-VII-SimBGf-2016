# Camada equivalente aplicada ao processamento e interpretação de dados de campos potenciais

Material do minicurso oferecido no [VII SimBGf](http://www.sociedadebrasdegeofisica.com.br/simposio/index.php?option=com_content&view=article&id=103&Itemid=435)

## Responsável

**Vanderlei C. Oliveira Jr.**

Possui graduação em geofísica no [Instituto de Astronomia, Geofísica e
Ciências Atmosféricas](http://iag.usp.br/) 
da [Universidade de São Paulo](http://www5.usp.br/) (2008), mestrado 
em geofísica pelo [Observatório Nacional](http://www.on.br/)
 (2010) e doutorado em geofísica pelo 
Observatório Nacional (2013). Atualmente é pesquisador no departamento de 
geofísica do Observatório Nacional. Tem experiência em geofísica aplicada, 
com ênfase em métodos potenciais, modelagem e inversão.

Para mais informações:

* [PINGAlab](http://www.pinga-lab.org/people/oliveira-jr.html)
* [ORCID](http://orcid.org/0000-0002-6338-4086)
* [ResearcherID](http://www.researcherid.com/rid/E-1871-2013)
* [Google Scholar](https://scholar.google.com.br/citations?user=TQbQ4TcAAAAJ)
* [Currículo Lattes](http://lattes.cnpq.br/4332841435949533)
* [ResearchGate](https://www.researchgate.net/researcher/2021325258_Vanderlei_C_Oliveira_Jr/)
* [GitHub](https://github.com/birocoles)

## Ementa

1. Introdução
2. Fundamentos matemáticos
3. Camada equivalente clássica
4. Aspectos computacionais
5. Aplicações

## Objetivo

Apresentar a técnica da Camada Equivalente como alternativa para o 
processamento e interpretação de dados gravimétricos
e magnetométricos. Apresentar exemplos de aplicações a dados 
sintéticos e reais com o pacote [Fatiando a Terra](http://www.fatiando.org/).

## Público-alvo

Graduandos e pós-graduandos das áreas de Ciências Exatas e da Terra 
e profissionais de áreas afins.

## Requisitos

Conceitos de métodos potenciais (gravimetria e magnetometria), cálculo 
diferencial/integral, álgebra linear e física. Conhecimentos básicos 
de programação.

## Sobre esta página estranha

Esta página é um repositório no GitHub. Mas que raio é isso?
Pois é, muita gente ao redor do mundo tem utilizado o Git e o GitHub para
fazer colaborações em suas pesquisas, divulgar a pesquisa, divulgar
o material desenvolvido em disciplinas, palestras, seminários, etc.
Aos interessados em Git/GitHub, abaixo segue uma
lista de links que eu considero úteis:

* [Tudo que você queria saber sobre Git e GitHub, mas tinha vergonha de perguntar]
(http://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)

* [Git e Github para Iniciantes](http://willianjusten.teachable.com/courses/git-e-github-para-iniciantes)

* [tryGit - Got 15 minutes and want to learn Git?](https://try.github.io/levels/1/challenges/1)

* [Good Resources for Learning Git and GitHub](https://help.github.com/articles/good-resources-for-learning-git-and-github/)

* [Software Carpentry - Version Control with Git](http://swcarpentry.github.io/git-novice/)

## A linguagem Python

Diferentemente de C ou Fortran, a linguagem [Python](https://www.python.org/) 
é interpretada. Isso signififca que o código não precisa ser previamente 
compilado e os comandos são executados imediatamente. De acordo com a 
[Software Carpentry](http://software-carpentry.org/index.html), quando 
estamos programando, o tempo total necessário para obtermos a solução 
desejada é determinado por duas coisas: *o tempo gasto por* **você** *para 
desenvolver o código* e *o tempo gasto pelo* **computador** *para rodar o 
código*. Estes fatores devem ser levados em consideração no momento da 
escolha de uma linguagem de programação. Para fins acadêmicos de pesquisa 
e ensino, a linguagem Python oferece algumas vantagens, dentre as quais 
eu destaco o fato de ser gratuita e distribuída livremente na internet, 
relativamente fácil de aprender e extremamente bem documentada.

Para mais informações, eu recomendo (fortemente) que você acesse o site 
da [Software Carpentry](http://software-carpentry.org/index.html). Mais 
especificamente, dê uma olhada nas lições [Programming with Python] 
(http://swcarpentry.github.io/python-novice-inflammation/). 
Os códigos Python serão feitos utilizando-se o [Jupyter Notebook]
(http://jupyter.org/).

## Jupyter Notebook

O [Jupyter Notebook](http://jupyter.readthedocs.org/) é um
arquivo com extensão `.ipynb` e
permite combinar código, texto, equações feitas em 
LaTeX, figuras e animações. Além disso, 
é gratuito e extremamente bem documentado. Esta poderosa feramenta computacional 
possibilita reunir (quase) todas as etapas envolvidas no desenvolvimento de 
um código com fins acadêmicos, desde a leitura e processamento dos dados até a 
visualização dos resultados. Para informações sobre o Jupyter Notebook, 
acesse http://jupyter-notebook.readthedocs.io/en/latest/notebook.html

## Instalação do Python e de suas dependências

Uma maneira fácil de baixar e instalar a última versão do Python e de suas 
dependências é utilizar a distribuição [Anaconda](http://continuum.io/downloads), 
da [Continuum Analytics](http://continuum.io/). Para tanto, 
acesse o link do [Anaconda](http://continuum.io/downloads), 
escolha o instalador `PYTHON 2.X` adequado para o seu sistema
operacional e siga as instruções. O Anaconda já vem com quase tudo o que você 
precisa para fazer os seus primeiros códigos.

Por qual motivo escolher o instalador `PYTHON 2.X` ao invés do `PYTHON 3.X`?
Simples, os códigos deste curso usam a biblioteca [Fatiando a Terra](http://www.fatiando.org/) 
que, por sua vez, é desenvolvida para `PYTHON 2.X`.

## Biblioteca Fatiando a Terra

O [Fatiando a Terra](http://www.fatiando.org/) é uma biblioteca de acesso livre
que é desenvolvida em linguagem Python. Esta biblioteca possibilita a
modelagem a inversão de dados geofísicos. Os códigos desenvolvidos
neste minicurso utilizam esta biblioteca e, portanto, é necessário
instalá-la para poder rodá-los. Para tanto, siga as instruções no
link http://www.fatiando.org/install.html#.