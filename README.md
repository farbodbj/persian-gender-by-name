---
license: apache-2.0
language:
- fa
- en
pretty_name: gendery by name persian
size_categories:
- 10K<n<100K
---

# Persian Gender Detection by Name

A comprehensive dataset for determining gender based on Persian names, enriched with English representations.

## Overview

The **Persian Gender Detection by Name** dataset is the largest of its kind, comprising approximately **22,000** entries. Each entry includes a Persian name, its corresponding gender, and the English transliteration. This dataset is designed to facilitate accurate gender detection and enhance searchability through multiple name representations.

## Features

- **Extensive Data**: ~22,000 name-gender-English tuples.
- **Multiple Representations**: Various spellings and formats for each name to improve search flexibility.
- **High Quality**: Aggregated from reliable sources and meticulously hand-cleaned for accuracy.
- **Expandable**: Plans to incorporate more names and data sources in the future.

## Data Sources

This dataset aggregates information from the following primary sources:

- [Iranian Names Database By Gender](https://github.com/nikahd99/iranian-Names-Database-By-Gender)
- [Persian Names Gender Dataset on Kaggle](https://www.kaggle.com/datasets/misssahar75/persian-names-gender)

Additionally, supplementary data was scraped and manually cleaned to ensure consistency and completeness.

## Data Structure

The dataset is organized in a CSV format with the following columns:

- **Name**: The Persian name.
- **Gender**: Assigned gender (e.g., Male, Female).
- **English Representation**: The transliterated version of the Persian name.

**Example:**

| Name  | Gender | English Representation |
|-------|--------|------------------------|
| علی   | M   | Ali                    |
| زهرا | F | Zahra                  |

## Usage

This dataset is ideal for:

- Developing gender prediction models based on Persian names.
- Academic research in linguistics, gender studies, and natural language processing.
- Enhancing search algorithms with multilingual name representations.

## Future Enhancements

Future updates will focus on:

- Expanding the dataset with additional names and gender associations.
- Incorporating more diverse sources to cover a broader range of names.
- Refining data quality through ongoing cleaning and validation processes.

## Acknowledgments

Thanks to the contributors of the original datasets and those who assisted in data aggregation and cleaning.
