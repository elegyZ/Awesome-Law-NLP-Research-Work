# NLP Paper Analysis in LAW

There are different areas of application for NLP methods.

模型的目标，语义逻辑，推理

如果用纯中文文本是否会不利于项目申请

## Classification Issues

question classification in text classification (hierarchical classification)

law issue classification based on multi-task classification

为法律案件和法规检索构建一个框架

Most legal QA system

predict the law area for cases (which area of law applies to a given case, what the ruling might be, which laws apply to the case, etc. Given the data available on previous court rulings)

As for searching,  instead of key word based search, we use the full “draft” case description and text classification methods

document classification of legal court opinions

assigning classification cases automatically

## Textual Entailment

legal question answering information retrieval (IR) task

capture the relationship between legal question and civil law articles



## Vague Legal Concepts

legal concepts may not be as accurate as we expected



## Charge Prediction



## Domain Identification



## Evaluating the Rationality of Judicial Decision

In order to make full use of precedent judgments, there are still several key issues that need to be addressed: 

*i)* how to effectively extract features well representing a case from legal texts,

*ii)* how to quickly and accurately retrieve the most similar cases from the vast case-base

*iii)* how to evaluate the rationality of a judgment with its similar cases.



## Legal Text Summarization

Legal document summarization is an emerging subtopic of text summarization.

At present, lot of effort goes into preparing manual drafting of case summaries. 

an automated text summarization system based on sematic analysis



## Research on Multiple Law

Deep learning in law: early adaptation and legal word embeddings trained on large corpora

text classification, information extraction, and information retrieval

## Possible Datasets

LQDS datasets [中国法律问题数据集](https://ieeexplore.ieee.org/abstract/document/8119153)

Wikipedia word pages

crawl text, questions from legal website, such as China Judgement Online [中国裁判文书网](http://wenshu.court.gov.cn/website/wenshu/181217BMTKHNT2W0/index.html?s8=02)

The most popular databases for Chinese commercial cases are the *Magic Weapon of Peking University*, *Tiantong*, and *Jurist*, which emphasize the management of legal documents.

European Court of Human Rights (ECHR) 

Washington University School of Law Supreme Court Database [SCDB](http://supremecourtdatabase.org/)

词向量预训练语料(Google新闻数据集)

[找法网](http://china.findlaw.cn/)

[中国法律文献网络](http://www.falvwenshuwang.com/)

Emmanuel, S.L.: Strategies and Tactics for the MBE (Multistate Bar Exam), 2nd edn. Wolters Kluwer, Maryland (2011)

Herring, J.: Criminal Law: Text, Cases, and Materials. Oxford University Press USA, New York (2014)

Martin, J., Storey, T.: Unlocking criminal law, 4th edn. Routledge, New York (2013)

New York State Board of Law Examiners: Course Materials for the New York Law Course and New York Law Examination. [https://www.newyorklawcourse.org/CourseMaterials/NewYorkCourseMaterials.pdf](http://www-newyorklawcourse-org-s.libziyuan.bjut.edu.cn:8118/CourseMaterials/NewYorkCourseMaterials.pdf). Accessed 15 July 2018

[Law2Vec: Legal Word Embeddings](https://archive.org/details/Law2Vec)



## Relative Models

CNN, multi-task learning

genetic algorithm, KNN

中文分词系统SCWS，FudanNLP，HTTPCWS，IKAnalyzer 3.x，CKIP，ICTCLAS

中文分词插件Jieba

SVM for classification

ranking SVN and deep-CNN

LSTM model, locality-sensitive hashing (LSH) scheme

semi-supervised learning, N-Grams model

Latent Semantic Analysis (LSA) Model

