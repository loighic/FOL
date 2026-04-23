## first-order logic, assignment 01 (meeting)

---

Provide a proof for each argument. The first will be a proof in TFL. 19.2 - 19.9 will be proofs in FOL.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). 

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="25" late-credit="17"}
19.1 P -> (N & S) :|-: ~N -> ~P
~~~

---

**FOL short proofs**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="2" late-credit="1"}
19.2 AxQx :|-: Qa
19.3 Az(Pz <-> Tz) :|-: Pe <-> Te
19.4 Lc :|-: EzLz
19.5 Fa & Ma :|-: Ex(Fx & Mx)
19.6 Gb	:|-: Ey(Gy v Ty)
~~~

---

**FOL main problems**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="22" late-credit="17"}
19.7 Ax(Px & Rx), Ax(Px -> Qx) :|-: EyQy
19.8 Ey(Ny v Ry) -> ~Rc, Ax(Nx v Rx) :|-: Nc
19.9 Ay~(Cy & Dy), (Ca & Da) v (ExFx -> AyGy), Fa :|-: Ge
~~~ 

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---