# CODE-GEO Derivation: Quantum Tunneling Time as a Complexity Shortcut

**Protocol:** SCHEMA_V5 (Informational Spacetime)  
**Status:** Theoretical Framework — Academic Ready (2026-03-04)

## 1. Motivation: The Hartman Effect

In standard quantum mechanics, the phase time (group delay) saturates as barrier width  \to \infty$:
2156\tau_H = \frac{\hbar}{\sqrt{2m(V_0 - E)}} \cdot \frac{1}{\kappa}2156
The **CODE-GEO reinterpretation** posits that the barrier region is a zone of *low computational complexity density*. The particle is not propagated—it is *reconstructed* on the far side by the ambient QEC substrate.

## 2. The CODE-GEO Nonlinear Gate

To satisfy high-precision constraints, we define the relevant length scale as the evanescent decay length $\ell_\kappa \equiv \kappa^{-1}$. The gate is defined as:
2156\mathcal{G}_{tun}(x) = \left(\frac{1}{1 + \kappa x}\right)^62156

## 3. Computational Path Length {\text{comp}}$

The particle does not traverse $; instead, the QEC substrate performs a reconstruction operation whose cost is:
2156L_{\text{comp}} = \int_0^L \frac{dx}{\mathcal{G}_{tun}(x) \cdot \mathcal{C}_k(x) / \mathcal{C}_0} = \int_0^L (1 + \kappa x)^6\, e^{2\kappa x}\, dx2156

## 4. Tunneling Time via Krylov Operator Variance

We define the **tunneling latency** {tun}$ as the duration of the **Krylov Plateau**—the time during which spread complexity $\sigma_K^2(t)$ is stationary:
2156t_{tun} \approx \frac{\hbar \kappa L}{2(V_0 - E)} \cdot \left(\frac{1}{\mathcal{G}_{tun}^{1/2} e^{-\kappa L}}\right)2156

## 5. The Hartman Limit (Conditional Reconstruction)

For large $, the **phase time** (Hartman time) is recovered as the *conditional reconstruction time*:
2156\tau_H^{(\text{CODE-GEO})} = \lim_{L\to\infty} t_{tun}\big|_{\text{cond.}} = \frac{\hbar}{2(V_0 - E)}2156
This matches the "Instantaneous" observation while accounting for the .8$ as latency in Hydrogen systems.
