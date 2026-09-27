---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research lies at the intersection of **algebraic geometry** and **mathematical physics**. During my PhD under the supervision of Bernd Siebert, I have been exploring applications of tropical and logarithmic methods to enumerative geometry and mirror symmetry. With training in both mathematics and physics, I am broadly interested in connections between geometry and theoretical physics, including supersymmetric quantum field theory, string theory, and M-theory.

## Quantum mirror symmetry for local \(\mathbb P^2\)

My main current project is joint work with **Pierrick Bousseau** and **Bernd Siebert**:

> *Quantum Geometry of Mirror Landau–Ginzburg Model of* \((\mathbb P^2,E)\).

The local Calabi–Yau threefold in this project is
\[
X = K_{\mathbb P^2}.
\]

On the A-model side, Bousseau's work identifies the relevant Nekrasov–Shatashvili limit with higher-genus logarithmic Gromov–Witten invariants of the pair
\[
(\mathbb P^2,E),
\]
where \(E\subset \mathbb P^2\) is a smooth cubic curve.

On the B-model side, one starts with the mirror curve
\[
\check C
=
\left\{
(X,P)\in(\mathbb C^\ast)^2
\;\middle|\;
-1+W(X,P)=0
\right\},
\]
with superpotential
\[
W
=
T\left(
X+P+\frac{1}{XP}
\right).
\]

Writing \(X=e^x\) and \(P=e^p\), quantization gives the difference equation
\[
(-1+Te^x)\psi(x)
+
T\psi(x+\hbar)
+
Te^{\hbar/2}e^{-x}\psi(x-\hbar)
=
0.
\]

The WKB ansatz is
\[
\psi(x)
=
\exp\left(
\frac{1}{\hbar}\int^x f_\hbar(x)\,dx
\right),
\qquad
f_\hbar(x)
=
\sum_{i\ge 0} f_i(x)\hbar^i,
\]
and the B-model quantum periods are integrals of the form
\[
\oint_{\gamma} f_\hbar\,dx.
\]

### Main theorem

> **Theorem (Bousseau–Siebert–Yao).**  
> The quantum closed-string mirror-symmetry conjecture of Aganagic–Cheng–Dijkgraaf–Krefl–Vafa holds for local \(\mathbb P^2\).

Our proof replaces direct order-by-order WKB calculation by an intrinsic geometric interpretation of the quantum periods.

### Deformation quantization

The quantized mirror is described by a quantum torus algebra \(\mathcal A\) satisfying
\[
\widehat X\,\widehat P
=
e^{-\hbar}\widehat P\,\widehat X,
\]
together with the Landau–Ginzburg deformation-quantization module
\[
\mathcal M_{\mathrm{LG}}
=
\mathcal A\big/\mathcal A(-1+\widehat W).
\]

The resulting relative Deligne–Fedosov class gives a coordinate-independent interpretation of the quantum periods: pairing the class with a relative \(2\)-cycle recovers the WKB quantum period of its boundary.

### Gross–Siebert program

The second ingredient is the Gross–Siebert construction of the mirror. Its wall structures simultaneously encode enumerative information on the A-model side and gluing data on the B-model side. Passing to coordinates naturally adapted to the Gross–Siebert construction makes the comparison with logarithmic Gromov–Witten invariants transparent.

Because both deformation quantization and the Gross–Siebert construction apply much more generally, the same method extends directly to local toric del Pezzo surfaces.

### My contribution

In this joint project, I have taken the leading role. I developed the main framework of the proof, proposed the deformation-quantization interpretation of quantum periods, identified the simplifying Gross–Siebert coordinates, carried out the explicit computations, and wrote essentially the entire manuscript.

## Wavefunctions, wall crossing and punctured–open correspondence

This project, joint with **Pierrick Bousseau** and **Bernd Siebert**, studies the open-string part of quantum mirror symmetry.

If adjacent chambers in a quantum scattering diagram are separated by a wall with quantum Hamiltonian \(\widehat H\), then the superpotential transforms by
\[
\widehat W
\longmapsto
\operatorname{Ad}_{\exp(\widehat H/\hbar)}(\widehat W)
=
e^{\widehat H/\hbar}\,
\widehat W\,
e^{-\widehat H/\hbar},
\]
while a corresponding wavefunction transforms as
\[
\psi
\longmapsto
e^{\widehat H/\hbar}\psi.
\]

This reduces the open-string conjecture to a wall-crossing problem. In the good chamber of the Gross–Siebert construction, the wavefunction becomes
\[
\psi_\infty=1.
\]

The expected punctured–open correspondence takes the schematic form
\[
Z_{\mathrm{open}}^{\mathrm{NS}}
=
\overrightarrow{\prod_d}
\exp\left(\frac{H_d}{\hbar}\right)
\psi_\infty,
\qquad
\psi_\infty=1,
\]
where the ordered product runs over the walls crossed by a chosen wall-crossing path.

## Theta functions and crystal melting

My second ongoing direction concerns the relation between **theta functions**, **crystal melting**, and toric-degeneration mirror symmetry.

In the usual toric crystal-melting picture, lattice points behave like atoms of a crystal. In the Gross–Siebert setting, theta functions provide the natural analogue of these lattice points. My goal is to combine logarithmic equivariant localization with the theta-function basis to extend the Gromov–Witten/Donaldson–Thomas crystal-melting picture from the toric case to general toric degenerations.

A further goal is to understand how the classical mirror geometry emerges from this quantum/combinatorial picture in a semiclassical limit such as
\[
\hbar\longrightarrow 0.
\]

## Longer-term directions

I am also interested in the **topological string/spectral theory correspondence** for local del Pezzo surfaces and in **quantum integrable systems**. In the latter direction, I hope to develop intrinsic quantum action-angle coordinates, with quantum periods playing the role of quantum action variables.
