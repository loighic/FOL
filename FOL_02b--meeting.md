---
title: FOL, assignment 3
---


# first-order logic assignment 03 (meeting)

---

## Instructions

Use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

## FOL short proofs

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" guides="fitch" points="5" late-credit="3"}
1 Se & Qe :|-: Ez(Sz & Qz)
2 Az(Mz <-> Tc) :|-: Ma <-> Tc
3 Ax(Fx -> EyGy) :|-: (Fe -> EyGy)
4 Ha v Ma :|-: Ex(Hx v Ma)
~~~

## FOL main problems

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
5 Ax(Px <-> Qx), Qa :|-: EyPy
6 Ax(Pa -> Wx), AxPx :|-: AyWy
~~~

See the handout for guidance with 7.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" guides="fitch" points="20" late-credit="16"}
7 AxAy(Txy & My), Ax(Tcx -> Px) :|-: AxPx
8 AxAy(Rxy -> Ty), Az(Rez & Ma) :|-: AyTy
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---