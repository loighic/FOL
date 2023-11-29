## first-order logic, assignment 04 (in-class)

---

Provide a proof for each argument. 19.1 - 19.3 will be proofs in TFL. 19.4 - 19.7 will be proofs in FOL.

There will not be feedback at the end of each line for proofs 19.2 - 19.5. These (like the others) can only be submitted when they are correct, however.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;). Don't put parentheses around the names or variables. Use this format: Fa and ExFx.

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="18" late-credit="12"}
19.1 ~(S v T) :|-: ~S & ~T
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" feedback="none" guides="fitch" points="12" late-credit="8"}
19.2 M -> ~P, P :|-: ~M 
19.3 Q -> (R & T), Q v R :|-: R
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" feedback="none" guides="fitch" points="12" late-credit="8"}
19.4 AyFy, AzMz :|-: Ex(Fx & Mx)
19.5 Ay(Fy v Gy), Ax~Fx :|-: ExGx
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="18" late-credit="12"}
19.6 Ax(Px v ~Qx), AxAy(Sx -> Qy), Sa & Na :|-: Pe
19.7 AxAy(~Nx <-> Ly), Az(Fz v ~Nz), ~Fa :|-: AxLx
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---