# Big Data

This repository contains basic programs to analyze Big Data using Hadoop. It includes hands-on experiments and examples that demonstrate how to set up a Hadoop environment, execute basic Hadoop commands, and perform data analysis tasks such as word counting and stock analysis. The programs here are aimed at helping users understand how to work with large datasets and derive useful insights.

## Table of Contents

- [Installation and Setup](#installation-and-setup)
- [Experiments](#experiments)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Installation and Setup

1. Install Hadoop in a single-node cluster configuration using the steps provided in **Exp 01**.
2. Follow the setup steps to configure and test your Hadoop environment.

---

## Experiments

This repository includes the following experiments:

### Exp 01 - Installing Hadoop Single Node Cluster Configuration
- **Description:** Step-by-step instructions for installing and configuring a single-node Hadoop cluster.
- **Usage:** Follow this guide to set up your own Hadoop environment, which will be required for subsequent experiments.

### Exp 02 - Hadoop Commands
- **Description:** A list of basic Hadoop commands for interacting with the Hadoop Distributed File System (HDFS).
- **Usage:** Learn and practice these commands to effectively manage data in HDFS.

### Exp 03 - Word Count Programs
These programs count occurrences of words in a text file and sort them in ascending order. Different versions of the word count program demonstrate the use of different delimiters and target words.
- **Word_Count:** Counts the number of occurrences of each word in a file, using spaces as delimiters.
- **Word_Count_Comma_Delimiter:** Similar to the above, but uses commas as delimiters.
- **Word_Count_Specific_word:** Counts how many times a specific word appears in the file.

### Exp 04 - Stock Analysis
- **Description:** Analyzes stock data based on stock names and other attributes.
- **Usage:** Perform data analysis on stock data to gain insights into stock trends and other metrics.

---

## Usage

1. Ensure Hadoop is installed and configured correctly by following **Exp 01**.
2. Use **Exp 02** to familiarize yourself with basic Hadoop commands.
3. Run the **Exp 03** programs to analyze text files for word counts, using different delimiters and search terms.
4. Use **Exp 04** to analyze stock data for trends and patterns.

### Running the Experiments
- Each experiment includes specific instructions within the respective folder.
- Upload data files to HDFS as required by each experiment.
- Execute the corresponding Hadoop or MapReduce jobs as instructed to see results.

---

## Contributing

Contributions are welcome! If you'd like to add new Big Data analysis experiments or improve existing ones, feel free to fork this repository and submit a pull request.

---

Happy Analyzing!
