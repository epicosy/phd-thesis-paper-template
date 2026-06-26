# Introduction Chapter Templates

This folder contains templates and guidelines for structuring the **Introduction** chapter of a PhD thesis built around conference-style core chapters in empirical CS/SE. The Introduction is thesis-specific: it orients the reader, frames the problem and trajectory, and connects the later core chapters and publications into a coherent whole.

> **Status:** Section-level templates/guidelines are planned but not yet extracted from the source thesis.  
> TODO: Add detailed templates for each section and subsection based on the final thesis version.

## Chapter overview

The Introduction chapter has two main roles:

- Provide a **conceptual and technical frame** for the thesis topic (problem, background, trajectory).  
- Explain **how the thesis addresses the gap**, what the objectives and research questions are, and how the approach and contributions are organized across chapters.

A typical overview paragraph for this chapter should:

- Identify the **structural gap or problem** the thesis addresses (e.g., mismatch between how vulnerabilities are reported and how they must be reasoned about in code).  
- State the **scope and context** (e.g., fuzzing-derived security bugs in C/C++ OSS projects).  
- Outline the **main research questions** and briefly indicate how each is addressed by the thesis.

See `chapter_overview.md` for a generic template capturing these elements.

## Sections and files

The Introduction chapter is organized into the following sections. Each section will have its own Markdown file with guidelines and (optionally) LaTeX templates.

1. [Problem Context and Motivation](problem_context_and_motivation.md)  
2. [Technical and Conceptual Background](technical_and_conceptual_background.md)  
3. [Research Trajectory and Problem Refinement](research_trajectory_and_problem_refinement.md)  
4. [Thesis Objectives and Research Questions](thesis_objectives_and_research_questions.md)  
5. [Research Approach and Methodological Strategy](research_approach_and_methodological_strategy.md)  
6. [Summary of Contributions](summary_of_contributions.md)  
7. [Structure of the Thesis](structure_of_the_thesis.md)  
8. [Relationship to Prior Publications](relationship_to_prior_publications.md)  

> **TODO:** Populate each of the above `.md` files with:
> - A brief purpose statement for the section.  
> - A minimal checklist of elements that must appear.  
> - LaTeX skeletons (e.g., subsection layout).

The goal is for the Introduction to make the thesis **legible and navigable**, and to make it easy to see how later chapters and associated papers answer the stated research questions.
