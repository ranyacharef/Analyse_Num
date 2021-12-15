# Projet 
- [Introduction](#Introduction)
- [Démonstration](#Démonstration)
- [Méthode :](#Méthode) <br/>
-[réctangles ](#réctangles ) <br/>
-[trapèzes](#trapèzes)<br/>
-[Simpson ](#Simpson)
## Introduction :
Supposons qu'on veuille intégrer une fonction f(x) sur un intervalle [a,b]. Puisque
l'intégrale est la limite de sommes de Riemann, l'idée la plus évidente pour approximer
numériquement le résultat qu'on cherche est de calculer des sommes de Riemann en
espérant qu'elles s'approcheront de manière désirée de la réponse exacte à condition de
prendre les sous-intervalles suffisamment petits.
Découpons donc l'intervalle [a, b] en n sous-intervalles [x<sub>i-1</sub>,x<sub>i</sub>] de largeur : <br/>
<img src="https://render.githubusercontent.com/render/math?math=d(x)=\displaystyle\frac{(b-a)}{n}">
## Démonstration : 
<img src="https://github.com/SarahSabbagh/Analyse_Num/blob/main/projet/img/demo.gif" alt="démonstration" width="800" height="400">
## Méthode :
#### -réctangles :
Le principe de cette technique est illustré dans la figure (3.1)
L’expression de l’intégrale devient :<br/>
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{2}\sum_{i=1}^{n} f(x_{i%2B1} + x_i)f(x_i)"> <br/>
On considère le point milieu de chaque sous intervalle pour augmenter la précision.<br/>
L’expression de l’intégrale devient dans ce cas : <br/>
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{2}\sum_{i=1}^{n} f(\frac{x_{i%2B1} + x_i}{x_i})"><br/>
<img src="https://github.com/SarahSabbagh/Analyse_Num/blob/main/Tp3/img/Rectangle.gif" alt="Méthode de rectangle" width="800" height="400">

#### -trapèzes :
Le principe de l’approximation d’une intégrale par la méthode des trapèzes est
illustré dans la figure(III.2).
La formule générale de l’intégrale par la méthode des trapèzes s’écrit :<br/>
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{2}\sum_{i=1}^{n} (f(x_{i%2B1}) + f(x_i))"><br/>
<img src="https://github.com/SarahSabbagh/Analyse_Num/blob/main/Tp3/img/Trapéze.gif" alt="Méthode de trapéze" width="800" height="400">

#### -Simpson :
Le principe de l’approximation d’une intégrale par la méthode de Simpson est
illustré dans la figure ci-dessous :
Figure III.3 : Principe de la méthode de Simpson
La formule générale de l’intégrale par la méthode de Simpson s’écrit :<br/>
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{3}[f(a)%2B4\sum_{i=2,4,6}^{n}f(x_i)%2B2\sum_{i=1,3,5}^{n-1}f(x_i)%2Bf(b)"> <br/>
<img src="https://github.com/SarahSabbagh/Analyse_Num/blob/main/Tp3/img//Simpson.gif" alt="Méthode de simpson" width="800" height="400">
