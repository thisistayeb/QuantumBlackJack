# Quantum Blackjack

Welcome to Quantum Blackjack! This project offers a unique twist on the classic card game, implemented using Python and Qiskit. Instead of relying purely on chance, you'll leverage quantum principles like **superposition**, **entanglement**, and **measurement** to outsmart your opponent and the dealer.

This repository contains two distinct versions of the same game, both provided as Jupyter Notebooks:

1.  **`QuantumBlackJack.ipynb`**: A command-line version where you interact with the game through text-based prompts directly in the notebook's output cells.
2.  **`QuantumBlackJack-withGUI.ipynb`**: An enhanced version featuring a user-friendly Graphical User Interface (GUI) powered by `ipywidgets`, offering a more visual and interactive experience.



---

## Getting Started

To play either version of the game, you first need to set up a dedicated Python environment. The following steps will guide you through creating a Conda environment and installing all the necessary dependencies from the `requirements.txt` file.

### Prerequisites

* You have [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system.
* You have `git` installed to clone the repository.

### Setup Instructions

**1. Create a Conda Environment**

Open your terminal or Anaconda Prompt and run the following command to create a new Conda environment named `quantum-blackjack` with Python 3.12.

```bash
conda create --name quantum-blackjack python=3.12 -y
