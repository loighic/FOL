---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## first-order logic, assignment 02 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
18.1 N <-> Q, ~Q :|-: ~N
~~~

Notice that the main logical operator in &not;(P &rarr; Q) is the &not;. Hence, you can't use the conditional introduction rule to get the conclusion. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
18.2 P & ~Q :|-: ~(P -> Q)
~~~


~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
18.3 Ax(Fx -> Gx), Fa :|-: Ex(Fx & Gx)
18.4 (Fa v Qc) -> AxGx, AxFx :|-: Ex(Gx v Px)
18.5 AzRz, Ay(Sy <-> Ry), Sa -> Wa :|-: ExWx
~~~ 