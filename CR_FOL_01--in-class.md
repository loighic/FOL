## first-order logic, assignment 01 (in-class)

---

Provide a proof for each argument. The first will be a proof in TFL. 17.2 - 17.4 will be proofs in FOL.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). Don't put parentheses around the names or variables. Use this format: Fa and ExFx.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
17.1 P -> (N & S) :|-: ~N -> ~P
~~~


~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
17.2 Ax(Px & Rx), Ax(Px -> Qx) :|-: EyQy
17.3 Ey(Ny v Ry) -> ~Rc, Ax(Nx v Rx) :|-: Nc
17.4 Ay~(Cy & Dy), (Ca & Da) v (ExFx -> AyGy), Fa :|-: Ga
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---