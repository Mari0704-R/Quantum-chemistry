# Bulk Silicon — PySCF

## Objective

First-principles electronic-structure study of crystalline
bulk silicon using periodic PySCF calculations.

## Material

- Material: Silicon (Si)
- Crystal structure: Diamond cubic
- Lattice constant: 5.43 Å

## Computational Method

- Software: PySCF
- Method: Periodic Hartree-Fock
- Reference: KRHF
- k-point sampling: 2 × 2 × 2

## Workflow

Bulk Si
→ Crystal structure
→ Periodic boundary conditions
→ k-point mesh
→ KRHF
→ Electronic structure

## Planned calculations

1. KRHF
2. PBE
3. PBE0
4. HSE06
5. Band structure
6. Density of states
7. VBM and CBM
8. Band-gap analysis

## Research Extension

The validated bulk-Si model will later be extended to:

- Si:P
- Si:Sb
- Doped supercells
- Quantum-chemistry cluster models
- Qiskit/VQE calculations
