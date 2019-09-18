---
layout: post
title: Mi segundo BLOG!
---
Empezamos con algo de series de tiempo...

**Teorema.(Teorema de Takens)** Sean $$M$$ una variedad compacta de dimensión $$m$$, $$\varphi:M\to M$$ un difeomorfismo suave y $$f:M\to\mathbb{R}$$ una función suave. La función $$\Phi_{(\varphi,f)}:M\to\mathbb{R}^{2m+1}$$ definida por	
$$\Phi_{(\varphi,f)}(x):=\left(f(x),f(\varphi(x)),\ldots,f(\varphi^{2m}(x))\right)$$ es un embebimiento para genéricas $$( \varphi,f )$$.

Empezamos haciendo las siguientes dos suposiciones para solventar problemas iniciales: 
* Si $$x$$ es un punto periódico, de período $$k\leq 2m+1$$, de $$\varphi$$ los autovalores de $$(d\varphi^k)_x$$ son diferentes y ninguno es 1.
* Puntos fijos de $$\varphi$$ no están en el mismo nivel bajo $$f$$, es decir, si $$x$$, $$y$$ son puntos fijos: $$f(x)\neq f(y)$$  

En efecto, si se descarta ii) $$\varPhi_{(\varphi,f)}$$ deja de ser inyectiva. Mientras que si en i) no fuese cierto lo de tener diferentes autovalores, $$\varPhi_{(\varphi,f)}$$ no es una inmersión: Si $$x\in M$$ es un punto fijo de $$\varphi$$, sean $$v_1,v_2$$ dos autovectores de $$d\varphi_x$$ que tienen el mismo autovalor $$\lambda$$. Luego existen $$c_1,c_2$$ constantes tal que $$c_1T_xf(v_1)+c_2T_xf(v_2)=0$$ y para todo $$k$$:
		$$d(f\circ\varphi^k)_x(u)=df(d\varphi^k)_x(u)=(df)_x(\lambda^ku)=\lambda^kdf_x(u)=0$$
De manera análoga si $$x$$ es de período $$k\leq2m+1$$. Por otra parte, La hipótesis de que los autovalores sean distintos a uno tiene como objetivo lo siguiente:
