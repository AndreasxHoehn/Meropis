# Meropis an Artificial Population Generator for Geospatial Simulation
## **Overview**
Meropis is an artificial population generator for geospatial simulation. The population is of the fictional island mentioned by ancient Greek writer Theopompus of Chios. 
These sets of notebooks implements an **artificial population generator** that create mythical but deomgrapicaly realistic **adult demographic profiles** (16+ years) for geospatial analysis and policy simulation. The system simulates diverse adult populations across different geographic area types, with detailed household structures and individual socioeconomic attributes.

**Project Context:** This artificial population framework is specifically designed to generate:
- A synthetic adult population (individuals 16+ and their households)
- A census summary of those households  
- Survey samples from the population
- Mythical but deomgrapicaly realistic geospatial distributions of the island of Meropis

## **Purpose**
Generate statistically realistic **adult-only populations** with:
- **Demographic diversity** across 9 socioeconomic classes
- **Geographic variation** based on 8 urban/rural area types  
- **Household composition** reflecting adult living arrangements
- **Compatible relationships** based on multi-dimensional similarity metrics
- **Mythical but deomgrapicaly realistic** geographic distributions of the island of Meropis

## **Key Features**

### **1. Demographic Modeling**
- **9 Adult Demographic Profiles**: From affluent professionals to rural workers
- **Statistical Distributions**: Age, education, income, ethnicity 
- **Lifecycle Patterns**: Age-dependent household formation probabilities

### **2. Geographic Variation**  
- **8 Area Types**: Major cities, cities, university towns,  agricultural, coastal, market towns, remote areas
- **Urban/Rural Characteristics**: Distinct demographic mixes per area type

### **3. Intelligent Household Formation**
- **Person-First Approach**: Individuals form households based on personal characteristics
- **Similarity-Based Matching**: Multi-factor compatibility scoring (age, education, income, ethnicity)
- **Probability-Driven Types**: Household type determined by individual profile × area characteristics
- **4 Household Structures**: Single person, couples, shared households, multi-generational adults

### **4. Statistical Foundations**
- **Roulette Wheel Selection**: Proportional sampling for demographic representation
- **Bayesian Probability Combination**: Multiply individual × area probabilities for household types
- **Reproducible Generation**: Seeded random number generation

### **5. Output Capabilities**
- **Census Summaries**: Aggregate statistics by household and demographic categories
- **Survey Samples**: Individual household detailed analysis
- **Flexible Scale**: From small tests to LSOA-sized populations (~1,500)
- **Adults-Only Focus**: All individuals 16+, suitable for voting, employment, taxation simulations

## **System Architecture**

```
Individual Generation → Household Formation → Census/Survey Output
       ↑                      ↑                      ↑
Demographic Profiles   Similarity Matching   Statistical Aggregation  
Area Type Definitions  Probability Blending  Flexible Sampling
```



----------------------------------------------------------------------------------------------------------------      

*Development Acknowledgments:
The demographic profiles, area type definitions and probability combination methodology were created with the assistance of
DeepSeek-R1 (2025-01-31 release). DeepSeek-R1 also assisted with code documentation,
debugging critical logic issues, and validating statistical approaches.*



