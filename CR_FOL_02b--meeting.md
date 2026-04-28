## first-order logic assignment 03 (meeting)

---

Use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

**FOL short proofs**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="5" late-credit="3"}
21.1 Se & Qe :|-: Ez(Sz & Qz)
21.2 Az(Mz <-> Tc) :|-: Ma <-> Tc
21.3 Ax(Fx -> EyGy) :|-: (Fe -> EyGy)
21.4 Ha v Ma :|-: Ex(Hx v Ma)
~~~

**FOL main problems**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="15"}
21.5 Ax(Px <-> Qx), Qa :|-: EyPy
21.6 Ax(Pa -> Wx), AxPx :|-: AyWy
~~~

See the handout for guidance with 20.3.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="20" late-credit="15"}
21.7 AxAy(Txy & My), Ax(Tcx -> Px) :|-: AxPx
21.8 AxAy(Rxy -> Ty), Az(Rez & Ma) :|-: AyTy
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---