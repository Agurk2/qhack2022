# Solving binding energies for the ground state protease in SARS-Cov-2

This project has been developed during the QHack 2022 open hackathon.

### Team Name: 

Quionizers

### Project Description: 

This project computes the binding energies of glutamine in order to facilitate speedups in the development of novel Civid-19 vaccines. A protease is an enzyme that works as a "hammer", breaking down particles into smaller amino acids and polypeptides. These amino acids and polypeptides then form long chains, allowing the virus to spread within the host. 

Covid-19 contains a protease called glutamine (see image).

![image](https://user-images.githubusercontent.com/86123205/155739807-1b60def5-765b-4530-af4a-6c538dcc5419.png)

_National Center for Biotechnology Information. "PubChem Compound Summary for CID 5961, Glutamine" PubChem, https://pubchem.ncbi.nlm.nih.gov/compound/Glutamine. Accessed 30 January, 2022._

Therefore, by blocking the protease's receptors, we effectively halt the virus's ability to spread within the host. This can be done by reacting the protease with a protease inhibitor in order to stop this chemical process from occuring.

Current quantum hardware is not powerful enough to simulate whole macromolecules. However, as quantum computers get more and more powerful, so too will the ability to simulate molecular interactions. Glutamine molecule is the key protease in SARS-Cov-2. To simulate the whole molecule, 40+ qubits and several weeks of computation time would be required -- unfeasible with current technology.

However, by reducing the glutamine to NH₂C, we are able to simulate the binding of glutamine with a protease inhibitor, effectively achieving a speedup in the development of new SARS-Cov-2 vaccines. For this project, we simplified the glutamine molecule to create a so-called toy protease, in order to prove the effectiveness of quantum computers. 

The glutamine molecule is simplified to methanamine (see image). 

![image](https://user-images.githubusercontent.com/86123205/155741903-53ddd53c-ff82-4bfb-8814-378b1536fde1.png)

_National Center for Biotechnology Information. "PubChem Compound Summary for CID 450541, (111C)methanamine" PubChem, https://pubchem.ncbi.nlm.nih.gov/compound/111C_methanamine. Accessed 30 January, 2022._

By computing the bonding energy for the ground state toy protease, we can develop more sophisticated inhibitors that may be more effective against other Covid variants. One major way we were able to simulate the molecule was by using the Hartree-Fock approximation method, which allows us to approximate the wave function of the quantum system of specific molecules in the quantum level, like glutamine.

This [research paper](http://vergil.chemistry.gatech.edu/notes/hf-intro/hf-intro.pdf) goes further in depth into the Hartree Fock method. 

### Presentation: 

https://docs.google.com/presentation/d/1jXdZgyL0UMFsaJY3CagPcJ-0RO5mTW9KV9YCDDhtTeg/edit#slide=id.g11742b38c2e_0_81

### Business Pitch: 

https://docs.google.com/presentation/d/1RUTgP6EQV1CDNaoC5YO_VSJL7UFLT_LaiENJxCoTO5Q/edit#slide=id.g11742b38c2e_0_81

### Source code: 

[https://github.com/Agurk2/qhack2022](url)

### Which challenges/prizes would you like to submit your project for?

Young Scientist Challenge  
Science Challenge  
Simulation Challenge  
Quantum Entrepreneur Challenge (slideshow still required)  
Quantum Chemistry Challenge  
QAOA Challenge  
Hybrid Algorithms Challenge
IBM Qiskit Challenge

