---
js: https://carnap.io/shared/gregory.s.johnson@gmail.com/copy.js
--- 

## first-order logic, assignment 02 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
20.1 N <-> Q, ~Q :|-: ~N
~~~

Notice that the main logical operator in &not;(P &rarr; Q) is the &not;. Hence, you can't use the conditional introduction rule to get the conclusion. 

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
20.2 P & ~Q :|-: ~(P -> Q)
~~~

---

**FOL short proofs**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
20.3 AxMx :|-: Ma
20.4 Az(Lz -> Mz) :|-: Lc -> Mc
20.5 Fa :|-: EzFz
20.6 Da v Ka :|-: Ex(Dx v Kx)
20.7 Pe	:|-: Ey(Ly v Py)
~~~

---

**FOL main problems**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="10" late-credit="7"}
20.8 Ax(Fx -> Gx), Fa :|-: Ex(Fx & Gx)
|1.Ax(Fx -> Gx)	:PR
|2.Fa		:PR
|3.Fa -> Ga	:AE 1
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
20.9 (Fa v Qc) -> AxGx, AxFx :|-: Ex(Gx v Px)
|1.(Fa v Qc) -> AxGx	:PR
|2.AxFx			:PR
|3.Fa			:AE 2
|4.Fa v Qc			:vI
~~~

If you're not sure how to begin, start by doing universal elimination (if that's an option). In 20.10, you can do universal elimination with the sentence on line 1 and the one on line 2.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="16"}
20.10 AzRz, Ay(Sy <-> Ry), Sa -> Wa :|-: ExWx
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>