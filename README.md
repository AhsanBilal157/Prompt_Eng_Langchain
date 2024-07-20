# Prompt Engineering with LangChain


Welcome to the **Prompt Engineering with LangChain** repository! This repository showcases the implementation of prompt engineering tasks using LangChain, specifically focusing on generating social media posts and personalized study timetables.

## Table of Contents

- [Introduction](#introduction)
- [Repository Structure](#repository-structure)
- [Tasks Overview](#tasks-overview)
  - [Task 1: Social Media Post Writer](#task-1-social-media-post-writer)
  - [Task 2: Timetable Generator](#task-2-timetable-generator)
- [Getting Started](#getting-started)
- [Usage](#usage)

## Introduction

This repository contains two main tasks implemented using LangChain and the gemma2 model from Ollama. Each task is designed to demonstrate the capabilities of prompt engineering in real-world applications.

## Repository Structure

```plaintext
.
├── social_media_post
│   └── social_media_post_task.ipynb
├── timetable
│   └── timetable_task.ipynb
├── LICENSE
├── README.md
└── requirements.txt
```
- **social_media_post:** Contains the Jupyter notebook for the social media post writer task.
- **timetable:** Contains the Jupyter notebook for the timetable generator task.
- **README.md:** This README file.
- **requirements.txt:** List of required packages.


## Tasks Overview
### Task 1: Social Media Post Writer
**Objective**
Write a prompt to generate a social media post based on user-provided answers to a questionnaire. The generated post should be professional, engaging, and similar in tone and structure to a given example.

**Implementation**
- Input: User answers to a questionnaire.
- Output: A professionally crafted social media post.
- Methodology:
  - Defined a system prompt to set the context for the task.
  - Created a user prompt template with placeholders for the questionnaire answers.
  - Combined the system and user prompts into a single template.
  - Utilized LangChain and gemma2 model to generate the social media post.

**Folder:** ```social_media_post```

The implementation of this task is detailed in the `social_media_post_task.ipynb` notebook.

### Task 2: Timetable Generator
**Objective**
Design a detailed prompt to create personalized study plans for students. The prompt should consider various student-specific data, including subjects, academic performance, learning styles, extracurricular activities, and personal objectives.

**Implementation**
- Input: Diverse student-specific data.
- Output: A personalized study timetable.
- Methodology:
  - Analyzed the student's data to understand their unique needs.
  - Created a prompt to generate a study plan that addresses academic requirements and aligns with the student's aspirations.
  - Utilized LangChain to process and synthesize the information into a comprehensive study plan.

**Folder:** `timetable`

The implementation of this task is detailed in the `timetable_task.ipynb` notebook.


## Getting Started
### Prerequisites
Ensure you have the following installed:

- Python 3.8 or later
- Jupyter Notebook
- Required packages (listed in requirements.txt)

**Installation**
Clone the repository:
```
bash
git clone https://github.com/AhsanBilal157/Prompt_Eng_Langchain.git
cd Prompt_Eng_Langchain
```

Install the required packages:
```
bash
pip install -r requirements.txt
```
Install the Ollama packages:
for linux
```
bash
curl -fsSL https://Ollama.com/install.sh | sh
```
for windows visit : https://github.com/Ollama/Ollama

Run Gemma2 model from Ollama
```
bash
Ollama run gemma2
```

## Usage
### Running the Notebooks
1. Navigate to the desired task folder (social_media_post or timetable).

2. Open the Jupyter notebook:
```
bash

jupyter notebook social_media_post_task.ipynb
# or
jupyter notebook timetable_task.ipynb
```
Follow the instructions within the notebook to run the cells and generate the outputs.





