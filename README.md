# Introduction to Natural Language Processing and LLMs

**University of Konstanz, Winter Semester 2026/27**
Thursdays, 11:45–13:15, C424

**Instructor:** Miriam Schirmer (miriam.schirmer@uni-konstanz.de)

**Office hours:** by appointment; please email to arrange a time

**Course type:** BA VS / MA S, taught in English

---

## About the course

Natural language processing (NLP) and large language models (LLMs) are transforming how researchers analyze text at scale. This course gives students the methodological foundation to understand how automated text processing works, from lexicon-based approaches to transformer architectures and chatbots. While the course is methods-focused, we will also work hands-on with real-world data drawn from political communication and international contexts on the Web. We will be working with Python. No prior programming experience is required.

After an introductory session, the course is taught in four blocks of three sessions each:

- Text as Data (sessions 2 to 4)
- Learning from Text (sessions 5 to 7)
- Embeddings and Transformers (sessions 8 to 10)
- LLMs as Research Tools (sessions 11 to 13)

Each block consists of a theory session, a coding session in which we work with pre-built Python notebooks in Google Colab, and a paper session in which students present and discuss applied research. The course ends with a written exam in session 14.

### Learning objectives

By the end of the course, students will be able to:

- explain how NLP methods and LLMs work, from bag-of-words models to transformers;
- apply basic computational text analysis to political and social science data;
- critically evaluate research that uses these methods.

---

## Schedule

<table>
<tr><th>Session</th><th>Date</th><th>Type</th><th>Topic</th><th>Materials</th></tr>
<tr><td align="center">1</td><td>22 Oct</td><td><img src="https://img.shields.io/badge/Intro-lightgrey?style=flat-square" alt="Intro"></td><td><a href="#session-1-22-october-introduction">Course overview</a></td><td><a href="slides/01_Introduction.pdf">Slides</a></td></tr>
<tr><td></td><td colspan="4"><b>Block 1: Text as Data</b></td></tr>
<tr><td align="center">2</td><td>29 Oct</td><td><img src="https://img.shields.io/badge/Theory-4C72B0?style=flat-square" alt="Theory"></td><td><a href="#session-2-29-october-theory-text-as-data">Text as data</a></td><td></td></tr>
<tr><td align="center">3</td><td>05 Nov</td><td><img src="https://img.shields.io/badge/Coding-55A868?style=flat-square" alt="Coding"></td><td><a href="#session-3-5-november-coding">Preprocessing, bag-of-words and dictionaries</a></td><td></td></tr>
<tr><td align="center">4</td><td>12 Nov</td><td><img src="https://img.shields.io/badge/Papers-DD8452?style=flat-square" alt="Papers"></td><td><a href="#session-4-12-november-paper-presentations">Paper presentations</a></td><td></td></tr>
<tr><td></td><td colspan="4"><b>Block 2: Learning from Text</b></td></tr>
<tr><td align="center">5</td><td>19 Nov</td><td><img src="https://img.shields.io/badge/Theory-4C72B0?style=flat-square" alt="Theory"></td><td><a href="#session-5-19-november-theory-supervised-classification-and-topic-models">Supervised classification and topic models</a></td><td></td></tr>
<tr><td align="center">6</td><td>26 Nov</td><td><img src="https://img.shields.io/badge/Coding-55A868?style=flat-square" alt="Coding"></td><td><a href="#session-6-26-november-coding">Training and evaluating a text classifier</a></td><td></td></tr>
<tr><td align="center">7</td><td>03 Dec</td><td><img src="https://img.shields.io/badge/Papers-DD8452?style=flat-square" alt="Papers"></td><td><a href="#session-7-3-december-paper-presentations">Paper presentations</a></td><td></td></tr>
<tr><td></td><td colspan="4"><b>Block 3: Embeddings and Transformers</b></td></tr>
<tr><td align="center">8</td><td>10 Dec</td><td><img src="https://img.shields.io/badge/Theory-4C72B0?style=flat-square" alt="Theory"></td><td><a href="#session-8-10-december-theory-embeddings-and-transformers">Embeddings and transformers</a></td><td></td></tr>
<tr><td align="center">9</td><td>17 Dec</td><td><img src="https://img.shields.io/badge/Coding-55A868?style=flat-square" alt="Coding"></td><td><a href="#session-9-17-december-coding">Word embeddings and transformer models</a></td><td></td></tr>
<tr><td align="center"></td><td>24 and 31 Dec</td><td></td><td><i>Winter break, no sessions</i></td><td></td></tr>
<tr><td align="center">10</td><td>07 Jan</td><td><img src="https://img.shields.io/badge/Papers-DD8452?style=flat-square" alt="Papers"></td><td><a href="#session-10-7-january-paper-presentations">Paper presentations</a></td><td></td></tr>
<tr><td></td><td colspan="4"><b>Block 4: LLMs as Research Tools</b></td></tr>
<tr><td align="center">11</td><td>14 Jan</td><td><img src="https://img.shields.io/badge/Theory-4C72B0?style=flat-square" alt="Theory"></td><td><a href="#session-11-14-january-theory-prompting-and-llms-as-annotators">Prompting and LLMs as annotators</a></td><td></td></tr>
<tr><td align="center">12</td><td>21 Jan</td><td><img src="https://img.shields.io/badge/Coding-55A868?style=flat-square" alt="Coding"></td><td><a href="#session-12-21-january-coding">LLM versus classifier</a></td><td></td></tr>
<tr><td align="center">13</td><td>28 Jan</td><td><img src="https://img.shields.io/badge/Papers-DD8452?style=flat-square" alt="Papers"></td><td><a href="#session-13-28-january-paper-presentations">Paper presentations</a></td><td></td></tr>
<tr><td></td><td colspan="4"><b>Exam</b></td></tr>
<tr><td align="center">14</td><td>04 Feb</td><td><img src="https://img.shields.io/badge/Exam-C44E52?style=flat-square" alt="Exam"></td><td><a href="#session-14-4-february-written-exam">Written exam, in class</a></td><td></td></tr>
</table>

---

## Assessment

### 1. Paper presentation (30%)

In groups (group size depends on the final course size), you present one of the applied papers listed for the paper sessions. Papers and groups are assigned during the first sessions. Each presentation is followed by a class discussion. Grades are given per group.

The presentation should cover:

- the research question and its relevance;
- the data (what texts, from where, how many);
- the method, explained in your own words and linked to the theory session of the block;
- the main findings;
- the limitations (would you trust this measurement?);
- and two or three questions to start the discussion.

Presentation length and the deadline for submitting slides will be announced and depend on the course size.

### 2. Written exam (70%)

4 February 2027, in class. The exam is on the concepts we work through in all sessions.

---

## Weekly content and readings

Each theory session has two prep readings:

- a chapter from Jurafsky and Martin's textbook *Speech and Language Processing* (3rd edition draft, [freely available online](https://web.stanford.edu/~jurafsky/slp3/))
- and an introductory article written for social scientists.

Please read both before the theory session.

The papers for the paper sessions are applied studies from political science and computational social science. Presenters read their paper in depth; everyone else should at least skim the papers before the session. All readings are freely accessible.

### Session 1 (22 October). Introduction

This session introduces the course.

<details open>
<summary><b>Block 1: Text as Data</b> (sessions 2 to 4)</summary>

#### Session 2 (29 October). Theory: Text as data

*How can text be turned into numbers?*

**Topics:** Preprocessing (tokenization, stopwords, stemming), the bag-of-words model, TF-IDF weighting and dictionary methods.

**Read before class:**

1. **[pp. 1–24]** Jurafsky, D. & Martin, J.H. (2026). Words and Tokens. *Speech and Language Processing*. 3rd ed. draft, ch. 2. [PDF](https://web.stanford.edu/~jurafsky/slp3/2.pdf)
1. Benoit, K. (2020). Text as Data: An Overview. In Curini, L. & Franzese, R. (eds) *The SAGE Handbook of Research Methods in Political Science and International Relations*. London: SAGE, pp. 461–497. [Link](https://ink.library.smu.edu.sg/soss_research/4015)

#### Session 3 (5 November). Coding

**In class:** Hands-on notebook on preprocessing, bag-of-words and dictionaries.

#### Session 4 (12 November). Paper presentations

**Papers to present:**

1. Rauh, C. (2023). Clear messages to the European public? The language of European Commission press releases 1985–2020. *Journal of European Integration* 45 (4): 683–701. [Link](https://doi.org/10.1080/07036337.2022.2134860)
1. Gründl, J. (2022). Populist ideas on social media: A dictionary-based measurement of populist communication. *New Media & Society* 24 (6): 1481–1499. [Link](https://doi.org/10.1177/1461444820976970)
1. Kittel, R.C. (2025). Simply Speaking? Language Complexity among (Non-)Populist Actors in Parliamentary Debates. *Government and Opposition* 60 (4): 1336–1366. [Link](https://doi.org/10.1017/gov.2025.4)

</details>

<details open>
<summary><b>Block 2: Learning from Text</b> (sessions 5 to 7)</summary>

#### Session 5 (19 November). Theory: Supervised classification and topic models

*How can computers learn categories from examples?*

**Topics:** Supervised classification, the annotation of training data and evaluation with precision, recall and F1.

We then look briefly at topic models (LDA) as the unsupervised contrast.

**Read before class:**

1. Jurafsky, D. & Martin, J.H. (2026). Logistic Regression and Text Classification. *Speech and Language Processing*. 3rd ed. draft, ch. 4. [PDF](https://web.stanford.edu/~jurafsky/slp3/4.pdf)
- van Atteveldt, W., van der Velden, M.A.C.G. & Boukes, M. (2021). The Validity of Sentiment Analysis: Comparing Manual Annotation, Crowd-Coding, Dictionary Approaches, and Machine Learning Algorithms. *Communication Methods and Measures* 15 (2): 121–140. [Link](https://doi.org/10.1080/19312458.2020.1869198)

#### Session 6 (26 November). Coding

**In class:** Hands-on notebook on training and evaluating a text classifier.

#### Session 7 (3 December). Paper presentations

**Papers to present:**

1. Theocharis, Y., Barberá, P., Fazekas, Z. & Popa, S.A. (2020). The Dynamics of Political Incivility on Twitter. *SAGE Open* 10 (2). [Link](https://doi.org/10.1177/2158244020919447)
1. Peterson, A. & Spirling, A. (2018). Classification Accuracy as a Substantive Quantity of Interest: Measuring Polarization in Westminster Systems. *Political Analysis* 26 (1): 120–128. [Free version](https://archive-ouverte.unige.ch/unige:109228)
1. Barberá, P., Casas, A., Nagler, J., Egan, P.J. et al. (2019). Who Leads? Who Follows? Measuring Issue Attention and Agenda Setting by Legislators and the Mass Public Using Social Media Data. *American Political Science Review* 113 (4): 883–901. [Link](https://doi.org/10.1017/S0003055419000352)

</details>

<details open>
<summary><b>Block 3: Embeddings and Transformers</b> (sessions 8 to 10)</summary>

#### Session 8 (10 December). Theory: Embeddings and transformers

*How do models represent meaning?*

**Topics:** Word embeddings and the biases they encode, the intuition behind attention, and the step from BERT to GPT-style models.

**Read before class:**

1. Jurafsky, D. & Martin, J.H. (2026). Transformers and Pretraining. *Speech and Language Processing*. 3rd ed. draft, ch. 7. [PDF](https://web.stanford.edu/~jurafsky/slp3/7.pdf)
1. Ornstein, J.T., Blasingame, E.N. & Truscott, J.S. (2025). How to train your stochastic parrot: large language models for political texts. *Political Science Research and Methods* 13 (2): 264–281. [Link](https://doi.org/10.1017/psrm.2024.64)

#### Session 9 (17 December). Coding

**In class:** Hands-on notebook on word embeddings and transformer models.

*Winter break: no sessions on 24 and 31 December.*

#### Session 10 (7 January). Paper presentations

**Papers to present:**

1. Garg, N., Schiebinger, L., Jurafsky, D. & Zou, J. (2018). Word embeddings quantify 100 years of gender and ethnic stereotypes. *Proceedings of the National Academy of Sciences* 115 (16): E3635–E3644. [Free version](https://par.nsf.gov/servlets/purl/10089508)
1. Widmann, T. & Wich, M. (2023). Creating and Comparing Dictionary, Word Embedding, and Transformer-Based Models to Measure Discrete Emotions in German Political Text. *Political Analysis* 31 (4): 626–641. [Link](https://doi.org/10.1017/pan.2022.15)

</details>

<details open>
<summary><b>Block 4: LLMs as Research Tools</b> (sessions 11 to 13)</summary>

#### Session 11 (14 January). Theory: Prompting and LLMs as annotators

*How can researchers use LLMs, and what can go wrong?*

**Topics:** Prompting, zero-shot and few-shot learning, the use of LLMs as annotators, and questions of validity and reproducibility.

**Read before class:**

1. Jurafsky, D. & Martin, J.H. (2026). Post-training. *Speech and Language Processing*. 3rd ed. draft, ch. 8. [PDF](https://web.stanford.edu/~jurafsky/slp3/8.pdf)
1. Törnberg, P. (2024). Best Practices for Text Annotation with Large Language Models. *Sociologica* 18 (2): 67–85. [Link](https://sociologica.unibo.it/article/view/19461)

#### Session 12 (21 January). Coding

**In class:** Hands-on notebook in which an LLM and the classifier from Block 2 compete on the same task.

#### Session 13 (28 January). Paper presentations

**Papers to present:**

1. Gilardi, F., Alizadeh, M. & Kubli, M. (2023). ChatGPT outperforms crowd workers for text-annotation tasks. *Proceedings of the National Academy of Sciences* 120 (30): e2305016120. [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC10372638/)
1. Alizadeh, M., Kubli, M., Samei, Z., Dehghani, S. et al. (2025). Open-source LLMs for text annotation: a practical guide for model setting and fine-tuning. *Journal of Computational Social Science* 8: 17. [Link](https://doi.org/10.1007/s42001-024-00345-9)
1. Le Mens, G. & Gallego, A. (2025). Positioning Political Texts with Large Language Models by Asking and Averaging. *Political Analysis* 33 (3): 274–282. [Link](https://doi.org/10.1017/pan.2024.29)

</details>

### Session 14 (4 February). Written exam

In class, 11:45–13:15, C424.


## Materials

- **Slides** are linked in the schedule above after each session and stored in [`slides/`](./slides).
- **Notebooks** for the coding sessions are stored in [`notebooks/`](./notebooks). Each one has an *Open in Colab* link, so they run in your browser without installing anything.

<!--
How to add materials (this comment is not shown on GitHub):
1. Export the slides from PowerPoint as PDF (File > Export > PDF), name them like 02_Text_as_Data.pdf
   and upload them to slides/.
2. Upload notebooks to notebooks/, e.g. notebooks/03_Preprocessing.ipynb.
3. In the schedule table, put the links into the last <td></td> (Materials) of that session's row, for example:
   <a href="slides/02_Text_as_Data.pdf">Slides</a>
   <a href="notebooks/03_Preprocessing.ipynb">Notebook</a> <a href="https://colab.research.google.com/github/MiriamSchirmer/nlp-llms-ws2627/blob/main/notebooks/03_Preprocessing.ipynb">Open in Colab</a>
-->
