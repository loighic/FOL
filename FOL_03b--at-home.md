---
title: FOL, assignment 4
---


# FOL, assignment 04 (at-home, contingent)

---

## Instructions


<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>

**This is a contingent assignment.** See the explanation for contingent assignments in the &ldquo;test 2 pre-test assignments&rdquo; module in Canvas.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
1 P -> ~T :|-: T -> ~P
2 S <-> Q, ~(S v T) :|-: ~Q
~~~

---


~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
3 Ax(Fx -> Gx), AxFx :|-: AxGx
4 AxAy(Fx -> Gy), Fa :|-: AxGx
|1.AxAy(Fx -> Gy)	:PR
|2.Fa		:PR
|3.Ay(Fa -> Gy)	:AE 1
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" guides="fitch" points="20" late-credit="15"}
5 Ax(Px -> (Qa v Tx)), AxPx, ~Qa :|-: AxTx & Ey~Qy
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---