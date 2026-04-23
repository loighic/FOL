## first-order logic, assignment 01 (meeting)

---

Provide a proof for each argument. The first will be a proof in TFL. 18.2 - 18.9 will be proofs in FOL.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
18.1 P -> (N & S) :|-: ~N -> ~P
~~~

---

**FOL short proofs**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
18.2 AxQx :|-: Qa
18.3 Az(Pz <-> Tz) :|-: Pe <-> Te
18.4 Lc :|-: EzLz
18.5 Fa & Ma :|-: Ex(Fx & Mx)
18.6 Gb	:|-: Ey(Gy v Ty)
~~~

---

**FOL main problems**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="22" late-credit="17"}
18.7 Ax(Px & Rx), Ax(Px -> Qx) :|-: EyQy
18.8 Ey(Ny v Ry) -> ~Rc, Ax(Nx v Rx) :|-: Nc
18.9 Ay~(Cy & Dy), (Ca & Da) v (ExFx -> AyGy), Fa :|-: Ga
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---