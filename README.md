# CS753 - ASR Hacker & Poster Role for STEMM: Self-learning with **S**peech-**T**ext **M**anifold **M**ixup for Speech Translation

## Team Pitch Perfect

This project (STEMM) is an implementation of the ACL 2022 main conference paper [STEMM: Self-learning with Speech-text Manifold Mixup for Speech Translation](https://arxiv.org/abs/2203.10426). 

The poster (MSN) has been added to the root folder. There is a python notebook that can be used to run this model. Since the dataset being used is very large, we will use a smaller dataset MaSS - Multilingual corpus of Sentence-aligned Spoken utterances (https://github.com/getalp/mass-dataset/tree/master), developed by the CMU team (https://arxiv.org/pdf/1907.12895.pdf). 

There is google colab notebook containing the code to run this project. Instead of the montreal forced aligner, we have used a muas aligner. (https://www.bas.uni-muenchen.de/Bas/BasMAUS.html). 
Since the dataset (must-c) was extremely large and the code is heavily tailored for must-c dataset, we were not able to complete this.

Citations
```
@inproceedings{fang-etal-2022-STEMM,
	title = {STEMM: Self-learning with Speech-text Manifold Mixup for Speech Translation},
	author = {Fang, Qingkai and Ye, Rong and Li, Lei and Feng, Yang and Wang, Mingxuan},
	booktitle = {Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics},
	year = {2022},
}
@inproceedings{zanon-boito-etal-2020-mass, 
	title = {{M}a{SS}: {A} {L}arge and {C}lean {M}ultilingual {C}orpus of {S}entence-aligned {S}poken {U}tterances {E}xtracted from the {B}ible}, author = {Zanon 	      Boito*, Marcely and Havard*, William and Garnerin, Mahault and Le Ferrand, Éric and Besacier, Laurent}, booktitle = {Proceedings of the 12th Language                 Resources and Evaluation Conference}, month = may, year = {2020}, address = {Marseille, France}, publisher = {European Language Resources Association}, url = 	  {https://aclanthology.org/2020.lrec-1.799}, pages = {6486--6493}, language = {English}, isbn = {979-10-95546-34-4}, 
}
```

## Contact

If you have any questions, feel free to contact me at `fangqingkai21b@ict.ac.cn`.

