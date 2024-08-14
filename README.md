# 🌸 GA-Iris-Clustering 🌱

## Overview
This repository contains a Jupyter notebook that implements a **Genetic Algorithm (GA)** for clustering the famous **Iris dataset**. The Genetic Algorithm is an evolutionary technique inspired by natural selection, which is used to optimize the clustering process. This approach is particularly useful when traditional clustering algorithms, like K-means, might not yield satisfactory results due to their reliance on initial conditions or assumptions about cluster shapes.

## ✨ Overview
- 🧬 **Genetic Algorithm for Clustering**: Utilizes the GA to evolve a population of cluster solutions.
- 📊 **Iris Dataset**: Applies the GA to one of the most well-known datasets in machine learning.
- 🔧 **Customizable Parameters**: Allows tuning of GA parameters such as population size, mutation rate, and crossover probability.
- 📈 **Visualizations**: Includes visualizations to help understand the clustering results and the evolution of solutions over generations.

## 🚀 Getting Started

### Prerequisites
- 🐍 Python 3.6 or higher
- 📒 Jupyter Notebook
- 📦 Required Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/GA-Iris-Clustering.git
    ```
2. Navigate to the project directory:
    ```bash
    cd GA-Iris-Clustering
    ```
3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Notebook
1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `GA clustering.ipynb` file.
3. Run all cells to execute the Genetic Algorithm and observe the clustering results.

## 🧠 Code Explanation
The notebook follows these main steps:
1. **Data Preprocessing**: Load and prepare the Iris dataset for clustering.
2. **Genetic Algorithm Implementation**: Define the genetic operators (selection, crossover, mutation) and the fitness function used to evaluate cluster quality.
3. **GA Execution**: Run the GA over multiple generations to evolve cluster solutions.
4. **Visualization**: Plot the results to visualize the clustering output and evolution process.

## 📊 Results
The genetic algorithm typically converges to a set of clusters that optimize the chosen fitness function, providing an alternative approach to traditional clustering methods. The results include cluster centroids, cluster assignments, and visual representations of the clustered data.

## 🎛️ Customization
Users can experiment with different parameters such as:
- **Population Size**
- **Mutation Rate**
- **Crossover Probability**
- **Number of Generations**

This flexibility allows for exploring different evolutionary paths and potentially improving clustering results.

## 🤝 Contributions
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## 🙏 Acknowledgments
- The Iris dataset used in this project is a classic dataset in machine learning, originally published by Ronald A. Fisher in 1936.
- The implementation of the genetic algorithm was inspired by various evolutionary computation literature and tutorials.
  
## 📬 Contact
For any questions, feedback, or further information, feel free to reach out:
📧 [aparsa.khadem@gmail.com](mailto:aparsa.khadem@gmail.com)
