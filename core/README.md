# Core Chapter Templates

This folder contains templates and guidelines for **core thesis chapters** that are designed to mirror a typical conference-style paper in empirical CS/SE. Each core chapter is intended to be a self-contained unit that:

- Presents a specific study, experiment, or analysis.  
- Follows a standard paper-like structure.  
- Can later be adapted into a conference or journal paper with minimal restructuring.

## Chapter overview

A core chapter should read like a well-structured empirical paper:

- It starts by introducing the problem and framing the contribution.  
- It situates the work in its technical and conceptual background and related literature.  
- It explains the methodology clearly enough to be reproducible.  
- It presents results in a disciplined way.  
- It interprets those results in a discussion.  
- It ends with a concise summary that closes the chapter and prepares the reader for the next one.

This alignment with a paper-style format is deliberate: the goal is that **one chapter ≈ one publishable study**, so the candidate can focus on writing the thesis while keeping the path to publication straightforward.

## Sections and files

Each core chapter is organized into the following sections:

1. [Introduction](core/introduction.md)  
   - Purpose: Motivate the specific chapter’s problem, scope, and contribution; state the chapter’s objectives or research questions.  
   - Status: **TODO** – guidelines and templates still need to be extracted.

2. [Background](core/background.md)  
   - Purpose: Provide the technical and conceptual background needed to understand the chapter’s methods and results.  
   - Status: **TODO** – guidelines and templates still need to be extracted.

3. [Related Work](core/related_work.md)  
   - Purpose: Position the chapter’s contribution relative to prior work, highlighting what is extended, refined, or challenged.  
   - Status: **TODO** – guidelines and templates still need to be extracted.

4. [Methodology](core/methodology.md)  
   - Purpose: Describe the study design, data, procedures, tools, and analysis methods in enough detail for replication or critical evaluation.  
   - Status: **TODO** – guidelines and templates still need to be extracted.

5. [Results](core/results.md)  
   - Purpose: Present the empirical findings in a clear, structured way, separating raw outcomes from interpretation.  
   - Notes: This section already has a Markdown file with guidelines/templates for presenting results.

6. [Discussion](core/discussion/README.md)  
   - Purpose: Interpret the results, connect them back to the research questions and broader context, and highlight implications.  
   - Notes: The Discussion section has dedicated files for each subsection (e.g., implications, limitations, future work).  
     - See the detailed structure and guidelines in [`discussion/README.md`](discussion/README.md).

7. [Summary](core/summary.md)  
   - Purpose: Provide a concise recap of what the chapter did and found, and how it connects to the rest of the thesis.  
   - Notes: This section already has a Markdown file with guidelines/templates for summarizing the chapter.

> **TODO:**  
> - Populate `introduction.md`, `background.md`, `related_work.md`, and `methodology.md` with section-level guidelines and minimal templates.  
> - Ensure each `.md` file includes: a short purpose statement, a checklist of required elements, and LaTeX skeletons.

## How to use these templates

Suggested workflow for each core chapter:

1. Start from this conference-style structure and create the chapter with all seven sections.  
2. Use the existing `results.md`, `discussion/README.md`, and `summary.md` as concrete guides for those parts of the chapter.  
3. When a chapter is mature, create a **paper version** by:
   - Tightening the Introduction and Related Work to match venue length constraints.  
   - Keeping Methodology, Results, Discussion, and Summary aligned with the chapter templates.  
