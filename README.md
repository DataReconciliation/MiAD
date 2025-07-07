# Dataset for MiAD

This dataset is a dataset of the MiAD dataset and was constructed utilizing the Ta-da-recipe dataset, which originates from the Data Science and Knowledge Engineering Laboratory of Zhengzhou University of Light Industry. This dataset is composed of two Chinese recipe websites, represented by tableA and tableB, respectively. The former consists of seven properties, namely id, name, mainFood, subFood, skill, taste, and difficulty, while the latter contains eight properties, namely id, name, mainFood, subFood, skill, taste, difficulty, and time. It is worth noting that no additional attributes were included in this experiment, as only those aforementioned are deemed applicable. If interested, you may access the entire Ta-da-recipe dataset at https://github.com/Eimo-Bai/Ta-da-recipe-dataset, which were constructed by our team members.

# Dataset Structure

```bash
dataset/
├── tableA.csv           # Source entity table A
├── tableB.csv           # Target entity table B
├── matches.csv          # Gold-standard matched entity pairs (idA, idB)
├── skill.json           # JSON metadata describing the "skill" attribute
├── taste.json           # JSON metadata describing the "taste" attribute
├── difficulty.json      # JSON metadata describing the "difficulty" attribute
```

# Addition & Description 添加和描述

To ensure the quality of the dataset, the team cleaned and pre-processed the initial data, and built the precipitated knowledge into a knowledge graph and applied it to the practical aspects. The details of the work will be discussed in detail in a forthcoming paper by the team members.

We present here a demo of the dataset.

Due to the unpublished paper and the confidentiality of the project, we have only published a part of the data as a formal presentation. We have not yet published the user review data in the dataset. The complete dataset and the construction method will be fully disclosed after the publication of the paper.

This team is from the Data Science and Knowledge Engineering Laboratory of Zhengzhou University of Light Industry.

![image](https://github.com/Eimo-Bai/Ta-da-recipe-dataset/raw/main/lab.png)

