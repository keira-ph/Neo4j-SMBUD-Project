# Neo4j-SMBUD-Project

# Systems and Methods for Big and Unstructured Data Project

**Author**: Chiara Fossà  
**Group Number**: 63  
**Academic Year**: 2023-2024  

## Overview

This project explores the "Mexican Crime Statistics: Comprehensive Incident Dataset" covering the years 2015 to 2023. The aim is to analyze crime patterns in Mexico using Neo4j, a graph database technology, to uncover complex relationships in the data.

## Table of Contents

1. **Introduction**
   - Overview of the dataset and the chosen technology.
2. **Dataset**
   - Description of the Mexican Crime Statistics dataset.
   - Structure and key attributes of the dataset.
3. **Database Implementation**
   - Implementation of the dataset in Neo4j.
   - Overview of node and relationship types.
4. **Queries**
   - Various queries executed to extract insights from the dataset.

## 1. Introduction

This project addresses criminal activity in Mexico by utilizing a dataset sourced from the official Mexican government website. The dataset provides a comprehensive overview of criminal incidents reported over several years, allowing for an in-depth analysis of crime trends, categories, and geographical variations.

### 1.1 The Dataset

The dataset includes records from 2015 to October 2023, encompassing 332,416 entries. It categorizes crimes based on various criteria, such as type, subtype, modality, and geographical location, making it a rich resource for understanding crime dynamics in Mexico.

### 1.2 The Technology

Neo4j was selected for this project due to its ability to efficiently manage and analyze complex relationships within the dataset. The graph database structure allows for dynamic exploration of the connections between different crime types, locations, and time periods, facilitating a deeper understanding of criminal patterns.

## 2. Dataset

The "Mexican Crime Statistics: Comprehensive Incident Dataset" is structured in CSV format and includes the following key attributes:

- **Year**: The year of the reported crime.
- **Entity Code**: A numeric identifier for the geographical region.
- **Entity**: The name of the state or region where the crime occurred.
- **Affected Legal Good**: The general category of the legal good affected by the crime.
- **Type of Crime**: The general category of crime.
- **Subtype of Crime**: A more detailed classification of the crime.
- **Modality**: Describes how the crime was committed (e.g., with or without violence).
- **Month**: The month in which the crime was reported.
- **Count**: The number of reported incidents for each crime.

## 3. Database Implementation

In Neo4j, the dataset was implemented with eight node types and five relationship types. The nodes include:

- **Place**: Representing geographical regions.
- **Year**: Representing the year of the crime.
- **Month**: Representing the month of the crime.
- **Crime Category**: General categories of crime.
- **Crime Type**: More specific classifications of crime.
- **Crime Subtype**: Detailed classifications within crime types.
- **Crime Modality**: Specific methods of committing crimes.
- **Number**: The count of occurrences for specific crime types.

The relationships help connect the various nodes, illustrating how different elements interact within the dataset.

## 4. Queries

A series of queries were executed to extract meaningful insights from the dataset. Some notable queries include:

- **Total Crimes**: Counting the total number of crimes committed from 2015 to 2023.
- **Crime Categories**: Identifying the categories into which reported crimes fall.
- **Regional Analysis**: Analyzing crime types in specific regions, such as Chihuahua.
- **Historical Context**: Investigating specific crime incidents, such as abortion-related crimes before legalization.
- **Crime Frequency**: Finding the most frequently reported crime in the dataset and its temporal distribution.
- **Violent Crimes**: Identifying crimes committed with violence and their corresponding types.
- **Data Integrity**: Assessing the dataset for entries with zero reported crimes to streamline the data.

This project aims to contribute to the understanding of crime in Mexico through a data-driven approach, enabling stakeholders to make informed decisions based on the analysis of trends and patterns in crime statistics.
