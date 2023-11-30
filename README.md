# MSBD5018-SemEval2021-Task4
## Task
[SemEval-2021 Task 4: Reading Comprehension of Abstract Meaning](https://competitions.codalab.org/competitions/26153)

## Methodology
- Baseline
    - GA Reader
- Text to Text Generation
    - T5
- Masked Language Modeling
    - BERT
    - ALBERT
- Replaced Token Detection
    - ELECTRA

The dataset and baseline can be found here [SemEval2021-Reading-Comprehension-of-Abstract-Meaning](https://github.com/boyuanzheng010/SemEval2021-Reading-Comprehension-of-Abstract-Meaning/tree/master)

## Result

| Model | Task 1 | Task 2 | Task3 (Train 1, Test 2) | Task3 (Train 2, Test 1) |
| --- | --- | --- | --- | --- |
| GA Reader | 0.294 | 0.170 | 0.202 | 0.202 |
| T5 Fine Tune Attempt 1 | 0.247 | 0.149 | 0.197 | 0.221 |
| T5 Fine Tune Attempt 2 | 0.597 | 0.543 | 0.536 | 0.498 |
| BERT Base Uncased | 0.764 | 0.828 | - | - |
| BERT Base Uncased Fine Tuned | 0.773 | 0.801 | 0.811 | 0.745 |
| BERT Large Uncased | 0.788 | 0.859 | - | - |
| ALBERT XLarge V2 | 0.804 | 0.828 | - | - |
| ALBERT XLarge V2 Fine Tuned | 0.738 | 0.778 | 0.743 | 0.764 |
| ALBERT XXLarge V2 | 0.875 | 0.913 | - | - |
| ELECTRA Base | 0.822 | 0.882 | - | - |
| ELECTRA Base with Wordnet | 0.775 | 0.857 | - | - |
| ELECTRA Large | 0.898 | 0.923 | - | - |
| ELECTRA Large with Wordnet | 0.850 | 0.895 | - | - |
| ELECTRA Large Fine Tuned | 0.896 | 0.928 | 0.926 | 0.896 |