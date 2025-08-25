# Amazon Product Recommendation System

This project implements a content-based recommendation system for Amazon products.  
The system suggests products to users by analyzing product descriptions and calculating similarity between items using TF-IDF and cosine similarity.

---

## Project Overview

Recommendation systems are widely used in e-commerce to enhance customer experience and boost sales.  
This project focuses on building a **content-based recommendation system** that leverages product descriptions to recommend similar products.

---

## Features

- Data loading and preprocessing  
- Handling missing values  
- Visualizing product categories and price distributions  
- Text vectorization using **TF-IDF**  
- Similarity computation using **Cosine Similarity**  
- Recommendation function to suggest similar products  
- Evaluation framework for measuring system performance  

---

## Dataset

- **Source:** Amazon product dataset (10,000 product samples from January 2020).  
- **Contents:** Product category, product name, product description, price, and other metadata.  

---

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/recommendation-system.git
cd recommendation-system
pip install -r requirements.txt
