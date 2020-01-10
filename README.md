# RNN Wavefunctions

RNN Wavefunctions are efficient quantum many-body wavefunction ansätzes based on Recurrent Neural Networks. These wavefunction can be used to find the ground state of a quantum many-body Hamiltonian using Variational Monte Carlo (VMC). In our recent paper, we show that this new architecture can provide accurate estimations of ground state energies, correlation functions as well as entanglement entropies.

Our implementation is based on TensorFlow 1 and we plan to support TensorFlow 2 and Pytorch in the future.

## Running Variational Monte Carlo Calculations

Currently, this repository contains four folders, each one is specific for a given model and architecuture in the following order:
- 1DTFIM: 1D pRNN wavefunction for 1D Transverse-field Ising Model (TFIM).
- 2DTFIM_1DRNN: 1D pRNN wavefunction for 2D TFIM.
- 2DTFIM_2DRNN: 2D pRNN wavefunction for 2D TFIM.
- J1J2: 1D cRNN wavefunction for 1D J1-J2 Model.