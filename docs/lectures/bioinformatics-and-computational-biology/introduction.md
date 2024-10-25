# Introduction to Bioinformatics

[TOC]

## What is Bioinformatics?

_The definition of bioinformatics is not universally agreed upon_, however we'll define it as...

> _"The creation and development of advanced information and computational technologies for problems in biology, most commonly molecular biology"_

In alternative, the following extended defition could be considered:

- Bioinformatics is an interdisciplinary field that combines biology, computer science, mathematics, and statistics to analyze and interpret biological data, especially large datasets. It primarily involves developing algorithms, computational models, and software tools to understand biological processes and systems.

### Definition of **Computational Biology** (according to the $ \text{NIH} $)

Computational Biology refers to the development and application of data-analytical and theoretical methods, mathematical modeling and
computational simulation tecniques to the study of biological, behavioral and, social systems.

**What is Systems Biology?**

It is the study of the interactions between components of a biological systems, and how these interactions give rise to the funciton and
behavior of that system.

To create models that describe all the interactions within a biological system, such as interactions between genes, proteins, or metabolic pathways. The goal is not just to study individual components, but to understand how they work together as a whole to drive the behavior and function of the system. Since the aim is to model all interactions in the system (which is a large and complex task), the experimental techniques that are best suited to systems biology are those that can capture data about the system on a large scale or "system-wide." This means techniques that gather data from many components simultaneously, rather than focusing on one or a few at a time.

**High throughput techniques??**

These are merely technologies that can generate a vast amount of data quickly and on a large scale, which are critical in systems biology. These methods provide the quantitative data (i.e. numerical measurements) needed to build and validate computational models. These models can then be used to predict how the system behaves, how it responds to changes, or how the interactions between components lead to the overall function of the system.

e.g. **NGS** (Next-generation sequencing)

> A technique that rapidly sequences large amounts of DNA or RNA, generating vast data. Processing this data often involves **GPUs** or **multiprocessing** to handle the massive computational demands for alignment, assembly, and analysis efficiently.

## Role of ICT (Information Communication Technologies)

- Management (store, integrate, query, search, retrieve, ...) and analysis of data and information (knowledge)
- Development of models and algorithms
- Implementation of instruments and services
- Creation of visualization tools

## Modern Bioinformatics and Computational Biology were born with the DNA sequencing projects

The sequencing of human DNA was first proposed in 1984 at a conference organized by the U.S. Department of Energy (DOE). This idea eventually led to the launch of the [Human Genome Project](https://en.wikipedia.org/wiki/Human_Genome_Project) in 1990, an international effort to map and sequence the entire human genome. A first draft of the project was finished and available to the public by June 2000. The project was then completed in 2003, providing a complete blueprint of human DNA.

In June 2000, the [International Human Genome Sequencing Consortium](https://www.genome.gov/11006939/ihg-sequencing-centers) (a public effort) and the private company [Celera Genomics](https://en.wikipedia.org/wiki/Celera_Corporation) announced the completion of the first draft of the human genome. This milestone marked significant progress in understanding human genetics.

The first draft sequence was completed in October 2000 and later published in February 2001, with both the consortium and Celera publishing their results. This draft provided a rough map of the human genome, identifying most of the genetic material but leaving some gaps and areas that required further refinement.

The private company Celera Genomics announced the completion of the first draft of the human genome. This milestone marked significant progress in understanding human genetics.

The first draft sequence was completed in October 2000 and later published in February 2001, with both the consortium and Celera publishing their results

## The Human Genome Project (HGP)

Providing a complete, high-quality sequence of human genomic DNA to the research community as a freely, publicly available resource.

### Goals

- **Human DNA sequence variation**

  - **Finding and mapping common and less common variants**: Identify genetic differences, both frequent and rare, across the population. These variations can help explain why some individuals are more prone to certain diseases or traits.
  - **Making the information available**: Share these findings in public databases so researchers worldwide can access and utilize them.
  - **Develop algorithms for using such information**: Create tools to efficiently analyze genetic variations, linking them to health outcomes or disease risks.

- **Comparative genomics**

  - **Interpreting the human genome sequence**: Compare the human genome to those of other species to better understand how certain parts of our DNA contribute to biological functions.
    - **Functions of conserved sequences**: Identify DNA sequences that are similar across species, which likely serve important roles (e.g., regulating genes or coding for essential proteins).
    - **Support experiments in model systems**

- **Functional analysis of genes**

  - **Proteins**: Study how genes encode proteins, which carry out most cellular tasks.
  - **Coding regions**: Investigate sections of DNA that directly instruct cells to build proteins.
  - **Other functional elements of the genome**: Explore non-coding regions that play roles in regulating genes or maintaining chromosome structure.
  - **High-throughput, genome-wide basis**: Use technologies that analyze thousands of genes or proteins at once to collect data on gene activity and interactions.

- **Genome informatics**
  - **Data analysis methods**:
    - **Sequence analysis**: Examine the order of DNA bases (A, T, C, G) to identify genes and their functions.
    - **Gene mapping**: Locate specific genes on chromosomes.
    - **Complex trait mapping**: Study how multiple genes contribute to traits like height or disease susceptibility.
    - **Genetic variation**: Analyze differences in DNA that may impact health.
    - **Functional analysis**: Determine what different parts of the genome do.
  - **Development of database tools**: Build software that allows scientists to store, access, and analyze genetic data.
  - **Development and maintenance of databases**: Maintain large collections of genomic data for public use.

> 💡 _Difference between terms DNA, Genes and Genome_
>
> - **DNA**: The molecule that contains genetic instructions for the development and function of living organisms.
> - **Genes**: Specific segments of DNA that contain instructions to make proteins, which perform most functions in a cell.
> - **Genome**: The complete set of DNA in an organism, including all of its genes and non-coding regions.

After the publishing of the complete sequence of the human genome in 2001 start the "post-genomic era":

- The complete human **DNA sequence** is **known**
- Much must still to be yet understood:
  - What are **all the genes** in the DNA and where do they start and end?
  - What are **all** the DNA components?
  - How do they **interact** with each other in a **"systemic way"**?
  - What is their **function**; how is it **altered in pathologies**; how to **correct** such **alterations**?

**What's Molecular medicine?**

- **Molecular medicine** is a broad field, where **physical**, **chemical**, **biological**, and **medical** techniques are used to describe **molecular structures** and **mechanisms**, identify fundamental **molecular** and **genetic errors of disease**, and to develop **molecular interventions** to correct them.
- The molecular medicine perspective emphasizes **cellular** and **molecular phenomena** and **interventions** rather than the previous conceptual and observational focus on patients and their organs.

- Therefore, molecular medicine is interconnected with and develops into **pharmacogenomics**, which in turn has molecular medicine as its application focus.

**What is Pharmacogenomics?**

- **Pharmacogenomics** is the branch of **pharmacology** that deals with the **influence of genetic variation on drug response** in patients by correlating **gene expression** or **single-nucleotide polymorphisms** with a drug's **efficacy** or **toxicity**. By doing so, pharmacogenomics aims to develop rational means to **optimize drug therapy**, with respect to the patients' **genotype**, to ensure **maximum efficacy** with **minimal adverse effects** and **economical burden**.

- Such approaches promise the advent of "**personalized medicine**", in which **drugs** and **drug combinations** are **optimized** for each **individual's unique genetic makeup**.

- **Pharmacogenomics** is the whole **genome application** of **pharmacogenetics**, which examines **single gene interactions**.