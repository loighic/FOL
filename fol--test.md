

~~~{.ProofChecker .magnusQL options="fonts tabindent render" guides="fitch" points="10" late-credit="9"}
2.1 Ex~Fx, Ax(Fx or Gx) :|-: ExGx 
2.2 AxFx :|-: AyFy
2.3 Ax(Fx -> Gx), AxFx :|-: AxGx
2.4 Ax(Fx -> Gx), Fa :|-: Ex(Fx & Gx)
2.5 ExFx :|-: Ex(Fx or Gx)
2.6 Ex(Fx -> P), AxFx :|-: P
2.7 Ex(Fx -> Gx), AxFx :|-: ExGx
2.8 Ex((Fx & Ay(Fy -> y=x)) & Gx), ~Ga :|-: ~Fa
~~~ 

~~~{.ProofChecker .ForallxQL options="fonts tabindent render" guides="fitch" points="10" late-credit="9"}
3.1 Ex~F(x), Ax(F(x) v G(x)) :|-: ExG(x) 
3.2 G(a) <-> H(a), a=d :|-: G(d) <-> H(d)
3.3 Ax(G(x,a) -> x=a), G(b,a) :|-: Ax(G(x,b) -> x=b)
3.4 M(a) \/ N(b), N(b) -> b=d, ~M(a) :|-: N(d)
3.5 a=b, M(b,a) :|-: ExM(x,x)
3.6 Ax(F(x) & G(x)) :|-: AxF(x) 
3.7 AxAyAz((L(x,y) & L(y,z)) -> L(x,z)), L(a,b), L(b,c) :|-: L(a,c)
~~~

<font size="6.5">&#9786;</font>