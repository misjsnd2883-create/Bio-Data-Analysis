# Salma-1: In Silico Anticancer Study
### Targeting Tubulin Colchicine Binding Site

**Author:** Mohamed Mahmoud Elsayed Mohamed  
**Institution:** Faculty of Science, Cairo University  
**Department:** Biochemistry  
**Email:** mohamed.osmana30@gmail.com  
**Year:** 2026  

---

## About Salma-1
Novel small molecule designed to inhibit tubulin polymerization 
via the colchicine binding site.

**SMILES:** `COc1cc(F)c(CC(C)C(=O)O)cc1O`  
**Formula:** C11H13FO4  
**MW:** 228.22 Da  

---

## Key Results

| Parameter | Value |
|---|---|
| Binding Energy | -6.10 kcal/mol |
| Colchicine Reference | -7.40 kcal/mol |
| Distance from Site | 2.77 Å |
| Lipinski Violations | 0 |
| hERG Inhibition | No |
| Hepatotoxicity | No |
| QSAR IC50 (predicted) | ~13 μM |

---

## Methods
- Molecular Docking: AutoDock Vina 1.2
- Protein: Tubulin (PDB: 1SA0)
- ADMET: pkCSM + RDKit
- QSAR: XGBoost (ChEMBL dataset, n=1180)

---

## Files
- `Salma1_InSilico_Study.ipynb` - Complete analysis notebook

---

## Citation
If you use this work, please cite:
Mohamed MM. Salma-1: In Silico Investigation of a Novel 
Tubulin Colchicine Site Inhibitor. 2026. GitHub.
