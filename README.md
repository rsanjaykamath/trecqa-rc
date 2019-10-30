# trecqa-rc
Trec QA 13 dataset with answer spans from the paragraphs

The original trec qa task has answer patterns which were used for automatic judgement of answers. 

The dataset released by the authors [What is the Jeopardy Model? A Quasi-Synchronous Grammar for QA](https://www.aclweb.org/anthology/D07-1003/) contains only relevant and non relevant labels for answer sentences. 

In this repository using the pattern files provided by trec, we also release the answer spans. 

Each line has a question and each question is repeated in this line as many times as the number of paragraphs it has which are either relevant or irrelevant.
