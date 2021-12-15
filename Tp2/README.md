## Interpolation et approximation polynômiale
### **Polynome d'interpolation de Lagrange**
Étant donné une fonction f

Soient  <img src="https://render.githubusercontent.com/render/math?math=x_0, x_1,">....<img src="https://render.githubusercontent.com/render/math?math=,x_N "> 2 à 2 distincts .

L’objectif de ce TP : est d’interpoler f aux nœuds <img src="https://render.githubusercontent.com/render/math?math=x_0, x_1,">....<img src="https://render.githubusercontent.com/render/math?math=,x_N "> par un polynôme p .

Ce polynôme s’appelé le polynôme d’interpolation de Lagrange
 
Soient <img src="https://render.githubusercontent.com/render/math?math=(x_0,y_0), \ldots,(x_k,y_k),\ldots ,(x_n,k_n)">  ,  n+1 points deux à deux distincts, le polynôme d'interpolation de Lagrange associés à ces points supports est défini par :
> <img src="https://render.githubusercontent.com/render/math?math=\displaystyle P_n(x)=\sum_{k=0}^{n%2B1} y_kL_k(x)">

avec


> <img src="https://render.githubusercontent.com/render/math?math=L_{0}(x)=\displaystyle\frac{(x-x_1)(x-x_2)\ldots(x-x_{n})}{(x_0-x_1)(x_0-x_2)\ldots(x_0-x_{n})}">

et 


> <img src="https://render.githubusercontent.com/render/math?math=L_{k}(x)=\displaystyle\frac{(x-x_1)(x-x_2)\ldots(x-x_{k-1})(x-x_{k%2B1})\ldots(x-x_{n})}{(x_k-x_0)(x_k-x_1)\ldots(x_k-x_{k-1})(x_k-x_{k %2B 1})\ldots(x_k-x_{n})}">


 pour 
 
 > <img src="https://render.githubusercontent.com/render/math?math=k\in \{1,\ldots,n\}">
