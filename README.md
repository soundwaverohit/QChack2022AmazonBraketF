# Quantum Coalition Hackathon 2022 Amazon Braket Challenge Submission 

## Implementation of the Quantum Restricted Boltzmann Machine Neural Network Algorithm using Variational Methods




## Problem Description

The problem of approimating the statistics of a thermal state of a given hamiltonian is a largely and expensive computational problem in Statritcal Physics. 

For a given Ising hamiltonian: ![Screen Shot 2022-04-10 at 4 42 58 AM](https://user-images.githubusercontent.com/30132476/162616395-72185b4f-a1fd-46e5-8665-36631eb8302f.png) ![Screen Shot 2022-04-10 at 4 43 42 AM](https://user-images.githubusercontent.com/30132476/162616421-c2e74594-56b1-4b90-ba1f-bb71995cb223.png)

For a given thermal state: ![Screen Shot 2022-04-10 at 4 46 07 AM](https://user-images.githubusercontent.com/30132476/162616505-2de4c95a-470a-4838-9a50-1808f26d53df.png) for the above ising hamiltonian we have to find a set of states ![Screen Shot 2022-04-10 at 4 44 20 AM](https://user-images.githubusercontent.com/30132476/162616445-5ad822c8-da39-4bbe-9da7-b015d45a0df9.png) where ![Screen Shot 2022-04-10 at 4 44 46 AM](https://user-images.githubusercontent.com/30132476/162616459-8200105b-39ee-4509-b9d4-d2270183a846.png) is a set of variational parameters for the state preparation ansatz that we must find and optimize using the QRBM Algorithm.

We have to find the variational parameters using the QRBM Algorithm and compare its speed over a classical Restricted Boltzmann Machine Algorithm for complicated Hamiltonians.





## Results











## Instructions on Running the Project

Step 1: Clone the Project Repository into AWS Braket or your local machine.

Step 2: Make sure the following packages or softwares are installed:
        - Python Packages (pip install {package name}: pyquil, scipy, funcsigs, numpy, functools, typing, collections
        - If running on Braket make sure it is running on the Aspen-11 Rigetti Device
        - If running on local machine make sure the Rigetti Forest SDK is installed https://pyquil-docs.rigetti.com/en/1.9/start.html#
            - Go to terminal and run "qvm -S" and "quilc -S" to start the Quantum virtucal machine and the quil compiler from rigetti 
        - Make sure python, conda or jupyter notebook are installed if running on a local machine
        
Step 3: Run the jupyter notebook. Keep in mind the epochs and initial data can be adjusted in the notebook itself but keep in mind the entire algorithm 
        takes 30 minutes for 100 epochs for the given hamiltonian.
