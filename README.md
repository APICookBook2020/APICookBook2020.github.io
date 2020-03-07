# Replication Package of Identification and Applications of API-related Developer Needs in Stack Overflow

## Empirical Study

- [developer need and relevant information analysis of 266 posts](https://github.com/APICookBook2020/APICookBook2020.github.io/tree/master/empirical_study/developer%20need%20and%20relevant%20information%20classification/classification_for_500_posts).
We derived a fine-grained taxonomy through an empirical study of 266 API related SO posts from top 500 voted SO posts. Then discussed and summarized 8 developer need types and 17 relevant information types. This folder contains specific analysis of the above types. In the "processed_sentence_classified_data.json", key "id" represent the represents post ID in Stack Overflow, "label for title" contains several lists in which first items are start positions of title text, second items are ends position of title text and the third positions are the labels, "label for body" is similar to "label for title", "title" and "body" are the Stack Overflow question title and body. In "labels.json" are the corresponding label information of the previous json file.

- [developer need and relevant information analysis of 34 posts](https://github.com/APICookBook2020/APICookBook2020.github.io/tree/master/empirical_study/developer%20need%20and%20relevant%20information%20classification/classification_for_34_posts). 
This folder contains the results of two annotators which contain questions from the 266 questions which contain five questions for each developer need type. In the csv files, the column "post_id" represents post ID in Stack Overflow, "text" represents the current sentence of corresponding post, the other columns are developer need types and relevant information types. 

- [developer need instances classification](https://github.com/APICookBook2020/APICookBook2020.github.io/tree/master/empirical_study/developer%20need%20instances%20classification). 
This file contains the group result of developer need sentences. In the json file, key "post_id" represents post ID in Stack Overflow, "scenario" represents the developer need types, "annotation_1" represents the sentences group result of the first annotator, "annotation_2" represents the sentences group result of the second annotator, "kappa" represent the kappa value.

## API Identification
- [code for API identification](https://github.com/APICookBook2020/APICookBook2020.github.io/tree/master/api_recognition_code). 
This folder contains codes for API identification. Folder "text_based" contains scripts for extracting API from text. Folder "text_based" contains scripts for extracting API from code snippets, stack traces. Folder "combined" combined all extracting ways. We hide some Python libraries which released by ourselves in these scripts for reasons of anonymity.

## Annotated Data Expansion
- [annotated data expansion](https://github.com/APICookBook2020/APICookBook2020.github.io/tree/master/annotated_data_expansion). This folder contains 17 files corresponding to 17 relevant information types. In each csv file, the column "url" represents Stack Overflow url for postd, "sentence" represents the current sentence for annotating, "title" and "body" are the Stack Overflow question title and body, "arbitration" represents the arbitration result.
 

It is hereby stated that due to anonymity, some information is hidden and will be disclosed in the future
