# Movie Recommendation System

## Description

This repository contains the code and resources for a movie recommendation system using the k-nearest neighbors (KNN) algorithm. The system is built using Python and leverages popular libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn.

## Table of Contents

1. [Overview](#overview)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [Usage](#usage)
   - [1. Import Libraries](#1-import-libraries)
   - [2. Read CSV](#2-read-csv)
   - [3. Create SQL Database](#3-create-sql-database)
     - [3.1 Create SQLite Connection](#31-create-sqlite-connection)
     - [3.2 Save DataFrames in Database](#32-save-dataframes-in-database)
     - [3.3 Fusion Two Tables SQL for New Table](#33-fusion-two-tables-sql-for-new-table)
     - [3.4 Read New Table](#34-read-new-table)
     - [3.5 Close Database Connection](#35-close-database-connection)
   - [4. Use Only Selected Columns](#4-use-only-selected-columns)
   - [5. Text Processing](#5-text-processing)
   - [6. Change JSON: List to String](#6-change-json-list-to-string)
4. [Machine Learning - KNN](#machine-learning---knn)
   - [4.1 Import Libraries](#41-import-libraries)
   - [4.2 Text Vectorization](#42-text-vectorization)
   - [4.3 Similarity Matrix](#43-similarity-matrix)
   - [4.4 Recommendation Function](#44-recommendation-function)
   - [4.5 User Input](#45-user-input)

## Overview

This project involves creating a movie recommendation system using the k-nearest neighbors (KNN) algorithm. The dataset used for this project includes information about movies, such as budget, genres, keywords, and cast details.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- seaborn
- sqlite3
- scikit-learn
