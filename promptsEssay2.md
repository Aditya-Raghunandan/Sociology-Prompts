# LLM Usage Log — Assignment 2 (ELEN4019)

**Student:** Aditya Raghunandan (2434427)  
**Topic:** 3 — The Black Box of Machine Learning  
**Model used:** Claude (Anthropic), via Claude.ai Project  
**Purpose:** Research assistance, expanding pre-written notes into academic prose, LaTeX formatting, citation sourcing, and revision based on prior marking feedback.

---

## Phase 1: Planning and Pre-LLM Preparation

### Prompt 1: Topic Selection and Lecture Requirements
> Here is the next assignment. I want to do the ML black box one. Here are some lectures I haven't done — do I need to do any before starting?

Claude identified that the democracy and ideology lectures were irrelevant to Topic 3 and directed me to read the Mohamed et al. (2020) "Decolonial AI" paper as the essential starting material, since it defines the three harms (algorithmic oppression, exploitation, dispossession) used in the essay.

### Prompt 2: Pre-LLM Template Request
> Can you give me the Overleaf draft for the pre-LLM, like the last one?

Claude refused to write the pre-LLM content, explaining that the assignment requires this to be entirely my own work. Instead, it provided a bare LaTeX skeleton with section headings and word budgets only, leaving argument development to me.

### Prompt 3: Black Box Definition — Checking My Understanding
> ML models can be classified into different algorithms, some of them are called neural nets modelled after the brain. Similarly to a brain, the exact path to decisions and thoughts cannot be fully understood. This is what I have for "What is the black box in ML." Does the paper say anything about this, or could you back up my reasoning?

Claude corrected my brain analogy — the opacity isn't because neural nets are modelled after the brain, but because of the mathematical structure (millions of non-linearly interacting parameters). It pointed me to Burrell (2016) for three forms of opacity and Rudin (2019) for the formal definition.

---

## Phase 2: Research and Source Gathering

### Prompt 4: Research on Key Case Studies
> Can you find sources and data for the case studies I want to use — COMPAS, facial recognition bias, ghost work, Cambridge Analytica, and AI in developing countries?

Claude searched for and compiled academic sources covering each case study, including Angwin et al. (2016) on COMPAS, Buolamwini and Gebru (2018) on facial recognition, Gray and Suri (2019) on ghost work, and Perrigo (2023) on OpenAI's Kenyan workers. It also identified Barocas and Selbst (2016) on proxy discrimination and Couldry and Mejias (2019) on data colonialism.

### Prompt 5: Finding the Wylie Whistleblower Details
> My Cambridge Analytica paragraph mentions a whistleblower but I don't explain who. Can you find the details?

Claude found that Christopher Wylie disclosed internal documents to The Guardian and The New York Times in 2018, and sourced the Wylie (2019) book reference.

### Prompt 6: Verifying the Africa Data Centre Statistic
> I have a claim that Africa has less than 1% of global data centre capacity but I don't have evidence for it. Can you find a source?

Claude found the Africa Data Centres Association 2026 Economic Report confirming the statistic (less than 1% of capacity despite ~18% of world population).

### Prompt 7: Lobbying Data Sourcing
> I need a citation for the AI lobbying statistics — 648 companies, OpenAI's spending increase.

Claude found the OpenSecrets (2024) data showing 648 companies lobbied on AI in 2024 and OpenAI increased spending from $260,000 to $1.76 million.

---

## Phase 3: Drafting the Post-LLM Essay

### Prompt 8: Full Draft Request
> Using the research, can you make an Overleaf draft I can copy and paste for the essay right now?

Claude produced a full LaTeX draft structured around the four sections (Black Box definition, Oppression, Exploitation, Dispossession), incorporating the case studies and sources gathered in Phase 2.

### Prompt 9: Feedback Cross-Check
> Here is all the feedback I received from my previous essays (A1 and supplementary). Do I satisfy all of it? If not, tell me what's missing.

I provided compiled feedback from three rounds of marking (Sasha Rai on A1, Sasha's email feedback on the supplementary draft, and Martin Bekker's final supplementary marks). Claude systematically checked the essay against every feedback point and identified:
- Em-dashes needed replacing with semicolons/colons/brackets
- The introduction needed a conclusion-previewing sentence (per Martin's suggestion)
- Potential AI stock phrases to watch for
- The Amazon Mechanical Turk explanation was tangential
- The lobbying paragraph needed simplification
- Missing citations for the data centre and lobbying claims

### Prompt 10: Applying All Fixes
> Here is my current LaTeX. Make the fixes and give me a copy-paste version.

Claude produced a revised `.tex` file with all identified issues addressed: em-dashes replaced, intro preview sentence added, Wylie whistleblower paragraph expanded with citation, lobbying paragraph simplified with a plain-English definition, data centre claim cited, and the AMT tangent trimmed.

---

## Phase 4: Revision and Word Count

### Prompt 11: Word Count Reduction (Round 1)
> I need to remove 128 words.

Claude suggested targeted trims — tightening wordy sentences in Sections 1, 2, 3, and 4 and cutting one redundant colonial-pattern sentence. I accepted some suggestions and rejected others (the expanded section openings were added based on TA feedback, so I kept them).

### Prompt 12: Word Count Reduction (Round 2)
> I'm now at 2586 words. Find something else to cut — I'm not cutting the stuff you suggested because I added those due to feedback from TAs.

Claude identified alternative trims: tightening the oppression and exploitation opening paragraphs without removing content, compressing the XAI paragraph, cutting a redundant sentence, and tightening the introduction. Total savings: ~90 words with no arguments or examples removed.

### Prompt 13: Final 20-Word Trim
> Just 20 more words and we're done.

Claude found four micro-trims across four paragraphs: "predict the likelihood of reoffending" → "predict reoffending," compressing the ghost work list, merging two sentences in the lobbying paragraph, and tightening the OpenAI worker description. Total: ~21 words.

### Prompt 14: Reference Style Check
> Sasha told me something about my referencing style — do you remember what?

Claude recalled Sasha's feedback about inconsistent URL fonts in the bibliography and the rule to use `\parencite{}` everywhere with `\textcite{}` only when the author is the grammatical subject of the sentence. It recommended checking the `.bib` file for mixed URL field usage.

---

## Summary

The pre-LLM draft was written entirely by me based on my reading of Mohamed et al. (2020) and my understanding of black box models from my ML coursework. Claude was used to:

1. **Research:** Finding and verifying academic sources and case study data
2. **Drafting:** Expanding my notes and arguments into formal academic prose
3. **Quality control:** Cross-checking the essay against three rounds of prior marking feedback
4. **Formatting:** LaTeX structure, `biblatex` configuration, and Harvard referencing
5. **Revision:** Targeted word count reductions and citation consistency fixes

All arguments, case study selections, and analytical positions originated from my pre-LLM notes and our iterative discussion.

---
---

# Example Prompts for Topic 3: The Black Box of Machine Learning

**Note:** These are example prompts that students working on the same topic might find useful for learning purposes. They were not used in the production of my essay.

---

## Understanding the Core Concepts

> **What exactly makes a neural network a "black box"? Explain it in simple terms, then give me the technical version I'd need for an academic essay.**

> **What is the difference between a black box model and an interpretable model? Can you give me a side-by-side comparison using a decision tree vs. a deep neural network?**

> **Explain Burrell's (2016) three forms of opacity. Which one is most relevant to the harms discussed by Mohamed et al.?**

> **What is Explainable AI (XAI)? Do methods like LIME and SHAP actually solve the black box problem, or do they just create an illusion of transparency?**

## Engaging with Mohamed et al. (2020)

> **I've read the Mohamed et al. "Decolonial AI" paper. Can you help me distinguish between algorithmic oppression, exploitation, and dispossession? They feel overlapping.**

> **Mohamed et al. use the term "algorithmic exploitation." How is this different from normal labour exploitation? What role does the black box specifically play in making it worse?**

> **The paper talks about "ethics dumping." Can you explain what this means and give me an example I could use in an essay?**

> **How does Mohamed et al.'s concept of "algorithmic dispossession" connect to Couldry and Mejias's idea of "data colonialism"?**

## Finding and Using Case Studies

> **I want to use the COMPAS recidivism algorithm as a case study for algorithmic oppression. What are the key findings from the ProPublica investigation, and how does opacity specifically enable the discrimination?**

> **Can you find academic sources on the Gender Shades study by Buolamwini and Gebru? I want to use it as a second example of algorithmic oppression alongside COMPAS.**

> **What happened with IBM's Watson for Oncology? Why is it a good example of black box failure in a high-stakes setting?**

> **I want to write about ghost work and data labelling for the exploitation section. Who are the key authors, and what are the most striking statistics?**

> **Can you explain the Cambridge Analytica scandal in the context of "ethics dumping"? How were Kenya and Nigeria used as testing grounds?**

## Building Arguments

> **Barocas and Selbst (2016) argue that removing race from training data doesn't eliminate discrimination. Can you explain the concept of proxy variables and why opacity makes proxy discrimination harder to detect?**

> **One might argue that companies need trade secrets to protect their IP, so algorithmic opacity is justified. How would I construct a counterargument to this using the frameworks in my essay?**

> **How would I argue that transparency is necessary but not sufficient for accountability? I don't want my conclusion to be naively pro-transparency.**

> **Africa has less than 1% of global data centre capacity. How can I connect this infrastructure statistic to Mohamed et al.'s concept of algorithmic dispossession without it feeling like a tangent?**

## Structuring and Refining

> **My essay currently reads like a literature review — I'm summarising sources but not making my own arguments. How do I add analytical voice without sounding opinionated?**

> **I've been told my introduction is too long and contains arguments that belong in the body. Can you help me write a tight 150-word intro that previews my conclusion without arguing for it?**

> **My marker said to avoid two-sentence paragraphs and em-dashes. Can you scan my draft and flag any instances?**

> **I'm 200 words over the limit. Suggest specific cuts that lose no substance — don't cut any of my examples or case studies.**

## Referencing and Formatting

> **Can you help me set up a biblatex Harvard referencing system in Overleaf? I need authoryear style with Biber as the backend.**

> **When should I use `\parencite{}` vs `\textcite{}`? Give me examples of each in the context of my essay.**

> **My bibliography URL fonts are inconsistent. What's causing this and how do I fix it in LaTeX?**

> **How many sources do I need for a 2500-word ethics essay? The brief says 5 peer-reviewed minimum and ~10 total. Am I using enough?**
