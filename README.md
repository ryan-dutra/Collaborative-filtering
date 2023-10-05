# Overview

This repository contains all the source code used for the experiments and analyses presented in the article titled "Experimental Analysis of Pipelining Community Detection and Recommender Systems", which was submitted to and accepted by the International Conference on Web Information Systems and Technologies (WEBIST 2023).

This work investigated how community detection may lead to better recommendations than those obtained without awareness of implicit communities in the context of recommender systems.
We experimentally assessed various combinations of methods for community detection and recommendation algorithms, as well as synthetic and real datasets.
This targeted to unveil interesting patterns in the behavior of the resulting systems.
Our results show that insights into communities can significantly improve both the effectiveness and efficiency of recommendation algorithms in some favorable scenarios. 
These findings can be used to help data science researchers and practitioners to better understand the benefits and limitations of this methodology.

For further developments in this research topic, please refer to our other repository, recsys4communities (https://github.com/moretoknow/recsys4communities).


## Repository Structure
The repository is structured as follows:
* `/notebooks`:  This directory contains all the Jupyter Notebooks needed to execute and evaluate the experiments.
* `/outputs`:  It stores the results obtained from running the experiments in a `.csv` file format. 
* `/plots`: It stores all the plots generated during the evaluation

## Usage
To reproduce the experiments conducted in the article, follow these steps:
1. Clone the repository: `git clone https://github.com/ryan-dutra/Recommender-System.git`
2. Install the required dependencies listed in `requirements.txt`
3. Navigate to the `/notebooks` directory and run the `experiments_runner.ipynb` script
4. The experiment will generate results, which will be stored in the `/outputs` directory. Two CSV files will be generated: `experiment_results.csv`, containing information related to the RMSE of each execution, and `experiment_runs_cost.csv`, containing information about the runtime for training and testing.
5. Navigate to the `/notebooks` dictory and run the `summarization_of_error.ipynb` and `summarization_of_cost.ipynb` to obtain an graph view of performance and efficiency reached in the experiments.

Please refer to the individual code files for more detailed instructions on running specific experiments.

## Contact Information
For any inquiries or questions regarding the repository or the article, please contact the authors:

* Ryan Dutra de Abreu (ryan.abreu@aluno.cefet-rj.br)
* Laura Silva de Assis (laura.assis@cefet-rj.br)
* Douglas O. Cardoso (douglas.cardoso@ipt.pt)

We appreciate any feedback or contributions to this research project.
