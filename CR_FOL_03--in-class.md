## first-order logic, assignment 03 (in-class)

---

Provide a proof for each argument. The first will be a proof in TFL. 20.2 - 20.4 will be proofs in FOL.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
20.1 S v (~P & T), ~P -> Q, ~Q v ~T :|-: T -> S
~~~

If you get stuck on 20.2, think about what the main logical operator is in &forall;xRx &rarr; &forall;y&not;Sy.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
20.2 AxRx -> Ay~Sy, AxRx, Sa v Qe :|-: Qe
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
20.3 Pa -> Sa, AxAy(Px  <-> Qy), Qb :|-: EzSz
20.4 AxAy(Rxy -> Ty), Az(Raz & Mz) :|-: AyTy
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---