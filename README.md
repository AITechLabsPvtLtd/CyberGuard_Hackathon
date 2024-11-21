
---

# Hackathon Project: Text Classification for Government of India Categories

## Project Overview

This hackathon project involves a rich, unstructured text dataset with approximately **1.56 lakh rows**. The challenge is to classify these raw text descriptions into various **subcategories** and then into **broader categories**. This classification must align with the **rules and regulations of the Government of India**. The project allows participants to develop an understanding of these categories and apply machine learning to achieve accurate and meaningful classification.

## Problem Statement

Participants are provided with a dataset containing raw text descriptions. The **objective** is to:
- **Classify** these text descriptions into **subcategories** and subsequently into **categories**.
- **Explore and understand** the dataset to define the context and meaning of each category and subcategory.
- **Ensure compliance** with Government of India rules and regulations by aligning definitions accordingly.

This project requires participants to gain insights into each category and subcategory by analyzing the text data, making it essential to interpret both semantic and contextual information accurately.

## Dataset

The dataset consists of around **1.56 lakh rows** of unstructured text, covering diverse categories relevant to government classifications. Participants should download and examine the dataset thoroughly to create project pipelines and classification models. Only after familiarizing themselves with the data should participants proceed with classification tasks.

### Key Dataset Characteristics:
- **Rows**: Approximately 1.56 lakh unstructured text descriptions
- **Categories**: Broad government categories with specified subcategories
- **Goal**: Accurate classification aligned with Government of India guidelines

## Solution Approach

We are leveraging the **LLaMA 3.1 40B** language model for classification. LLaMA 3.1 is known for its efficiency in handling large-scale text classification and unstructured data, making it well-suited for this project. The model helps in understanding and categorizing the dataset, ensuring compliance with the necessary classification structure and guidelines.

## Screenshots

To understand the structure and flow of the classification, see the screenshots below:

- ![complaint2](https://github.com/user-attachments/assets/503df6b9-b361-4221-b18b-26b2966966ce)
- ![complaint1](https://github.com/user-attachments/assets/e1e2f34c-d46b-4cf1-bba7-d99ee259f9b1)
- ![complaint3](https://github.com/user-attachments/assets/3e71aa40-3d3b-4094-a73e-92f931a20a13)

These images illustrate examples of how the model performs classification on the dataset, showcasing its capabilities in interpreting and categorizing raw text data.

## Project Requirements

- **LLM Model**: LLaMA 3.1 70B
- **Data Processing**: Python, NLP libraries (like Hugging Face Transformers), and data management tools
- **Model Training**: Ensure model aligns category definitions with Government of India rules and regulations

## Getting Started

1. **Download Dataset**: Obtain the dataset provided in the hackathon.
2. **Set Up Environment**: Install Python, LLaMA 3.1 70B, and any other necessary dependencies.
3. **Model Training**: Train and fine-tune LLaMA 3.1 on the dataset for accurate classification.
4. **Evaluation**: Verify the model's classification output aligns with category definitions.

## Contributing

We welcome contributions! If you have ideas for improving the project, feel free to submit a pull request.


---

This README gives an overview, requirements, and instructions, helping participants to understand the project scope and get started quickly.
