In Silico Discovery of NDM-1 Metallo-β-Lactamase Inhibitors for Klebsiella pneumoniae

Overview
Antibiotic resistance poses a significant global health threat, and the emergence of New Delhi Metallo-β-Lactamase (NDM-1) in Klebsiella pneumoniae has rendered many β-lactam antibiotics ineffective. This project aims to identify potential inhibitors of NDM-1 using computational approaches, including molecular docking, ADMET analysis, and molecular dynamics (MD) simulations.

Project Objectives
- Retrieve and prepare the NDM-1 target protein.
- Screen standard ligands and sulfonamide derivatives for potential inhibitory activity.
- Conduct molecular docking studies using AutoDock Vina.
- Perform ADMET (Absorption, Distribution, Metabolism, Excretion, and Toxicity) predictions.
- Carry out molecular dynamics simulations using GROMACS to assess complex stability.

Methodology
1. Retrieval of Target Protein and Ligands
- Protein Data Bank (PDB ID: `6NY7`) was used to retrieve the NDM-1 protein.
- Standard ligands (Penicillin, Benzyl Penicillin, Mercaptopurine, Ampicillin, Sulfonamide, etc.) were retrieved from the *PubChem* database.
- Sulfonamide derivatives (~1400 molecules) were filtered using Lipinski’s and Veber’s rules.

2. Molecular Docking
- Protein preparation and docking studies were conducted using AutoDock Vina in PyRx.
- Sulfonamide showed promising inhibitory activity against NDM-1.
- Virtual screening of ~1400 sulfonamide derivatives led to the identification of 60 top hits.

3. ADMET Studies
- ADMET properties were analyzed using ADMETLab 2.0 and Protox-II.
- Two promising candidates were identified:
  - (3Z)-N-hydroxypenta-1,3-diene-2-sulfonamide (PubChem CID: 118156306)
  - N-hydroxyfuran-2-sulfonamide (PubChem CID: 46175386)

4. Molecular Dynamics Simulations
- Conducted for 100 ns using *GROMACS 5.0.4*.
- RMSD, RMSF, Rg, and SASA plots confirmed the stability of the identified complexes.

Results
- Docking Studies:Sulfonamide derivatives demonstrated strong binding affinity.
- Virtual Screening: A dataset of about 4500 sulfonamide compounds were screened against NDM-1
- ADMET Analysis: Two lead compounds exhibited favorable pharmacokinetics and minimal toxicity.
- MD Simulations: The selected compounds formed stable interactions with NDM-1.

Conclusion
This study identified (3Z)-N-hydroxypenta-1,3-diene-2-sulfonamide and N-hydroxyfuran-2-sulfonamide as potential NDM-1 inhibitors. Further experimental validation and lead optimization are necessary for drug development.

License
This project is licensed under the MIT License.

Contact
For any queries or contributions, please reach out via GitHub Issues or email raghava.332410@gmail.com
