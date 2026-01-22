# Gender, language, and knowledge representation on Wikipedia 
### Final Group Project – Group 3
<sup> Christina, Felipe, Lise Maartje </sup>

In this repositoy, you will find our final version of the project for the course Collecting Data. We aim to investigate how gender and language shape representation on Wikipedia. We focus on biographical articles of twentieth-century writers from **Chile**, **Greece**, and the **Netherlands**. 

<img width="402" height="280" alt="image" src="https://github.com/user-attachments/assets/9a0bd26c-6a73-404b-bf32-f928f9f8b9d0"/> 

### Research Question:
_Do Wikipedia biographies of men and women differ systematically in their structure and level of detail, and do these differences vary between native-language and English editions?_ 

The data that is used in this project were collected using the [Wikipedia API](https://en.wikipedia.org/wiki/Special:RestSandbox/wmf-restbase). <br/> The analysis focuses on structural characteristics of the articles, including their length, number of references, and number of images. Ratios between English and native-language versions are calculated to examine how coverage changes when biographies move into English. <br/> **Statistical tests** and **visualizations** were used to identify patterns. 

The repository consists of three parts: 
1.  **Introduction & Background** <br/>
The motivation for our project and some important background literature. 
2.  **Tutorial** <br/>
A discursive explanation of the code we used in the research. 
4.  **Output and Active Learning Exercises**  <br/>
The Output and Active Learning Exercises consists of a **research poster** and an **interactive quiz**. The poster visually summarizes the research questions, methods, and key findings, presenting the results in an accessible format. The quiz is designed as an active learning exercise, encouraging viewers to engage critically with the findings by interpreting visualizations and reflecting on gender bias and international visibility on Wikipedia.

> [!IMPORTANT]
> **Scan the QR code within the poster to access the interactive quiz.**

### Prerequisites

- Python 3.8+
- pip package manager
- Jupyter Notebook or JupyterLab

## What the Notebook Analyzes

### Metrics Extracted (for each writer)

| Metric | Description |
|--------|-------------|
| **Word Count** | Total words in article |
| **EN/Native Ratio** | English words ÷ Native words |
| **Images** | Number of visual resources |
| **References** | Number of citations |
| **Internal Links** | Cross-references to other articles |
| **Sections** | Article structural complexity |
| **Languages** | Number of available language editions |

### Statistical Analysis

- Descriptive statistics by gender
- Independent samples t-tests
- Country-level comparisons
- Visualization of patterns

## Sample Writers

### Chile
- **Women:** Gabriela Mistral, Isabel Allende, Marcela Paz
- **Men:** Pablo Neruda, Roberto Bolaño, José Donoso

### Greece
- **Women:** Kiki Dimoula, Katerina Gogou, Katerina Anghelaki-Rooke
- **Men:** Dinos Christianopoulos, Manolis Anagnostakis, Nikos Kavvadias

### Netherlands
- **Women:** Annie M.G. Schmidt, Hella Haasse, Renate Dorrestein
- **Men:** Harry Mulisch, Gerard Reve, Jan Wolkers

## Data Source

All data is collected from Wikipedia via the [MediaWiki API](https://www.mediawiki.org/wiki/API:Main_page) in accordance with Wikipedia's Terms of Use for academic research.


