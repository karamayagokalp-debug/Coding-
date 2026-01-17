# Bioinformatic Final Project
Session 1: Annotation of coding sequences

---

##  Analysis Highlights

### 1. Structural Similarity (Exe 7)
Using the **HHpred** server, we identified a conserved match with the **HD-ZIP_N** domain (Pfam: PF04618.17).
* **Identity:** 57%
* **Probability:** 18.44%

![HHpred Alignment](Allignments.png)

---

### 2. Functional Annotation (Exe 9)
Gene Ontology (GO) terms were analyzed via **QuickGO** to define the protein's biological role.
* **Biological Process:** Response to water deprivation (GO:0009414).
* **Cellular Component:** Root hair (GO:0035618).

![QuickGO Search Results](GeneOnthology.png)

---

### 3. 3D Structural Modeling (Exe 10)
The 3D model was retrieved from the **AlphaFold Protein Structure Database** (UniProt: Q9S7E2).
* **Average pLDDT:** **85.88** (High Confidence).
* **Structural Fold:** Stable alpha-helical arrangement supporting DNA-binding activity.

![AlphaFold Structure Model](AlphaFold_Result.png)

---

## Conclusion
The integration of HMM-based domain searches, GO annotations, and AlphaFold modeling confirms that **AT1G30330.2** is a functional **HD-ZIP transcription factor** involved in plant stress response and developmental regulation.
