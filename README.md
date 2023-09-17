# Data-Repo
Rumor and stance label test data repository for the SIGIR 2022 paper: A weakly supervised propagation model for rumor verification and stance detection with multiple instance learning

## Paper: https://dl.acm.org/doi/abs/10.1145/3477495.3531930

## Please use the following citation:
@inproceedings{yang2022weakly,
  title={A weakly supervised propagation model for rumor verification and stance detection with multiple instance learning},
  author={Yang, Ruichao and Ma, Jing and Lin, Hongzhan and Gao, Wei},
  booktitle={Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  pages={1761--1772},
  year={2022}
}

## Dataset
RumorEval2019-S test dataset in this paper contains 397 conversation threads, claim label comes from one of [True Rumor, False Rumor, Non Rumor, Unverified Rumor], post label comes from one of [Support, Deny, Question, Comment]. 

###Labal Folder: contains Claim label and post stance label files.
###Tweets Folder: each file is named with claim id, that contains Claim id, claim texts, and corresponding reply id, reply text.

###As for another test dataset SemEval8, you can get it directly through: 

