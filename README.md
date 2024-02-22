# NISQ algorithm implementation inspired from Universal Quantum Algorithms

<h2>Qhack 2024</h2>
<h4>Team - Quantum Questers</h4>

<h4>Team members</h4>
<UL>
  <LI>Ramachandran Sekanipuram Srikanthan</LI>
  <LI>Hirmay Sandesara</LI>
  <LI>Yu-Cheng Lin</LI>
  <LI>Astor</LI>
</UL>

<h4>Power Ups</h4>

<p> Thank you Xanadu, AWS and NVIDIA for providing power ups to perform furthur experimentation for our project. </p>

<h4>Description</h4>

<p>Our primary goal through this project was to simulate open-quantum sys-
tems suitable for the Noisy Intermediate-Scale Quantum (NISQ) era and the
Intermediate-Scale Quantum (ISQ) era. Since certain special algorithms are
implemented as Universal Quantum Algorithms (UQAs) for Fault Tolerant
Quantum Computing (FTQ), which are currently not realized. Furthermore,
Quantum Error Correction as mentioned in Laurent Prost’s presentation is not
currently quite practical since it requires additional qubits (logical qubit for-
mulation), though one can use cat qubits, which we have also incorporated in
one of our framework (state preparation), but that too would be feasible in
the ISQ era. Hence, there is absence of existing VQA framework for specific
problems like “direct estimation of energy difference between two structures in
chemistry”. The paper [1], discusses about the need for a UQA inspired frame-
work with shallow circuit depth for NISQ devices (essentially a VQA algorithm)
for such special problems. In this project, we aim to implement the framework
in Python while also introducing our own innovations to enhance its robustness
and expand its usability. We will not only utilize these innovations but also test
the framework across various scenarios to showcase its usability and discuss the
future implications of our work</p>

<h4> Project Categories </h4>
Our project addresses three categories, namely: "Preparing for Battle," "Seeing the Future," and "The Sound of Silence." A detailed write-up of our work is provided in the shared report. The Submission folder contains the code files and datasets used for generating the results presented in our report. The Approach 1 folder contains all the code files for the simulations used in Subsection 6.2.1, named Approach 1, while the Approach 2 folder contains code files for the simulations used in Subsection 6.2.2, named Approach 2. The Cat Qubits folder includes simulations done using the cat qubit framework with 8 and 12 qubits. The Open Systems Simulation folder contains simulations of example 1, which involve utilizing the state preparation method using Approach 1, computing the evolution unitary, and conducting the simulations. Furthermore, in the Package folder, we have created Python packages for our two approaches. Lastly, the Testing_drug_target_prediction_dataset contains the chEMBL dataset used in the report.
