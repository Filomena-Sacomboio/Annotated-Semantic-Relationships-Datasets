data center that will be useful for our research
============================================

This repository contains datasets that have been used in malaria-related work.

<br><br>

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|
| [aimed.tar.gz](datasets/aimed.tar.gz)| 2 | English | 2005 | [Subsequence Kernels for Relation Extraction](nips-05.pdf)|
| [wikipedia_datav1.0.tar.gz](datasets/wikipedia_datav1.0.tar.gz) | 53 | English | 2006 | [Integrating Probabilistic Extraction Models and Data Mining to Discover Relations and Patterns in Text](papers/culotta06integrating.pdf) |
| [SemEval2007-Task4.tar.gz](datasets/SemEval2007-Task4.tar.gz) | 7 | English | 2007 | [SemEval-2007 Task 04: Classification of Semantic Relations between Nominals](papers/semeval2007.pdf)
| [hlt-naacl08-data.txt](datasets/hlt-naacl08-data.txt) | 2 | English | 2007 | [Learning to Extract Relations from the Web using Minimal Supervision](papers/bunescu-acl07.pdf) |
| [ReRelEM.tar.gz](datasets/ReRelEM.tar.gz) | 4 | Portuguese | 2009 | [Relation detection between named entities: report of a shared task](papers/FreitasetalSEW2009.pdf) |
| [SemEval2010_task8_all_data.tar.gz](datasets/SemEval2010_task8_all_data.tar.gz) | 10 / 19 (directional) | English | 2010 | [SemEval-2010 Task 8: Multi-Way Classification of Semantic Relations Between Pairs of Nominals](papers/semeval.pdf)
| [BioNLP.tar.gz](datasets/BioNLP.tar.gz) | 2 | English | 2011 | [Overview of BioNLP Shared Task 2011](papers/W11-1801.pdf) |
| [DDICorpus2013.zip](datasets/DDICorpus2013.zip) | 4 | English | 2012 | [The DDI corpus: An annotated corpus with pharmacological substances and drug–drug interactions](papers/1-s2.0-S1532046413001123-main.pdf) |
| [ADE-Corpus-V2.zip](datasets/ADE-Corpus-V2.zip) | 2 | English | 2013 | [Development of a benchmark corpus to support the automatic extraction of drug-related adverse effects from medical case reports](papers/ADE-V2.pdf) |
| [DBpediaRelations-PT-0.2.txt.bz2](datasets/DBpediaRelations-PT-0.2.txt.bz2)| 10 | Portuguese | 2013 |[Exploring DBpedia and Wikipedia for Portuguese Semantic Relationship Extraction](papers/minwise-linguamtica-13.pdf)|
| [kbp37-master.zip](datasets/kbp37-master.zip) | 37 directional | English | 2015 | [Relation Classification via Recurrent Neural Network](papers/KBP37.pdf) |

<br><br>

| Dataset                           | Nr. Classes   | Language | Year | Cite | 
| --------------------------------- |:-------------:| :-------:|------|------|
| [DataSet-IJCNLP2011.tar.gz](datasets/DataSet-IJCNLP2011.tar.gz) | Open | English | 2011 | [Extracting Relation descriptors with Conditional Random Fields](papers/rel_descriptors_with_crf.pdf) |
| [reverb_emnlp2011_data.tar.gz](datasets/emnlp2011_data.tar.gz) | Open | English | 2011 | [Identifying Relations for Open Information Extraction](papers/Fader-emnlp11.pdf) |
| [ClausIE-datasets.tar.gz](datasets/ClausIE-datasets.tar.gz) | Open | English | 2013 | [ClausIE: Clause-Based Open Information Extraction](papers/delcorro13clausie.pdf) |
| [emnlp13_ualberta_experiments_v2.zip](datasets/emnlp13_ualberta_experiments_v2.zip) | Open | English | 2013 | [Effectiveness and Efficiency of Open Relation Extraction](papers/Effectiveness_OIE.pdf) |

<br><br>

| Dataset                           | Nr. Classes   | Language |  Year | Cite | 
| --------------------------------- |:-------------:| :-------:|-------|------|
| [http://iesl.cs.umass.edu/riedel/ecml/](http://iesl.cs.umass.edu/riedel/ecml/) | Distant | English | 2010 | [Modeling Relations and Their Mentions without Labeled Text](papers/Ridel2010.pdf) |
| [https://github.com/google-research-datasets/relation-extraction-corpus](https://github.com/google-research-datasets/relation-extraction-corpus) | Distant | English | 2013 | [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html) |
| [PGR.zip](datasets/PGR.zip) | Distant | English | 2019 | [A Silver Standard Corpus of Human Phenotype-Gene Relations](papers/PGR.pdf)
| [PGR-crowd.zip](datasets/PGR-crowd.zip) | Distant + Crowdsourced | English | 2020 | [A hybrid approach toward biomedical relation extraction training corpora: combining distant supervision with crowdsourcing](papers/PGR-crowd.pdf)



<br><br>

<a name="tie"></a>
# Traditional Information Extraction

### DBpediaRelations-PT

**Dateset**: [DBpediaRelations-PT-0.2.txt.bz2](datasets/DBpediaRelations-PT-0.2.txt.bz2)

**Cite**: [Exploring DBpedia and Wikipedia for Portuguese Semantic Relationship Extraction](papers/minwise-linguamtica-13.pdf)

**Description**: A collections of sentences in Portuguese that express semantic relationships between pairs of entities extracted from
DBPedia. The sentences were collected by distant supervision, and were than manuall revised.

---

### AImed


**Dateset**: [aimed.tar.gz](datasets/aimed.tar.gz)

**Cite**: [Subsequence Kernels for Relation Extraction](erk-nips-05.pdf)

**Description**: It consists of 225 Medline abstracts, of which 200 are known to describe interactions between human proteins, while the other 25 do not refer to any interaction. There are 4084 protein references and around 1000 tagged interactions in this dataset.

---

### SemEval 2007

**Dateset**: [SemEval2007-Task4.tar.gz](datasets/SemEval2007-Task4.tar.gz)

**Cite**: [SemEval-2007 Task 04: Classification of Semantic Relations between Nominals](papers/semeval2007.pdf)

**Description**: Small data set, containing 7 relationship types and a total of 1,529 annotated examples.

---

### SemEval 2010

**Dateset**: [SemEval2010_task8_all_data.tar.gz](datasets/SemEval2010_task8_all_data.tar.gz)

**Cite**: [SemEval-2010 Task 8: Multi-Way Classification of Semantic Relations Between Pairs of Nominals](papers/semeval.pdf)

**Description**: SemEval-2010 Task 8 as a multi-way classification task in which the label for each example must be chosen from the complete set of ten relations and the mapping from nouns to argument slots is not provided in advance. We also provide more data: 10,717 annotated examples, compared to 1,529 in SemEval-1 Task 4.

---

### ReRelEM

**Dateset**: [ReRelEM.tar.gz](datasets/ReRelEM.tar.gz)

**Cite**: [Relation detection between named entities: report of a shared task](papers/FreitasetalSEW2009.pdf)

**Description**: First evaluation contest (track) for Portuguese whose goal was to detect and classify relations betweennamed entities in running text, called ReRelEM. Given a collection annotated with named entities belonging to ten different semantic categories, we marked all relationships between them within each document. We used the following fourfold relationship classification: identity, included-in, located-in, and other (which was later on explicitly detailed into twenty different relations).

---

### Wikipedia

**Dateset**: [wikipedia_datav1.0.tar.gz](datasets/wikipedia_datav1.0.tar.gz)

**Cite**: [Integrating Probabilistic Extraction Models and Data Mining to Discover Relations and Patterns in Text](papers/culotta06integrating.pdf)

**Description**: We sampled 1127 paragraphs from 271 articles from the online encyclopedia Wikipedia and labeled a total of 4701 relation instances. In addition to a large set of person-to-person relations, we also included links between people and organizations, as well as biographical facts such as birthday and jobTitle. In all, there are 53 labels in the training data.

---

### Web

**Dateset**: [hlt-naacl08-data.txt](datasets/hlt-naacl08-data.txt)

**Cite**: [Learning to Extract Relations from the Web using Minimal Supervision](papers/bunescu-acl07.pdf)

**Description**: Corporate Acquisition Pairs and Person-Birthplace Pairs taken from the web. The corporate acquisition test set has a total of 995 instances, out of which 156 are positive. The person-birthplace test set has a total of 601 instances, and only 45 of them are positive.

---

### BioNLP Shared Task

**Dateset**: [BioNLP.tar.gz](datasets/BioNLP.tar.gz)

**Cite**: [Overview of BioNLP Shared Task 2011](papers/W11-1801.pdf)

**Description**: The task involves the recognition of two binary part-of relations between entities: PROTEIN-COMPONENT and SUBUNITCOMPLEX. The task is motivated by specific challenges: the identification of the components of proteins in text is relevant e.g. to the recognition of Site arguments (cf. GE, EPI and ID tasks), and relations between proteins and their complexes relevant to any task involving them. REL setup is informed by recent semantic relation tasks (Hendrickx et al., 2010). The task data, consisting of new annotations for GE data, extends a previously introduced resource (Pyysalo et al., 2009; Ohta et al., 2010a).

---

### The DDI corpus

**Dateset**: [DDICorpus2013.zip](datasets/DDICorpus2013.zip)

**Cite**: [The DDI corpus: An annotated corpus with pharmacological substances and drug–drug interactions](papers/1-s2.0-S1532046413001123-main.pdf)

**Description**: The DDI corpus  contains MedLine abstracts on drug-drug interactions as well as documents describing drug-drug interactions from the DrugBank database. This task is designed to address the extraction of drug-drug interactions as a whole, but divided into two subtasks to allow separate evaluation of the performance for different aspects of the problem. The task includes two subtasks:
- Task 1: Recognition and classification of drug names.
- Task 2: Extraction of drug-drug interactions. The extraction of drug-drug interactions is a specific relation extraction task in biomedical literature. This task could be very appealing to groups studying PPI (protein-protein interaction) extraction because they could adapt their systems to extract drug-drug interactions. 

Four types of DDIs are proposed:
- mechanism: This type is used to annotate DDIs that aredescribed by their PK mechanism (e.g.Grepafloxacin may inhibitthe    metabolism of theobromine).
- effect:This type is used to annotate DDIs describing an effect(e.g.In uninfected volunteers, 46% developed rash while      receivingSUSTIVA and clarithromycin) or a PD mechanism (e.g.Chlorthali-done may potentiate the action of other                antihypertensive drugs).
- advice:This type is used when a recommendation or adviceregarding a drug interaction is given (e.g.UROXATRAL shouldnot      be used in combination with other alpha-blockers).
- int:This type is used when a DDI appears in the text withoutproviding any additional information (e.g.The interaction        ofomeprazole and ketoconazole has been established)
 
---

### ADE-V2

**Dateset**: [ADE-Corpus-V2.zip](datasets/ADE-Corpus-V2.zip)

**Cite**: [Development of a benchmark corpus to support the automatic extraction of drug-related adverse effects from medical case reports](papers/ADE-V2.pdf)

**Description**: The work presented here aims at generating a systematically annotated corpus that can support the development and validation of methods for the automatic extraction of drug-related adverse effects from medical case reports. The documents are systematically double annotated in various rounds to ensure consistent annotations. The annotated documents are finally harmonized to generate representative consensus annotations. In order to demonstrate an example use case scenario, the corpus was employed to train and validate models for the classification of informative against the non-informative sentences. A Maximum Entropy classifier trained with simple features and evaluated by 10-fold cross-validation resulted in the F1 score of 0.70 indicating a potential useful application of the corpus. 

---

### KBP-37

**Dateset**: [kbp37-master.zip.zip](datasets/kbp37-master.zip)

**Cite**: [Relation Classification via Recurrent Neural Network](papers/KBP37.pdf)

**Description**: This dataset is a revision of MIML-RE annotation dataset, provided by Gabor Angeli et al. (2014). They use both the 2010 and 2013 KBP official document collections, as well as a July 2013 dump of Wikipedia as the text corpus for annotation, 33811 sentences been annotated. To make the dataset more suitable for our task, we made several refinement: 

1. First, we add direction to the relation names, such that ‘per:employee of’ is splited into two relations ‘per:employee of(e1,e2)’ and ‘per:employee of(e2,e1)’ except for ‘no relation’. According to description of KBP task,3 we replace ‘org:parents’ with ‘org:subsidiaries’ and replace ‘org:member of’ with ‘org:member’ (by their reverse directions). This leads to 76 relations in the dataset.

2. Then, we statistic the frequency of each relation with two directions separately. And relations with low frequency are discarded so that both directions of each relation occur more than 100 times in the dataset. To better balance the dataset, 80% ‘no relation’ sentences are also randomly discarded.

3. After that, dataset are randomly shuffled and then sentences under each relation are all split into three groups, 70% for training, 10% for
development, 20% for test. Finally, we remove those sentences in the development and test set whose entity pairs and relation are appeared in a training sentence simultaneously. 


<br><br>






<a name="oie"></a>
# Open Information Extraction

### ReVerb

**Dateset**: [reverb_emnlp2011_data.tar.gz](datasets/emnlp2011_data.tar.gz)

**Cite**: [Identifying Relations for Open Information Extraction](papers/Fader-emnlp11.pdf)

**Description**: 500 sentences sampled from the Web, using Yahoo’s random link service.

---

### ClausIE

**Dateset**: [ClausIE-datasets.tar.gz](datasets/ClausIE-datasets.tar.gz)

**Cite**: [ClausIE: Clause-Based Open Information Extraction](papers/delcorro13clausie.pdf)

**Description**:

Three different datasets. First, the Reverb dataset consists of 500 sentences with manually labeled extractions. The sentences have been obtained via the random-link service of Yahoo and are generally very noisy. Second, 200 random sentences from Wikipedia pages. These sentences are shorter, simpler, and less noisy than those of the Reverb dataset. Since some Wikipedia articles are written by non-native speakers, however, the Wikipedia sentences do contain some incorrect grammatical constructions. Third, 200 random sentences from the New York Times collection these sentences are generally very clean but tend to be long and complex.

---

### Effectiveness and Efficiency of Open Relation Extraction

**Dateset**: [emnlp13_ualberta_experiments_v2.zip](datasets/emnlp13_ualberta_experiments_v2.zip)

**Cite**: [Effectiveness and Efficiency of Open Relation Extraction](papers/Effectiveness_OIE.pdf)

**Description**: WEB-500 is a commonly used dataset, developed for the TextRunner experiments (Banko and Etzioni, 2008). These sentences are often incomplete and grammatically unsound, representing the challenges of dealing with web text. NYT-500 represents the other end of the spectrum with formal, well written new stories from the New York Times Corpus (Sandhaus, 2008). PENN-100 contains sentences from the Penn Treebank recently used in an evaluation of the TreeKernel method (Xu et al., 2013). We manually annotated the relations for WEB-500 and NYT-500 and use the PENN-100 annotations provided by TreeKernel’s authors (Xu et al., 2013).

---

### Extracting Relation descriptors with Conditional Random Fields

**Dateset**: [DataSet-IJCNLP2011.tar.gz](datasets/DataSet-IJCNLP2011.tar.gz)

**Cite**: [Extracting Relation descriptors with Conditional Random Fields](papers/rel_descriptors_with_crf.pdf)

**Description**: New York Times data set contains 150 business articles from New York Times. The articles were crawled from the NYT website between November 2009 and January 2010. After sentence splitting and tokenization, we used the Stanford NER tagger (URL: http://nlp.stanford.edu/ner/index.shtml) to identify PER and ORG named entities from each sentence. For named entities that contain multiple tokens we concatenated them into a single token. We then took each pair of (PER, ORG) entities that occur in the same sentence as a single candidate relation instance, where the PER entity is treated as ARG-1 and the ORG entity is treated as ARG-2.

Wikipedia data was previously created by Aron Culotta et al.. Since the original data set did not contain the annotation information we need, we re-annotated it. Similarly, we performed sentence splitting, tokenization and NER tagging, and took pairs of (PER, PER) entities occurring in the same sentence as a candidate relation instance. We always treat the first PER entity as ARG-1 and the second PER entity as ARG-2.

<br><br>

<a name="ds"></a>
# Distant Supervision for Relation Extraction

### NYT dataset

**Dateset**: [http://iesl.cs.umass.edu/riedel/ecml/](http://iesl.cs.umass.edu/riedel/ecml/)

**Cite**: [Modeling Relations and Their Mentions without Labeled Text](papers/Ridel2010.pdf)

**Description**: The NYT dataset is a widely used dataset on distantly supervisied relation extraction task. This dataset was generated by aligning freebase relations with the New York Times (NYT) corpus, with sentences from the years 2005-2006 used as the training corpus and sentences from 2007 used as the testing corpus.

---

### Google's relation-extraction-corpus

**Dateset**: [https://github.com/google-research-datasets/relation-extraction-corpus](https://github.com/google-research-datasets/relation-extraction-corpus)

**Cite**: [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html)

**Description**: [https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html](https://research.googleblog.com/2013/04/50000-lessons-on-how-to-read-relation.html)

---

### PGR Corpus

**Dataset**: [PGR.zip](datasets/PGR.zip)

**Cite**: [A Silver Standard Corpus of Human Phenotype-Gene Relations](papers/PGR.pdf)

**Description**: Human phenotype-gene relations are fundamental to fully understand the origin of some phenotypic abnormalities and their associated diseases. Biomedical literature is the most comprehensive source of these relations, however, we need Relation Extraction tools to automatically recognize them. Most of these tools require an annotated corpus and to the best of our knowledge, there is no corpus available annotated with human phenotype-gene relations. This paper presents the Phenotype-Gene Relations (PGR) corpus, a silver standard corpus of human phenotype and gene annotations and their relations. The corpus consists of 1712 abstracts, 5676 human phenotype annotations, 13835 gene annotations, and 4283 relations. We generated this corpus using Named-Entity Recognition tools, whose results were partially evaluated by eight curators, obtaining a precision of 87.01%. By using the corpus we were able to obtain promising results with two state-of-the-art deep learning tools, namely 78.05% of precision. The PGR corpus was made publicly available to the research community.

---

### PGR-crowd Corpus

**Dataset**: [PGR-crowd.zip](datasets/PGR-crowd.zip)

**Cite**: [A hybrid approach toward biomedical relation extraction training corpora: combining distant supervision with crowdsourcing](papers/PGR-crowd.pdf)

**Description**: Biomedical relation extraction (RE) datasets are vital in the construction of knowledge bases and to potentiate the discovery of new interactions. There are several ways to create biomedical RE datasets, some more reliable than others, such as resorting to domain expert annotations. However, the emerging use of crowdsourcing platforms, such as Amazon Mechanical Turk (MTurk), can potentially reduce the cost of RE dataset construction, even if the same level of quality cannot be guaranteed. There is a lack of power of the researcher to control who, how and in what context workers engage in crowdsourcing platforms. Hence, allying distant supervision with crowdsourcing can be a more reliable alternative. The crowdsourcing workers would be asked only to rectify or discard already existing annotations, which would make the process less dependent on their ability to interpret complex biomedical sentences. In this work, we use a previously created distantly supervised human phenotype–gene relations (PGR) dataset to perform crowdsourcing validation. We divided the original dataset into two annotation tasks: Task 1, 70% of the dataset annotated by one worker, and Task 2, 30% of the dataset annotated by seven workers. Also, for Task 2, we added an extra rater on-site and a domain expert to further assess the crowdsourcing validation quality. Here, we describe a detailed pipeline for RE crowdsourcing validation, creating a new release of the PGR dataset with partial domain expert revision, and assess the quality of the MTurk platform. We applied the new dataset to two state-of-the-art deep learning systems (BiOnt and BioBERT) and compared its performance with the original PGR dataset, as well as combinations between the two, achieving a 0.3494 increase in average F-measure. The code supporting our work and the new release of the PGR dataset is available at https://github.com/lasigeBioTM/PGR-crowd.
