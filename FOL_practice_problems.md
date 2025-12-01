## FOL proofs practice problems

---

These are optional, and you can work on them with others. They can't be submitted, but you can see whether or not you have done them correctly.

---

**Part 1**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch"  submission="none"}
0.1 AxHx :|-: He
0.2 Ay(Py v Ty) :|-: Pn v Tn
0.3 Gc :|-: EyGy
0.4 Me <-> Pe :|-: Ez(Mz <-> Pz)
0.5 AxAy(Lx -> Py) :|-: Ay(La -> Py) 
~~~

**Part 2**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch"  submission="none"}
0.6 ~Wc, Ax(Px v Wx) :|-: EyPy
0.7 Ax(Fx <-> ~Gx), Ax~Gx :|-: ExFx
0.8 ~Fe <-> AxGx, Ay~Hy, Ax(Hx v ~Fx) :|-: Ga
0.9 Ex(Gx & Nx) -> AxHx, (Gc & Fc) & Nc :|-: Hc
0.10 ~Ta, Ra -> Ax(Nx <-> (Tx v Qx)), Ax(Nx & Rx) :|-: EyQy
0.11 (EyTy -> Se) <-> Nc, AxPx & ~Qc, Ax(Nx v Qx) & Te :|-: Ex(Sx & Px)
~~~

**Part 3**

You have to use the universal introduction rule in the following proofs. Check chapter 19, and be careful with the names that you use in the proof.

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent render" guides="fitch"  submission="none"}
0.12 Sa -> Ax(Px & Qx), AxSx :|-: AxQx
0.13 ~ExPx v Ay(Sy & Ty), Pa & Qa :|-: AyTy 
0.14 EyMy -> Ax(Qx & Wx), Ax(Mx <-> Px), Pa :|-: AzWz
0.15 Ax(Mx & Sx) <-> (Tc v Wa), Ay(Ry v Ty), ~Rc :|-: AxMx 
~~~


---
---

You can also work on proofs of FOL in the space below. Begin by listing the premise or premises, and then work to the conclusion. When you are finished, if the proof is complete and correct, every line will have a "+" at the far right and Carnap will display the premises and conclusion above your proof. That box won't turn green, however, since, without knowing the argument, Carnap can't determine that you've reached the conclusion.

---

~~~{.Playground .ForallxQLPlus options="fonts tabindent resize render" guides="fitch"} 
~~~


<p>&copy; 2023 - <script>document.write(new Date().getFullYear())</script> Gregory Johnson</p>
 
---