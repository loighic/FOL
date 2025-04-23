---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## first-order logic, assignment 03 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
20.1 N <-> Q, ~Q :|-: ~N
~~~

Notice that the main logical operator in &not;(P &rarr; Q) is the &not;. Hence, you can't use the conditional introduction rule to get the conclusion. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
20.2 P & ~Q :|-: ~(P -> Q)
~~~


~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="17"}
20.3 Ax(Fx -> Gx), Fa :|-: Ex(Fx & Gx)
20.4 (Fa v Qc) -> AxGx, AxFx :|-: ExGx v Px
20.5 Ey(Fy v Qy) -> AxGx, AxFx :|-: Ax(Fx & Gx)
~~~ 

<p>&copy; 2022 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>