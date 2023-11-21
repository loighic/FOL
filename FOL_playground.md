## first-order logic workspace

---

Begin by listing the premise or premises, and then work to the conclusion. When you are finished, if the proof is complete and correct, every line will have a "+" at the far right and Carnap will display the premises and conclusion above your proof. That box won't turn green, however, since, without knowing the argument, Carnap can't determine that you've reached the conclusion.

---

~~~{.Playground .ForallxQLPlus options="fonts tabindent resize render" guides="fitch"} 
~~~

---

Here are some valid arguments for which you can try to create proofs.

¬Wc, ∀x(Px ∨ Wx) &vdash; &exist;yPy

∀x(Fx ↔ ¬Gx), ∀x¬Gx &vdash; &exist;xFx

¬Fe ↔ ∀xGx, ∀y¬Hy, ∀x(Hx ∨ ¬Fx) &vdash; Ga

&exist;x(Gx & Nx) → ∀xHx, (Gc & Fc) & Nc &vdash; Hc

¬Ta, Ra → ∀x(Nx ↔ (Tx ∨ Qx)), ∀x(Nx & Rx) &vdash; &exist;yQy

(&exist;yTy → Se) ↔ Nc, ∀xPx & ¬Qc, ∀x(Nx ∨ Qx) & Te &vdash; &exist;x(Sx & Px)

---