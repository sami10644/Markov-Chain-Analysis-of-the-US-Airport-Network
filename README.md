# **Markov Chain Analysis of the US Airport Network**

Welcome to the **Markov Chain Analysis of the US Airport Network** project! In this notebook, we explore the airline transportation infrastructure of the United States by modeling it as a directed network or graph. The vertices represent airports, and the edges represent direct-flight segments between them.

## **Project Overview**

The goal of this project is to analyze the US airport network using Markov chain analysis and determine the criticality of each airport. We aim to answer the question: Which airports are most crucial to the overall network? By studying the probabilities of transitions between airports, we can identify the impact of disruptions on the network.

## **Data Sources**

The analysis in this notebook is based on the dataset provided by the US Bureau of Transportation Statistics. The dataset includes information on all flights originating or arriving in the United States. You can find the dataset [here](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FIM).

## **Analysis Approach**

To analyze the US airport network, we model it as a first-order Markov chain system. Here's an overview of our approach:

1. **Constructing the Probability Transition Matrix (P):** We calculate the probabilities of transitioning from one airport to another based on the flight data. The matrix P represents the transition probabilities between airports.

2. **Computing the Steady-State Probability Distribution (x∗):** We aim to find the steady-state distribution of the Markov chain, which represents the long-term probabilities of being at each airport. The larger the steady-state probability of an airport, the more critical it is to the network.

## **Notebook Structure**

This notebook is organized as follows:

1. **Data Preprocessing:** We preprocess the flight data to extract the necessary information for constructing the probability transition matrix.

2. **Probability Transition Matrix (P):** We calculate the transition probabilities and construct the probability transition matrix (P) based on the flight data.

3. **Markov Chain Analysis:** We analyze the Markov chain system and compute the steady-state probability distribution (x∗) using matrix operations.

4. **Ranking the Airports:** We rank the airports based on their steady-state probabilities to determine their criticality in the network.

## **Usage**

Follow these steps to get started:

1. Clone the repository: `git clone https://github.com/sami10644/Markov-Chain-Analysis-of-the-US-Airport-Network.git`
2. Install the required libraries: `pip install numpy pandas matplotlib seaborn`

Open the notebook in Jupyter Notebook or JupyterLab and execute each cell sequentially to perform the analysis and generate the results.

## **Contributing**

Contributions to the Markov Chain Analysis of the US Airport Network project are welcome! If you would like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
