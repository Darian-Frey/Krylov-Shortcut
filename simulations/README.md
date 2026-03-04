# CODE-GEO Simulation Suite: Sub-Atomic

This directory contains the verification engine for the **Krylov Shortcut** theory.

## 📄 Files

* `tunneling_shortcut.py`: The primary audit script. It calculates the **0.76 as** latency for Hydrogen at 7.6 eV.

## 🛠️ Usage

Requires Python 3.8+ and NumPy.

```bash
python3 simulations/tunneling_shortcut.py
```

## 📈 Methodology

The simulation maps the **Hartman Time** (phase delay) against the **Nonlinear Gate** $. The resulting "Plateau Duration" represents the time the QEC substrate spends reconstructing the particle wavefunction on the far side of the barrier.
