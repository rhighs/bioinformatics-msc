# Bioinformatics for Computational Genomics

This website is designed as a central hub for notes, scripts, and resources accumulated during the [MSc in Bioinformatics for Computational Genomics](https://www.unimi.it/en/education/master-programme/bioinformatics-computational-genomics). The goal is to provide a structured collection of materials for students and anyone interested in bioinformatics and related fields.

## Quick links

{% macro render_toc(pages) %}
<ul>
{% for page in pages %}
  <li>
    <a href="{{ page.url }}">{{ page.title }}</a>
    {% if page.children %}
      {{ render_toc(page.children) }}
    {% endif %}
  </li>
{% endfor %}
</ul>
{% endmacro %}
{{ render_toc(navigation.pages) }}

---

### Core contents in a few words

This website includes comprehensive lecture notes covering key concepts and methodologies in subjects like Organic Chemistry, Statistics, Genetics, and Molecular Biology.
It also provides scripts and code examples written in Python, R, and Bash to demonstrate practical bioinformatics tools, such as BioPython and R for statistical analysis.
Additionally, documentation for assignments and group projects showcases real-world applications, including data analysis, machine learning in genomics, and statistical model building.

--- 

### Courses table

| Course                                      | Max ECTS | Hours | Period          | Language | SSD                   | Lesson Link                                                                                                                | Course Info                                                                                                        |
|---------------------------------------------|----------|-------|-----------------|----------|-----------------------|----------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|
| Advanced Genomics and Epigenomics            | 12       | 96    | First semester  | English  | BIO/18 BIO/19          | [Advanced Genomics and Epigenomics](https://gpavesiage.ariel.ctu.unimi.it)                                                  | [Advanced Genomics and Epigenomics](https://www.unimi.it/en/ugov/of/af20250000f4b-10)                              |
| Biochemistry                                | 6        | 48    | First semester  | English  | BIO/10                | [Biochemistry](https://lgourlayb.ariel.ctu.unimi.it) / [Biochemistry (2024/25)](https://myariel.unimi.it/course/view.php?id=2886)  | [Biochemistry](https://www.unimi.it/en/ugov/of/af20250000f4b-12)                                                   |
| Bioinformatics and Computational Biology    | 6        | 48    | First semester  | English  | ING-INF/05            |                                                                                                           | [Bioinformatics and Computational Biology](https://www.unimi.it/en/ugov/of/af202500000f4b-5)                        |
| Biostatistics                               | 6        | 60    | Second semester | English  | MAT/06 SECS-S/01      |                                                                                                           | [Biostatistics](https://www.unimi.it/en/ugov/of/af202500000f4b-7)                                                  |
| Genetics, Cellular and Molecular Biology    | 12       | 96    | First semester  | English  | BIO/11 BIO/13 BIO/18  | [Genetics, Cellular and Molecular Biology](https://gcmb.ariel.ctu.unimi.it) / [2024/25 Edition](https://myariel.unimi.it/course/view.php?id=5200) | [Genetics, Cellular and Molecular Biology](https://www.unimi.it/en/ugov/of/af20250000f4b-11)                        |
| Genomic Big Data Management and Computing   | 6        | 48    | First semester  | English  | BIO/11 ING-INF/05     |                                                                                                           | [Genomic Big Data Management and Computing](https://www.unimi.it/en/ugov/of/af20250000f4b-17)                      |
| Genomics and Transcriptomics                | 12       | 96    | Second semester | English  | BIO/11                | [Genomics and Transcriptomics](https://gt.ariel.ctu.unimi.it)                                                              | [Genomics and Transcriptomics](https://www.unimi.it/en/ugov/of/af202500000f4b-3)                                   |
| Interdisciplinary Project                   | 6        | 48    | First semester  | English  | BIO/11 ING-INF/05     |                                                                                                           | [Interdisciplinary Project](https://www.unimi.it/en/ugov/of/af20250000f4b-18)                                      |
| Language Skills and Other Activities        | 3        | 0     | Year            | English  | —                     |                                                                                                           | [Language Skills and Other Activities](https://www.unimi.it/en/ugov/of/af20250000f4b-19)                           |
| Machine Learning                            | 6        | 60    | Second semester | English  | INF/01 ING-INF/05     |                                                                                                           | [Machine Learning](https://www.unimi.it/en/ugov/of/af202500000f4b-9)                                              |
| Neurogenomics and Brain Disease Modelling   | 6        | 48    | First semester  | English  | BIO/11                | [Neurogenomics and Brain Disease Modelling](https://gtestanbdm.ariel.ctu.unimi.it)                                          | [Neurogenomics and Brain Disease Modelling](https://www.unimi.it/en/ugov/of/af20250000f4b-16)                      |
| Organic Chemistry                           | 6        | 48    | First semester  | English  | CHIM/06               | [Organic Chemistry](https://lbelvisioc.ariel.ctu.unimi.it) / [2024/25 Edition](https://myariel.unimi.it/course/view.php?id=4257) | [Organic Chemistry](https://www.unimi.it/en/ugov/of/af202500000f4b-2)                                              |
| Programming and Data Bases                  | 12       | 96    | First semester  | English  | INF/01 ING-INF/05     |                                                                                                           | [Programming and Data Bases](https://www.unimi.it/en/ugov/of/af20250000f4b-13)                                     |
| Scientific Programming                      | 6        | 60    | Second semester | English  | ING-INF/05            |                                                                                                           | [Scientific Programming](https://www.unimi.it/en/ugov/of/af202500000f4b-6)                                         |
| Statistics                                  | 6        | 48    | First semester  | English  | MAT/06 SECS-S/01      |                                                                                                           | [Statistics](https://www.unimi.it/en/ugov/of/af20250000f4b-14)                                                     |
| Structural Chemistry                        | 6        | 48    | First semester  | English  | CHIM/06 ING-IND/34    | [Structural Chemistry](https://psenecirdscbm.ariel.ctu.unimi.it) / [2024/25 Edition](https://myariel.unimi.it/course/view.php?id=3136) | [Structural Chemistry](https://www.unimi.it/en/ugov/of/af202500000f4b-4)                                           |
| Systems Biology and Network Analysis        | 6        | 48    | First semester  | English  | ING-INF/06            |                                                                                                           | [Systems Biology and Network Analysis](https://www.unimi.it/en/ugov/of/af202500000f4b-8)                           |
| Thesis Project and Final Dissertation       | 21       | 0     | Year            | English  | —                     |                                                                                                           | [Thesis Project and Final Dissertation](https://www.unimi.it/en/ugov/of/af20250000f4b-15)                          |


---

## Requesting changes

If you find any typos, inconsistencies, or would like to suggest improvements, you can request changes via

- [Github: rhighs/bioinformatics-msc](https://github.com/rhighs/bioinformatics-msc)
