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

## Requesting changes

If you find any typos, inconsistencies, or would like to suggest improvements, you can request changes via

- [Github: rhighs/bioinformatics-msc](https://github.com/rhighs/bioinformatics-msc)
