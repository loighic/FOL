## FOL proofs, practice problems

---

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

You have to use the universal introduction rule in the following proofs. Check chapter 19, and be careful with the names that you use in the proof.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch"  submission="none"}
0.7 Sa -> Ax(Px & Qx), AxSx :|-: AxQx
0.8 ~ExPx v Ay(Sy & Ty), Pa & Qa :|-: AyTy 
0.9 EyMy -> Ax(Qx & Wx), Ax(Mx <-> Px), Pa :|-: AzWz
0.10 Ax(Mx & Sx) <-> (Tc v Wa), Ay(Ry v Ty), ~Rc :|-: AxMx 
~~~


---

You can also work on proofs of FOL in the space below. Begin by listing the premise or premises, and then work to the conclusion. When you are finished, if the proof is complete and correct, every line will have a "+" at the far right and Carnap will display the premises and conclusion above your proof. That box won't turn green, however, since, without knowing the argument, Carnap can't determine that you've reached the conclusion.

---

~~~{.Playground .ForallxQLPlus options="fonts tabindent resize render" guides="fitch"} 
~~~


<p>&copy; <script>document.write(new Date().getFullYear())</script> Gregory Scott Johnson</p>
 
---