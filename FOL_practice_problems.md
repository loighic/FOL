## FOL proofs, practice problems

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

---

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch"  submission="none"}
0.1 ~Wc, Ax(Px v Wx) :|-: EyPy
0.2 Ax(Fx <-> ~Gx), Ax~Gx :|-: ExFx
0.3 ~Fe <-> AxGx, Ay~Hy, Ax(Hx v ~Fx) :|-: Ga
0.4 Ex(Gx & Nx) -> AxHx, (Gc & Fc) & Nc :|-: Hc
0.5 ~Ta, Ra -> Ax(Nx <-> (Tx v Qx)), Ax(Nx & Rx) :|-: EyQy
0.6 (EyTy -> Se) <-> Nc, AxPx & ~Qc, Ax(Nx v Qx) & Te :|-: Ex(Sx & Px)
~~~

---

You can also work on proofs of FOL in the space below. Begin by listing the premise or premises, and then work to the conclusion. When you are finished, if the proof is complete and correct, every line will have a "+" at the far right and Carnap will display the premises and conclusion above your proof. That box won't turn green, however, since, without knowing the argument, Carnap can't determine that you've reached the conclusion.

---

~~~{.Playground .ForallxQLPlus options="fonts tabindent resize render" guides="fitch"} 
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---