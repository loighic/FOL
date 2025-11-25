## first-order logic, assignment 04 (at-home)

---

<font color="#9900FF">**Do this alone**, and don't discuss it with anyone who hasn't done it. If you need help, contact the instructor.</font>


---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="20" late-credit="15"}
21.1 P -> ~T :|-: T -> ~P
21.2 S <-> Q, ~(S v T) :|-: ~Q
~~~

---

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="15"}
21.3 Ax(Fx -> Gx), AxFx :|-: AxGx
21.4 AxAy(Fx -> Gy), Fa :|-: AxGx
21.5 Ax(Px -> (Qa v Tx)), AxPx, ~Qa :|-: AxTx & Ey~Qy
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---