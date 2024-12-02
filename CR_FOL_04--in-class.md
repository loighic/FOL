## first-order logic, assignment 04 (in-class)

---

Provide a proof for each argument. 22.1 - 22.3 will be proofs in TFL. 22.4 - 22.7 will be proofs in FOL.

There will not be feedback at the end of each line for proofs 22.2 - 22.5. These (like the others) can only be submitted when they are correct, however.

For the proofs in FOL, use A for the universal quantifier (&forall;) and E for the existential quantifier (&exist;).

---

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" guides="fitch" points="18" late-credit="12"}
22.1 ~(S v T) :|-: ~S & ~T
~~~

~~~{.ProofChecker .JohnsonSL options="fonts tabindent render" feedback="none" guides="fitch" points="12" late-credit="8"}
22.2 M -> ~P, P :|-: ~M 
22.3 Q -> (R & T), Q v R :|-: R
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" feedback="none" guides="fitch" points="12" late-credit="8"}
22.4 AyFy, AzMz :|-: Ex(Fx & Mx)
22.5 Ay(Fy v Gy), Ax~Fx :|-: ExGx
~~~

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch" points="18" late-credit="12"}
22.6 Ax(Px v ~Qx), AxAy(Sx -> Qy), Sa & Na :|-: Pe
22.7 AxAy(~Nx <-> Ly), Az(Fz v ~Nz), ~Fa :|-: AxLx
~~~

<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---