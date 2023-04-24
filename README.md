# More_CR_Proofs_Beluga
A formalization of the Church-Rosser property in lambda-calculi carried out with the proof environment Beluga.

The directory is organized as follows:
## Beta
- beta_pfenning: standard proof of CR for $\beta$-reduction (untyped $\lambda$-calculus)
- beta_tak: Takahashi's proof (triangle operator) of CR for $\beta$-reduction (untyped $\lambda$-calculus)
- beta_comp: encoding directly in Beluga's meta-logic of CR for $beta$-reduction (untyped $\lambda$-calculus)
## Eta
Proof of CR for $\eta$-reduction via commutation (untyped $\lambda$-calculus)
## Beta-Eta
Modular proof of $\beta\eta$-reduction via commutation by exploiting the results for $\beta$ and $\eta$ (untyped $\lambda$-calculus)
## Types
- stlc_tak: Takahashi's proof (triangle operator) of CR for $\beta$-reduction (simply typed $\lambda$-calculus)
- L2: Takahashi's proof (triangle operator) of CR for $\beta$-reduction (polymorphic $\lambda$-calculus)
- pts
