---
title: How to prepare for a GitHub repository?
linktitle: GitHub Repository
# summary: The presentation tips are based on Dr. Chao's comments for past lab presentations
authors:
- Qiang-Qiqi
tags:
- lab
date: '2025-11-28'
type: book
toc: true
weight: 3
---


## 1. Create a GitHub Account

Before getting started, you need to register and create a GitHub account at https://github.com.
{{< figure src="screenshot.png" title="Missing female births around the world during 1970--2017 (see [PNAS Fig.3](https://www.fengqingchao.com/files/1908359116.full.paper.pdf))" >}}

## 2. Run the Code Locally

Before changing anything on GitHub, make sure your entire project runs smoothly on your local machine. This includes:

- All scripts run without errors
- Required packages and dependencies are installed
- Inputs and outputs are correct
- No unexpected warnings or crashes

Local verification ensures that the version you publish is stable and reproducible.

Note: If you need data which doesn't contain in the project, email professor with the list of all needed data. Also, if you are not sure whether the data is needed or not, also email the professor to confirm.

## 3. Code Cleaning

Code cleaning is one of the most important steps before publishing your project.

### 3.1 Pay Attention to Spaces

According to the Google R Style Guide’s spacing rules Google's R Style Guide:

- Add spaces around all binary operators (`=`, `+`, `-`, `<-`, etc.).
- Never put a space **before** a comma; always put a space **after** it.
- Do not add unnecessary spaces inside parentheses.
- Extra spaces may be used to align code for readability.

GOOD:

```
total <- sum(x[1, ])
if (debug)
```

BAD:

```R
total<-sum(x[,1])
if( debug )
```

------

### 3.2 Remove Unnecessary Code with #

Some R code in the script will have comments, commented code should be deleted.

GOOD:

```R
a <- 5
b <- 3
# Then we can calculate c
c <- a*b
```

BAD:

```R
a <- 5
b <- 3
# Then we can calculate c
# c <- a+b
c <- a*b
```

------

### 3.3 Use Structured Comments

Following the Commenting Guidelines and Function Documentation sections of the Style Guide Google's R Style Guide:

#### **Rules for Structured Comments**

- Full-line comments start with `# `
- Inline comments have two spaces before `#`
- Comments should explain **why**, not just **what**

#### **Recommended Function Documentation Template:**

```R
FunctionName <- function(arg1, arg2, verbose = TRUE) {
  # One-sentence description of what the function does.
  #
  # Args:
  #   arg1: Description and expected type.
  #   arg2: Description and expected type.
  #   verbose: Logical flag indicating whether to print additional info.
  #
  # Returns:
  #   Explanation of the returned value.
  
  ...
}
```

The concrete example can be seen on the GitHub.

## 4. Add README.md

The following content is the template for the readme.md.

*(Copy this into your GitHub repository’s README.md file and modify as needed.)*

## Project Title

**[Your Project Title Here]**

## Project Summary

This repository contains the analysis and modeling work for **[brief description]**.
 The project applies **[method/model]** to study **[topic]**, using data collected from **[source(s)]**.
 The aim of the analysis is to **[research goal / context]**.

Please refer to the related publication for details on background, methodology, data sources, and broader implications:

**Main paper:**
 [Author 1], [Author 2] (Year). *Paper Title*. Journal Name, Volume(Issue), pages.

------

## Repository Structure

The repository contains two main components: **code** and **data**.

### Running the Code

- Give the example code here and explain.

### Input Data

- Give the explain for the input data.

------

## Research Context

This project investigates **[research question/topic]**, using a **[model description]** approach.
 Unlike previous studies that focus on **[existing limitations]**, this project provides **[contributions]**.
 The goal is to **[research objective]** using a structured database and statistical modeling.

We estimate/project **[variable]** for **[units / time range]** using a **[model type]**.
 The database includes **[description of data]** compiled from **[sources]**.

------

## Methodology

- Give the explanation of the methodology of the project.

### Key Scripts Related to the Model

- Give the explanation for the key scripts.

------

## Contributors of this page

- Qiqi Qiang, last updated on 2025 Nov 28.

<div align="right">Chao Lab Documentations</div>