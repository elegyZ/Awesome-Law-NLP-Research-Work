# NLP Paper Analysis in LAW

There are different areas of application for NLP methods.

模型的目标，语义逻辑，推理

如果用纯中文文本是否会不利于项目申请

有一个终极的研究目标（语义逻辑，推理），为了达到这个目标要进行的系列研究（文本分类等等）

## Classification Issues

question classification in text classification (hierarchical classification)

law issue classification based on multi-task classification

为法律案件和法规检索构建一个框架

Most legal QA system (some systems are developed for bar test)

predict the law area for cases (which area of law applies to a given case, what the ruling might be, which laws apply to the case, etc. Given the data available on previous court rulings)

As for searching,  instead of key word based search, we use the full “draft” case description and text classification methods

document classification of legal court opinions

assigning classification cases automatically

domain-speciﬁc classiﬁcation technique, classify pieces of laws into diﬀerent categories

legal documant management system

ﬁnding relevant cases given the query

providing applicable law articles for a given case

QA but focus on word features and embedding

hierarchical crime classification

## Textual Entailment**

legal question answering information retrieval (IR) task

capture the relationship between legal question and civil law articles

Analysis the legal document's inner logic problem via joint context and topic attention. By using the plaintiff allegation and defendant argument to figure the Dispute Generation (DG) problem (An text generation problem)

the proposed event tree construction method combined with the deep forest algorithm can greatly improve the logical interpretation and accuracy of judicial text.

Joint similarity training for semantic and structural information of data

legal bar examination QA system

## Argumentation Mining**

detect the arguments presented in a text document

the relations between them

the internal structure of each individual argument



## Vague Legal Concepts

legal concepts may not be as accurate as we expected



## Charge Prediction

legal jugement prediction

generate court view from the fact description in a criminal case (natural language generation)

Penalty prediction

## Domain Identification

automation, semi-automation of the legal domain



## Evaluating the Rationality of Judicial Decision

In order to make full use of precedent judgments, there are still several key issues that need to be addressed: 

*i)* how to effectively extract features well representing a case from legal texts,

*ii)* how to quickly and accurately retrieve the most similar cases from the vast case-base

*iii)* how to evaluate the rationality of a judgment with its similar cases.



## Legal Text Summarization

Legal document summarization is an emerging subtopic of text summarization.

At present, lot of effort goes into preparing manual drafting of case summaries. 

an automated text summarization system based on sematic analysis



## Legal Public Opinion News Summarization





## Document Translation





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

["中国法研杯"司法人工智能挑战赛数据](https://github.com/thunlp/CAIL)

Europarl: A Parallel Corpus for Statistical Machine Translation

DCEP -Digital Corpus of the European Parliament

The JRC-Acquis: A multilingual aligned parallel corpus with 20+ languages

International Court Cases: [Law2Vec: Legal Word Embeddings](https://archive.org/details/Law2Vec)

[HUDOC - European Court of Human Rights](https://www.dropbox.com/s/lxpvvqdwby30157/crystal_ball_data.tar.gz)

14,2394 legal judgments about all kinds of matrimonial disputes from China Judgments Online, and extract PA, DA and disputes from these legal judgments. (contact the author *bisheng*@*seu*.*edu*.*cn*)

[Chinese judicial reading comprehension (CJRC) dataset]SMP2019“中国法研杯”中文法律阅读理解比赛



## Relative Models

CNN, multi-task learning

genetic algorithm, KNN

中文分词系统SCWS，FudanNLP，HTTPCWS，IKAnalyzer 3.x，CKIP，ICTCLAS

中文分词插件Jieba, SOTA(目前最新的)

SVM for classification

ranking SVN and deep-CNN

LSTM model, locality-sensitive hashing (LSH) scheme

semi-supervised learning, N-Grams model

Latent Semantic Analysis (LSA) Model

multi-task deep learning, transfer learning

fastText, TextCNN

BERT, LDA, Glove

CapsNet, GRU

ROUGE metrics

## The Project Outline

1. methods evaluation and  classification model implementation

2. To predict the legal article and document, the previouse model should be improved. Learn decision-making rules to assist the legal judgment, such as recommendation of similar cases and legal document verification.

3. Make the model interpretable and merge the logistic of text into the model. Try to combine and compare the manual logic decision process with the machine learning momdel.

4.



predicting the legal area and what laws might apply to a case are very important applications for NLP



量化文本分析：利用文本数据进行因果推论

潜在关系挖掘, 机器学习技术擅长挖掘现有数据中难以检测的隐藏关系, 理清当前数据的复杂关系, 突出某些需要律师提高注意力的潜在相关文件

The evaluation metrix should contain both automatic evaluation and the human annotation.



Natural Language Inference

text entailment 给定一个前提文本（premise），根据这个前提去推断假说文本（hypothesis）与premise的关系，一般分为蕴含关系（entailment）和矛盾关系（contradiction），蕴含关系（entailment）表示从premise中可以推断出hypothesis；矛盾关系（contradiction）即hypothesis与premise矛盾。文本蕴含的结果就是这几个概率值。
前提文本--之前的判决法律文件

假说文本--作为input的一个特定的case

text entailment分为三个部分: 

recognizing text entailment

Textual Entailment Knowledge Acquisition

generating text entailment pairs

法律文件是否可以通过模板级别的蕴含知识获取来进行分析
