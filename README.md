# OLA Project 2023
This is the GitHub repository for the final project for the Online Learning Applications course, A.Y. 2022/2023.
Project authors: 

- Marco Lucchini ([GitHub](https://github.com/marcolucchini), [Linkedin](https://www.linkedin.com/in/marco-lucchini-294801218/))
- Massimo Perna ([GitHub](https://github.com/maxperna), [Linkedin](https://www.linkedin.com/in/massimo-perna-5ab2b7237/))
- Chiara Mocetti ([GitHub](https://github.com/chiaramocetti), [Linkedin](https://www.linkedin.com/in/chiara-mocetti-757652bb/))
- Giulia Rebay ([GitHub](https://github.com/giuliarebay), [Linkedin](https://www.linkedin.com/in/giuliarebay/))
- Giorgio Romano ([GitHub](https://github.com/grgromano), [Linkedin](https://www.linkedin.com/in/grgromano/))

## Project focus: Pricing and Advertising problems.

The project aims to apply online learning algorithms in a simulated environment to find the best price and advertising strategy to sell our product.
The product we choose to sell is a Lego Technic version of the AT-AT. 
At first, we created an artificial environment where we designed different classes of clients with their prior opinions about price. We modelled their behaviour with respect to advertising platforms.
Then through the steps, we applied different types of online learning algorithms starting from a simplified scenario to a realistic one where all the pieces of information about the environment are unknown. 
The algorithms we used are UCB1, Thompson Sampling and a modified version of them which exploits gaussian processes.
In the last two steps, we compare the results with the EXP3 algorithm.


The repository is organised in several branches.
On the main branch, the core implementation is found. This includes:
* All implemented Environments, contained in the folder “Environments”. These interact with the learners and conceptually model the context where the simulations required for the learning to take place happen. In this folder we have also saved the python scripts where the User and Product classes are implemented;
* Learners, defined in the folder “Learners”. Here the core Learner.py class can be found, and all of its extensions used in the following steps;
* Saved plots (which we will provide thorough explanation for in the presentation slides), in the folder “results”;
* The python files used for steps 0 to 6.
