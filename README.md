# Auto Mark Questions

## Problem Description
Short-answered questions require students to freely answer their thoughts as opposed to multiple choice questions. This type of assessment may be considered as an accurate assessment because it reveals a real student’s understanding. Nevertheless, grading short-answered questions is extremely challenging because manual experts grading process becomes extraordinarily expensive to scale up. To resolve this scalability challenge, we expect you to build an automated grading system.

For this purpose, you are provided an annotated dataset consists of 900 students’ short constructed answers and their correctness in the given context. Four qualitative levels of correctness are defined, correct, correct-but-incomplete, contradictory and Incorrect.

## Running Local Quickstart

**Make sure that you have [`poetry`](https://python-poetry.org/) installed for `python-3.7+`**

**For better performance you need to run this notebook using a GPU**

Download the model weights in the project directory from [here](https://drive.google.com/file/d/10QSCPEB8kILiHK0f-3rWxOjXoiU3i1AX/view?usp=sharing)

Install the project requirements
```bash
poetry install
```

Enter the created virtual environment
```bash
poetry shell
```


Then you need to run the jupyter server

```bash
jupyter notebook
```