# The ~Dance~ Data of the Dragons

## Introduction

This project examines the lineages, traits, and relationships of the dragons involved in the Targaryen civil war, known as the Dance of the Dragons, from George R. R. Martin’s *Fire & Blood* currently depicted in HBO's *House of the Dragon* series.
Using machine learning and genetic analysis, the goal is to accurately map the family connections between the dragons and predict traits for those without detailed descriptions. 
The final output includes a dragon family tree and original images created using a personally trained Stable Diffusion 3.0 model. 

## Quick Links

- [Project Webpage](https://phelpsbp.github.io/The-Dance-Of-The-Dragons-Project/)
- [The Dataset](https://github.com/phelpsbp/The-Dance-Of-The-Dragons-Project/blob/main/dragon_data.csv)
- [Project Notebook](https://github.com/phelpsbp/The-Dance-Of-The-Dragons-Project/blob/main/The%20Data%20of%20Dragons.ipynb)

## Project Overview

The project examines the family connections and traits of dragons involved in the Dance of the Dragons. Using a mix of data analysis, machine learning, and generative AI, it predicts characteristics for dragons with little to no documentation. The goal is to create an accurate family tree and visualize each dragon based on these predictions.

### Key Questions

1. How can we accurately map the family connections of the dragons based on known data?
2. What traits are passed down through generations, and can we use these traits to establish paternity? 
3. Can we use these traits to predict characteristics of dragons without specified physical characteristics?


## Methodology

1. **Data Loading and Preparation**: 
   - Load the dataset and clean it by removing missing or inconsistent values.
   
2. **Exploratory Dragon Analysis (EDA)**:
   - Explore the dataset using summary statistics and validate maternal relationships based on known lore.
   
3. **Genetic Trait Analysis**:
   - Identify dominant and recessive traits, such as scale color and eye color, passed down from older dragons like Balerion, Vhagar, and Meraxes.
   
4. **Paternity Assignment**:
   - Use trait dominance information along with machine learning techniques to assign paternity for dragons where this is unknown.
   
5. **Predictive Dragon Modeling**:
   - Use lineage data and trait inheritance patterns to predict physical characteristics of dragons with no canonical descriptions.
   
6. **Generative AI Model for Dragon Creation**:
   - Train a Stable Diffusion 3.0 model to generate visual representations of dragons based on the predicted traits.

7. **Final Dragon Family Tree**:
   - Create a visual family tree that showcases the relationships and predicted traits of each dragon involved in the Dance.

### Tools Used

- Python
- Pandas for data management
- Scikit-learn Decision Tree and Random Forest for machine learning
- Matplotlib for visualization
- Jupyter Notebook using Pretty-Jupyter magic functions (%%jmd)
- Stable Diffusion 3.0 for image generation
- Canva and Flourish for embedded graphics and headers

## Results

1. **Family Tree**:
   - A detailed tree mapping all dragons and their relationships.
   
2. **Trait Inheritance**:
   - Insights into which traits are passed down across generations.
   
3. **Paternity**:
   - Likely fathers were assigned to dragons without clear canon lineage.

4. **Predicted Traits**:
   - Traits for undocumented dragons were successfully predicted using genetic data.

5. **Dragon Images**:
   - Custom images were generated using the trained Stable Diffusion model, based on predicted traits.

## Acknowledgments & References

Unless otherwise specified, all headers, artwork, and graphics were created by me. I trained a custom Stable Diffusion 3.0 model to generate all the dragon images used in this project.

The data used for this analysis was compiled from the following sources:

### Books:

- Martin, George R. R. *Fire & Blood*. Bantam Books, 2018.
- Martin, George R. R. *The World of Ice and Fire*. Bantam Books, 2014.
- Martin, George R. R. *The Princess and The Queen*. Tor Books, 2013.

### Web Sources:

- A Wiki of Ice and Fire: https://awoiaf.westeros.org
- George R. R. Martin's "Not A Blog": https://georgerrmartin.com/notablog/

## Contact Information

- **Email**: [phelpsbp@gmail.com](mailto:phelpsbp@gmail.com)
- **LinkedIn**: [Brittany Phelps](https://www.linkedin.com/in/brittany-everette/)
- **GitHub**: [phelpsbp](https://github.com/phelpsbp)
