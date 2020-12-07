# Elections_as_Networks
A class project for CS510 and CS520 in the CADS PhD program at Chapman University that looks to extend my research as an undergrad. The goal will be to implement the action performed when computing the results of an election in a way that is consistent with category theory models of generalized open networks. Details on the goals and background of this project can be found in Wayland2019 and Project_Proposal. Initially this project will simulate a generalized voting system using R. Once a foundational understanding has been achieved from a programming perspective, the implementation can be translated into Haskell which has the potential to truly build a model consistent with the underlying category theory.


## Current Progress
All that has been developed thus far is a playground (programmed in R) for testing out and understanding the compuational aspects of computing an election when we view it formally as a specialized type of network. More than anything, this is a mental check that the formalism developed in Wayland2019 can indeed compute the outcome of a given election, for example a presidential election. 
* See Elections_as_Networks/R/Voting_Systems_in_R.ipynb to interact
* Note: this is a jupyter notebook run with an R kernel. To run this notebook you'll need a way to host a jupyter notebook (e.g. via Anaconda https://docs.anaconda.com/anaconda/install/). You can add an R kernel by following this guide: https://irkernel.github.io/
