# Advanced Methods in Deep Learning

Course materials for **Advanced Methods in Deep Learning** (*Métodos Avanzados en Deep Learning*), an elective course in the **Master in Applied Economics (MECA)** program at **Universidad del Pacífico (UP)**, taught by **Prof. Alexander Quispe Rojas**.

This repository hosts the slides, syllabus, lab notebooks, and reference materials used throughout the 2026-I term.

---

## Course Overview

The course offers a rigorous and applied introduction to deep learning, designed specifically for students and professionals in applied economics. It covers the theoretical foundations of neural networks — from the perceptron and backpropagation to modern architectures such as CNNs, RNNs, attention mechanisms, and Transformers — with an emphasis on practical implementation in Python using **PyTorch**. The course concludes with **Large Language Models (LLMs)** and **foundation models**, exploring their applications to economic analysis, research, and public policy.

### Course Information

| | |
|---|---|
| **Program** | Master in Applied Economics (MECA) — Universidad del Pacífico |
| **Cycle** | MECA 2 — Cycle 4 — Elective 3 |
| **Term** | 2026-I |
| **Credits** | 1.5 |
| **Workload** | 24 hours — 10 virtual sessions |
| **Modality** | Fully virtual (synchronous) |
| **Prerequisite** | Data Science with Python (or equivalent) |
| **Syllabus** | [Silabo_Deep_Learning_MECA_2026_I.pdf](Silabo_Deep_Learning_MECA_2026_I.pdf) |

### Learning Outcomes

By the end of the course, students will be able to:

- Understand the mathematical foundations of neural networks: activation functions, loss functions, backpropagation, and stochastic gradient descent.
- Implement feedforward neural networks, CNNs, and RNNs in PyTorch for classification and regression tasks.
- Explain attention mechanisms, self-attention, and the Transformer architecture.
- Use LLMs and pretrained models for text and economic data analysis.
- Apply transfer learning and fine-tuning to applied economics problems.
- Critically evaluate the possibilities, limitations, and ethical considerations of deep learning in economic research and public policy.

---

## Schedule

| # | Topic | Date | Deliverable |
|---|-------|------|-------------|
| 1 | Introduction to Deep Learning and Perceptrons | Mon, Apr 13 — 7:30–10:00 PM | |
| 2 | Non-linearities, Loss Functions, Backpropagation, Gradient Descent | Fri, Apr 17 — 7:30–10:00 PM | |
| 3 | Training: SGD, Regularization, Generalization | Mon, Apr 20 — 7:30–10:00 PM | **Lab 1** due Sun, Apr 27 |
| 4 | Convolutional Neural Networks (CNNs) | Sat, Apr 25 — 8:30–11:00 AM | |
| 5 | Word Embeddings (Word2Vec) and Recurrent Neural Networks | Mon, Apr 27 — 7:30–10:00 PM | **Lab 2** due Sun, May 4 |
| 6 | Attention and Self-Attention Mechanisms | Sat, May 2 — 8:30–11:00 AM | |
| 7 | Transformers | Sat, May 9 — 8:30–11:00 PM | **Lab 3** due Sun, May 11 |
| 8 | Large Language Models (LLMs) and Applications in Economics | Sat, May 16 — 8:30–11:00 AM | |
| 9 | Foundation Models: CLIP, DINO, Transfer Learning | Mon, May 18 — 7:30–9:30 PM | **Lab 4** due Mon, May 18 |
| 10 | **Final Oral Exam** (10 min, 2 questions per student) | Fri, May 22 — 7:30–9:30 PM | **Final Exam** |

---

## Lectures

Slides for each session are kept in their corresponding folder as compiled LaTeX/Beamer PDFs.

| Lecture | Topic | Slides |
|---------|-------|--------|
| 1 | Introduction to Deep Learning and Perceptrons | [lecture_1/](lecture_1/lecture_1_slides.pdf) |
| 2 | Non-linearities, Loss Functions, Backpropagation | [lecture_2/](lecture_2/lecture_2_slides.pdf) |
| 3 | Training: SGD, Regularization, Generalization | [lecture_3/](lecture_3/lecture_3_slides.pdf) |

> Additional lecture folders will be added as the term progresses.

---

## Labs and Scripts

> [!IMPORTANT]
> **Course deliverables live here.** Each lab includes a problem statement and a starter / reference script. Submissions must include the dataset used and the corresponding script (`.py` or `.ipynb`). See the [Schedule](#schedule) for due dates and the [Evaluation](#evaluation) section for the late policy.

| # | Video | Lab | Script |
|---|-------|-----|--------|
| 1 | Video 1 | [Lab 1](https://drive.google.com/file/d/1ITzCJcMFLgdyyliXE7TiosXiW7w9o_WY/view?usp=sharing) | [Script 1](https://drive.google.com/file/d/1UyWKRxD4ydZXFG1E19DQ8-k-OLdGzAaZ/view?usp=sharing) |
| 2 | Video 2 | [Lab 2](https://drive.google.com/file/d/1lYNrY9m5x4QFSd_Yg7G0bXWMJPLtoMZd/view?usp=sharing) | [Script 2](https://drive.google.com/file/d/1TkbJv87N_-ND0Ek19dfc_5ZNQl_cejYJ/view?usp=sharing) |
| 3 | Video 3 | *Coming soon* | *Coming soon* |
| 4 | Video 4 | *Coming soon* | *Coming soon* |

---

## Evaluation

| Component | Weight |
|-----------|-------:|
| Attendance / Participation | 10% |
| Lab 1 — Feedforward Neural Networks | 15% |
| Lab 2 — CNNs and RNNs | 15% |
| Lab 3 — Transformers and NLP | 15% |
| Lab 4 — LLMs and Foundation Models | 15% |
| Final oral exam | 30% |

**Late policy:** 2 points (out of 20) deducted per day late. After 3 days, the lab is not accepted (grade = 0).

**Final oral exam:** Individual, 10 minutes via Zoom. Two questions covering any topic from the course (conceptual, short mathematical exercise, or code interpretation). No LLMs, notes, or supporting materials are allowed during the exam.

**LLM policy:** Students are encouraged to use LLMs (ChatGPT, Claude, Gemini, etc.) — including [Claude Code](https://claude.com/claude-code) — as productivity tools while developing labs. However, they must understand the code they submit and be able to explain it.

---

## Tools and Setup

- **Language:** Python 3
- **Framework:** [PyTorch](https://pytorch.org/docs/stable/index.html)
- **Environment:** [Google Colab](https://colab.research.google.com/) (free GPU access). Colab Pro / Pro+ recommended for Labs 3 and 4.
- **AI Assistant (optional):** Claude Code

---

## Repository Structure

```
deep-learning-up/
├── lecture_1/                              # Lecture 1 slides (LaTeX/Beamer)
├── lecture_2/                              # Lecture 2 slides
├── lecture_3/                              # Lecture 3 slides
├── input/                                  # Reference materials
│   ├── cs_148/lecture_notes/               # Caltech CS148 lecture notes
│   ├── cs_155/lecture_notes/               # Caltech CS155 lecture notes
│   ├── cs_155/hw_solutions/                # CS155 problem set solutions
│   ├── Syllabus_DS_Python_UP_2025_I.pdf    # Prerequisite course syllabus
│   └── schedule.pdf                        # Course schedule
├── Silabo_Deep_Learning_MECA_2026_I.pdf    # Official syllabus
├── Silabo_Deep_Learning_MECA_2026_I.tex    # Syllabus source
├── LICENSE
└── README.md
```

---

## Bibliography

### Main Texts

- Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press. https://www.deeplearningbook.org/
- Zhang, A., Lipton, Z. C., Li, M., & Smola, A. J. (2023). *Dive into Deep Learning*. Cambridge University Press. https://d2l.ai/

### Complementary Texts

- Jurafsky, D., & Martin, J. H. (2024). *Speech and Language Processing* (3rd ed. draft). https://web.stanford.edu/~jurafsky/slp3/
- Vaswani et al. (2017). *Attention Is All You Need*. NeurIPS 30.
- Devlin et al. (2019). *BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding*. NAACL-HLT.
- Radford et al. (2021). *Learning Transferable Visual Models From Natural Language Supervision* (CLIP). ICML.

### Deep Learning in Economics

- Athey, S., & Imbens, G. W. (2019). *Machine Learning Methods That Economists Should Know About*. Annual Review of Economics, 11, 685–725.
- Gentzkow, M., Kelly, B., & Taddy, M. (2019). *Text as Data*. Journal of Economic Literature, 57(3), 535–574.
- Jean, N. et al. (2016). *Combining Satellite Imagery and Machine Learning to Predict Poverty*. Science, 353(6301), 790–794.
- Hansen, S., & McMahon, M. (2016). *Shocking Language: Understanding the Macroeconomic Effects of Central Bank Communication*. Journal of International Economics, 99, S114–S133.
- Dell, M., & Olken, B. A. (2020). *The Development Effects of the Extractive Colonial Economy*. The Review of Economic Studies, 87(1), 164–203.

---

## Instructor

**Prof. Alexander Quispe Rojas** — Universidad del Pacífico

- Email: [aw.quispero@up.edu.pe](mailto:aw.quispero@up.edu.pe) · [aquisper@caltech.edu](mailto:aquisper@caltech.edu)
- Office hours: [Schedule via Calendly](https://calendly.com/alexander-quispe)

---

## License

See [LICENSE](LICENSE). Course materials are intended for educational use within the MECA program at Universidad del Pacífico.
