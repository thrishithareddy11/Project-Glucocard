# Project-Glucocard🧬
●**Automated In-Silico Pipeline for Natural Alpha-Glucosidase Inhibitor Discovery**

## 📍Overview
Glucocard is a computational drug discovery framework developed to identify natural alternatives for Type 2 Diabetes management. The project integrates Python-based chemical screening with structural bioinformatics to evaluate the efficacy of Berberine against the human **3W37** enzyme.

## ~ Pipeline Workflow
1. **Data Acquisition:** Automated retrieval of chemical data via the `PubChemPy` API.
2. **Lipinski Screening:** Evaluating drug-likeness (MW, H-bond donors/acceptors).
3. **Bioavailability:** Utilizing the **BOILED-Egg model** for GI absorption prediction.
4. **Docking Analysis:** Comparative binding affinity analysis (Berberine vs. Acarbose).

## 🌐 Key Findings
| Molecule | Binding Energy (ΔG) | Status |
| **Berberine** | **-8.4 kcal/mol** | **Potent Inhibitor** |
| **Acarbose** | **-6.2 kcal/mol** | Standard Drug |

##  Tech Stack:
- **Language:** Python
- **Database:** PubChem
- **Analysis:** SwissADME, PDBe, SwissDock

