# Association Rule Mining: Apriori vs Brute Force

This project implements **Association Rule Mining** using two different algorithms — **Apriori** and **Brute Force** — to discover frequent itemsets and generate association rules from transactional datasets. It also compares the performance of both methods.

## 📌 Features

- Discover frequent itemsets from transaction data
- Generate strong association rules based on user-defined support and confidence
- Compare execution time of Apriori and Brute Force approaches
- Accepts dynamic input for:
  - Minimum support (in percentage)
  - Minimum confidence (in percentage)
  - Dataset selection (from preloaded options)

## 🧠 Algorithms Used

### Apriori
An efficient algorithm that uses a pruning strategy to avoid generating non-frequent itemsets, reducing computation time significantly.

### Brute Force
A naive approach that checks all possible item combinations to find frequent itemsets, useful for understanding the basic concept of association rule mining.

## 🗂️ Dataset Format

Each dataset (`Database1.csv`, `Database2.csv`, etc.) should contain transaction records where each line represents a transaction with items separated by commas.

**Example:**
milk, bread, butter bread, butter milk, cookies


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/association-rule-mining.git
   cd association-rule-mining
2. Place your datasets (e.g., Database1.csv) in the project directory.
3. Run the script
4. Enter the required input when prompted:

Minimum Support (e.g., 20)
Minimum Confidence (e.g., 30)
Dataset Number (1-5)

Output
Displays association rules that meet the support and confidence thresholds

Prints execution time for both algorithms

APRIORI ASSOCIATION RULES:
'milk' --> 'bread' Confidence: 75.0

BRUTE FORCE ASSOCIATION RULES:
'milk' --> 'bread' Confidence: 75.0

APRIORI RUN TIME: 0.01 seconds
BRUTE FORCE RUN TIME: 0.89 seconds
