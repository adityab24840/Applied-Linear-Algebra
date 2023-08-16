# Movie Review Similarity Analysis

This Python script analyzes the similarity between movie reviews using movie vectors and generates visualizations of the most commonly used words.

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Generated Plots](#generated-plots)
- [Questions](#questions)

## Description

The script reads a movie review dataset from a CSV file, calculates review vectors for each movie, and then calculates the similarity between pairs of movies using the dot product and angle between vectors formulas. It identifies the top 3 pairs of movies that are very much alike based on their similarity scores.

Additionally, the script analyzes the most commonly used words in the movie reviews, counts their frequency, and generates a bar chart visualizing the top 10 most frequent words.

## Prerequisites

To run this script, you need:

- Python 3.x
- Pandas
- NumPy
- Matplotlib

You can install the required packages using the following command:

```bash 
pip install pandas numpy matplotlib
```

## Usage
1. Clone this repository to your local machine.

2. Place your movie review dataset CSV file (e.g., moviereviews.csv) in the same directory as the script.

3. Open a terminal or command prompt and navigate to the directory containing the script.

4. Run the script using the following command:
```bash
python movie_similarity_analysis.py
```

The script will calculate movie review vectors, identify similar movie pairs, and generate visualizations.

## Generated Plots
![Output Frequency of repeated words plot](https://github.com/adityab24840/ALA-Lab-work/blob/Assignment-3/ALA%20Assignment%203/effective_frequency_words_bar_chart.png)
This bar chart displays the top 10 most frequently used words in the movie reviews along with their frequencies.

![Output Movies Similarity Plot](https://github.com/adityab24840/ALA-Lab-work/blob/Assignment-3/ALA%20Assignment%203/similarity_bar_chart.png)
This horizontal bar chart visualizes the top 3 pairs of movies that are very much alike based on their similarity scores.

## Questions
### Write the dot product using numpy.dot() and compare with hand coded multiplication and addition as an alternative. How much speedup do you see with numpy.dot()? Why?

numpy.dot() efficiently calculates this product using optimized routines written in C, allowing for parallelization and vectorized operations.  
numpy.dot() offers a considerable speedup due to its optimized implementation and low-level optimizations.
It leverages optimized routines, parallelization, and hardware-level optimizations, resulting in significant speedup for calculating the dot product.
