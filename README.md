# 📚 Schools Data Analysis Project

A data-driven analysis focused on schools in Punjab Pakistan, aiming to identify areas for strategic funding allocation, evaluate current infrastructure and resources, and highlight educational needs in the region.

## 📑 Table of Contents

0. [Dataset Overview](#dataset-overview)
1. [Project Overview](#project-overview)
2. [Technologies and Tools Used](#technologies-and-tools-used)
3. [Dataset Overview](#dataset-overview)
4. [Key Analysis Questions](#key-analysis-questions)
5. [Insights and Findings](#insights-and-findings)
6. [How to Use](#how-to-use)

## 📊 Dataset Overview

The dataset consists of school information, infrastructure details, and resource availability. Due to GitHub's file size limitation, the dataset is split into two parts:

- `Schools_Dataset 0.0`
- `Schools_Dataset 0.1`

## 📈 Project Overview

This project examines schools across Punjab to guide an international ed-tech company investing in local educational infrastructure. Through analysis, we identify regions needing improvement and offer insights into resource allocation, enrollment trends, and school facilities.

## 🛠️ Technologies and Tools Used

- **Microsoft Excel** for data cleaning, manipulation, and preliminary analysis
- **Power BI** for advanced data visualization and dashboard creation

## 📊 Dataset Overview

The dataset consists of school information, infrastructure details, and resource availability, including columns like:

| Column Name               | Description                                                            |
|---------------------------|------------------------------------------------------------------------|
| `school_id`               | Unique identifier for each school                                     |
| `district`                | District where the school is located                                  |
| `school_gender`           | Indicates if the school is for male, female, or co-education          |
| `school_level`            | Educational level offered (Primary, Secondary, Higher)                |
| `bldg_condition`          | Building condition status (Satisfactory, Poor, etc.)                  |
| `teachers`                | Number of teachers available                                          |
| `non_teachers`            | Number of non-teaching staff                                          |
| `enrollment`              | Total number of students enrolled                                     |
| `electricity`             | Availability of electricity                                           |
| `boundary_wall`           | Indicates if the school has a boundary wall                           |

*...and more detailed attributes related to school facilities, student enrollment, and staffing.*

## 🔍 Key Analysis 

1. **Total Schools:** Determine the total number of schools in the dataset.
2. **Enrollment by School Gender:** Identify the school levels with the lowest number of male and female students.
3. **Top Districts by Staff:** Find the top 5 districts with the highest number of teachers and non-teachers.
4. **Classroom Functionality:** Explore which school levels and mediums have the lowest number of functional classrooms.
5. **School Distribution by Area:** Calculate the number and percentage of schools in rural vs. urban areas, and mediums (Urdu, English, or both).
6. **District Enrollment Trends:** Identify districts with the highest enrollment in primary, secondary, and higher secondary schools.
7. **Building Condition:** Determine the percentage of schools with satisfactory building conditions.
8. **Facilities Shortage:** List districts with the lowest availability of electricity, drinking water, and toilets.

## 🔍 Insights and Findings

- **Total Schools:** There are 48,191 schools recorded.
- **Student Enrollment:** Secondary and sMosque schools have the lowest enrollment numbers for male (19 and 16) and female (51 and 0) students.
- **Top Districts by Staff:** Faisalabad has the highest number of teachers (22,996) and non-teachers (4,918).
- **Building Condition:** 70.28% of schools have satisfactory building conditions.
- **Security and Facilities:** 33,871 schools report having satisfactory security measures.
- **Facilities Shortages:** Certain districts like Chiniot and Hafizabad show a shortage in basic facilities like water and electricity.

## 📊 Visual Representations

- **Bar Chart:** Distribution of teachers across different school levels.
- **Pie Chart:** Proportion of schools with vacant vs. filled teaching and non-teaching posts.
- **Bar Chart:** School distribution by educational level (primary, secondary, etc.).
- **Table:** Comparison of schools based on ownership (public vs. private).
- **Map Visualization (Power BI):** Highlighting schools with critical resource shortages.

## 📂 How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/punjab-schools-analysis.git
