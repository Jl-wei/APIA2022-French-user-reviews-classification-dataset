# APIA2022-French-user-reviews-classification-dataset

*App review, user review, requirements engineering, text classification*

6000 French user reviews from three applications on Google Play (Garmin Connect, Huawei Health, Samsung Health) are labelled manually. We selected four labels: rating, bug report, feature request and user experience.

* **Ratings** are simple text which express the overall evaluation to that app, including praise, criticism, or dissuasion.
* **Bug reports** show the problems that users have met while using the app, like loss of data, crash of app, connection error, etc.
* **Feature requests** reflect the demande of users on new function, new content, new interface, etc.
* In **user experience**, users describe their experience in relation to the functionality of the app, how does certain functions be helpful.

As we can observe from the following table, that shows examples of labelled user reviews, each review belongs to one or more categories.


| App            | Total | Rating | Bug report | Feature request | User experience |
| -------------- | ----- | ------ | ---------- | --------------- | --------------- |
| Garmin Connect | 2000  | 1260   | 757        | 170             | 493             |
| Huawei Health  | 2000  | 1068   | 819        | 384             | 289             |
| Samsung Health | 2000  | 1324   | 491        | 486             | 349             |



If you find our dataset useful, please cite our paper:


```bibtex
@inproceedings{Wei2022,
author = {Wei, Jialiang and Courbis, Anne-Lise and Lambolais, Thomas and Xu, Binbin, and Bernard, Pierre Louis and Dray, Gérard},
booktitle = {7ème Conférence Nationale sur les Applications Pratiques de l’Intelligence Artificielle},
title = {{Towards a Data Driven Requirements Engineering Approach: Automatic Analysis of User Reviews}},
year = {2022}
}
```
