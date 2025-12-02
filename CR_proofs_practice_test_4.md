## proofs, practice problems for test 4

---

**This is not the pre-test. These are practice problems.**

These are optional, and you can work on them with others.

There is no feedback at the end of each line. They cannot, however, be submitted until they are correct. There won't be any problems set up like these on the test, but it will be helpful to do these as practice. 

These do not count toward your grade.

---

**FOL**

~~~{.ProofChecker .ForallxQLPlus options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
0.1 Ax(Fx -> Px), Fe :|-: Ey(Fy & Py)
0.2 ([Fc v Lc] -> AzPz), AxLx :|-: Pa
0.3 Az(~Tz & Wz), Ax(Wx <-> [Qx v Tx]) :|-: Qa
0.4 Ax~Dx, Ax(Bx -> [Lx v Dx]), Bm :|-: EzLz
0.5 (Tec -> AxMx), AxAy(Txy & Px) :|-: Ma
0.6 AxAy(Txy -> ~Rc), (Ma & Tcn) :|-: Ex~Rx
0.7 AzMz, (Ex[Rx & Mx] -> Ay[Qy v ~My]), (Rc <-> Mc) :|-: ExQx
0.8 AxAy(Px -> My), (Pa & Dc) :|-: AxMx
0.9 Ay(Fy -> ~Gy), AzFz, Ax(Ga v Hx) :|-: AxHx
0.10 (EyMy -> Ax[Qx & Wx]), ∀x(Mc <-> Px), Pa :|-: ∀zWz
~~~

**TFL**

~~~{.ProofChecker .JohnsonSL options="fonts tabindent" feedback="none" guides="fitch" points="1" late-credit="1"}
0.11 ~R v S, S -> Q :|-: R -> Q
0.12 T -> (P -> Q) :|-: (T & P) -> Q 
0.13 S & ~T, Q -> (S -> N) :|-: (Q v T) -> N 
0.14 T -> P, ~P v S :|-: (Q & T) -> (Q & S)
0.15 Q, (P -> ~Q) :|-: ~P
0.16 (S & T), (P <-> [Q & ~S]) :|-: ~P
0.17 (~M v T) :|-: (M -> T)
0.18 (S -> [Q & R]), (~[Q & S] <-> T):|-: (S -> ~T)
0.19 (M v P) :|-: (P v M)
0.20 (Q -> T), (P -> S), (P v Q) :|-: (S v T)
~~~