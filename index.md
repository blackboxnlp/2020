## Venue

The workshop will be collocated with EMNLP 2020.

**News (Sept. 2): Test models for the shared task have been [announced](http://blackboxnlp.github.io/shared).**

## Important dates (updated!)

- August 15, 2020 -- Submission deadline.
- September 20, 2020 -- Retraction of workshop papers accepted for EMNLP.
- September 21, 2020 -- Shared task submission deadline
- September 29, 2020 -- Notification of acceptance.
- October 10, 2020 -- Camera-ready papers due.
- November 20, 2020 -- Workshop.
 
## Workshop description

Neural networks have rapidly become a central component in NLP systems in
the last few years. The improvement in accuracy and performance brought by
the introduction of neural networks has typically come at the cost of our
understanding of the system: How do we assess what the representations and
computations are that the network learns? The goal of this workshop is to
bring together people who are attempting to peek inside the neural network
black box, taking inspiration from machine learning, psychology,
linguistics, and neuroscience. The topics of the workshop will include, but
are not limited to:

- Applying analysis techniques from neuroscience to analyze
high-dimensional vector representations (such as Haxby et al., 2001;
Kriegeskorte, 2008) in artificial neural networks;
- Analyzing the network's response to strategically chosen inputs in order
to infer the linguistic generalizations that the network has acquired
(e.g., Linzen et al., 2016; Loula et al., 2018);
- Examining the performance of the network on simplified or formal
languages (e.g., Hupkes et al., 2018; Lake et al., 2018);
- Proposing modifications to neural network architectures that can make
them more interpretable (e.g., Palanki et al., 2017);
- Scaling up neural network analysis techniques developed in the
connectionist literature in the 1990s (Elman, 1991);
- Testing whether interpretable information can be decoded from
intermediate representations (e.g., Adi et al.,  2017; Chrupala et al.,
2017; Hupkes et al., 2017);
- Translating insights on neural networks interpretation from the vision
domain (e.g., Zeiler & Fergus, 2014) to language;
- Explaining model predictions (e.g., Lei et al., 2016; Alvarez-Melis &
Jaakkola, 2017): What are ways to explain specific decisions made by neural
networks?
- Adversarial examples in NLP (e.g., Ebrahimi et al., 2018; Belinkov &
Bisk, 2018): How to generate them and how to evaluate their quality?
- Open-source tools for analyzing neural networks in NLP (e.g., Strobelt et
al., 2018; Rikters, 2018).
- Evaluation of analysis results: How do we know that the analysis is
valid?

BlackboxNLP 2020 is the third BlackboxNLP workshop. 
The programme and proceedings of the previous editions, which were held at EMNLP 2018 and ACL 2019, can be found [here](https://blackboxnlp.github.io/2018/) and [here](https://blackboxnlp.github.io/2019/).

The call for papers text is available [here](http://blackboxnlp.github.io/cfp).

## Organizers

### Afra Alishahi
Afra Alishahi (a.alishahi@uvt.nl) is an Associate Professor of Cognitive Science and Artificial Intelligence at Tilburg University, the Netherlands. 
Her main research interest is developing computational models for studying the process of human language acquisition. 
Recently she has been studying the emergence of linguistic structure in grounded models of language learning. 
She has chaired CoNLL 2015, and organized the EACL Workshop on Cognitive Aspects of Computational Language Acquisition in 2009, and co-organized the first edition of BlackboxNLP.

### Yonatan Belinkov
Yonatan Belinkov (belinkov@technion.ac.il) is an Assistant Professor at the Technion Department of Computer Science. He has previously been a postdoc at the Harvard School of Engineering and Applied Sciences (SEAS) and the MIT Computer Science and Artificial Intelligence Laboratory (CSAIL). 
His research focuses on interpretability and robustness of neural network models of human language. 
His research has been published at venues such as ACL, EMNLP, NAACL, TACL, ICLR, and NeurIPS. 
He serves or has served as an area chair for ACL, EMNLP, and CoNLL, and co-organized the second edition of BlackboxNLP. 
His PhD dissertation at MIT analyzed internal language representations in deep learning models, with applications in machine translation and speech recognition. 

### Grzegorz Chrupała
Grzegorz Chrupała (g.chrupala@uvt.nl) is an Associate Professor at the Department of Cognitive Science and Artificial Intelligence at Tilburg University. His research focuses on computational models of language learning from multimodal signals such as speech and vision and on the analysis and interpretability of representations emerging in
multilayer neural networks. His work has appeared in venues such as *Computational Linguistics*, ACL, EMNLP and CoNLL. He has served as area chair for ACL, EMNLP and CoNLL and he co-organized the first two editions of BlackboxNLP.

### Dieuwke Hupkes
Dieuwke Hupkes (d.hupkes@uva.nl) is a Postdoc at the University of Amsterdam, supported by the [ELLIS society](https://ellis.eu/).
The main focus of her research is understanding how neural networks can understand and learn the structures that occur in natural language.
Developing methods to interpret and interact with neural networks has therefore been an important area of focus in her research.
She authored 5 articles directly relevant to the workshop, one of them published in a top AI journal (Journal of Artificial Intelligence), and she is co-organizing a workshop on compositionality, neural networks, and the brain, held at the Lorentz Center in the summer of 2019.

### Yuval Pinter
Yuval Pinter (uvp@gatech.edu) is a PhD student at Georgia Institute of Technology. 
His main focus is on word-level representations in deep learning systems. 
He authored two papers on the topic of NLP neural model interpretation in 2019, including one at BlackboxNLP.
In addition to regularly serving on program committees for NLP and AI venues, he co-organized the TREC LiveQA competition for its three years of existence (2015--2017), and served as publicity and social media co-chair at NAACL 2019.

### Hassan Sajjad 
Hassan Sajjadd (hsajjad@hbku.edu.qa) is a research scientist at the Arabic Language Technologies group, Qatar Computing Research Institute - HBKU. 
His recent research focuses on developing methods to analyze and interpret neural network models both at the representation-level and at the individual neuron-level. 
His work on the analysis of deep models is recognized at various prestigious research venues such as ACL, NAACL, ICLR, and AAAI.  

## Workshop program 

TBA

## Invited speakers

### Idan Blank, UCLA 
*Understanding NLP’s blackbox with the brain’s blackbox and vice versa*

This talk will propose a bi-directional link between artificial and biological language processing mechanisms, demonstrating that each can be used as a tool for studying the other. First, I will ask: given what we know about language processing in the human brain and mind, what would success in artificial NLP look like? Specifically, I will focus on dissociations between language and the rest of high-level cognition to significantly narrow the space of “reasonable expectations” we should pose to language models. Next, I will ask: could state-of-the-art NLP systems provide a decent model of the human brain? Here, I will describe promising work demonstrating that some NLP systems can accurately predict brain responses to linguistic stimuli, and offer initial clues into what might drive such brain-machine correspondence.

### Roger Levy, MIT
*Evaluating and calibrating neural language models for human-like language processing*

With new architectures, larger datasets, and greater computational power, neural language models are getting better and better at the tasks they’re trained for and at offering out-of-the-box representations that can be fine-tuned for high performance in new tasks.  
But are they getting more and more human-like?  
Here we use linguistic theory and experimental methods inspired by psycholinguistic research to assess zero- and few-shot performance of contemporary neural models on a range of signature human-like language understanding behaviors.  
While we find impressive successes by models trained on large quantities of text alone, we find clear advantages for models with a symbolic component when training data scale is small.  
We also obtain success in calibrate models for more human-like processing.  
Our results highlight the value of insights from psycholinguistics and cognitive science for neural language models of the future.

### Anna Rogers, University of Copenhagen
*When BERT plays the lottery, all tickets are winning!*

The lottery ticket hypothesis was originally developed for randomly initialized models, but might it also apply to pre-trained Transformers? If the "good" subnetworks exist, can they tell us anything about how BERT achieves its performance? 

## Shared Interpretation Mission

BlackboxNLP 2020 will include a shared interpretation mission. Details available [here](https://blackboxnlp.github.io/shared).

## Paper submission 

We accept two types of papers

- <b>Archival papers</b>. These are papers reporting on completed, original and unpublished research, with maximum length of 8 pages + references. Papers shorter than this maximum are also welcome. An optional appendix may appear after the references in the same pdf file. Accepted papers are expected to be presented at the workshop and will be published in the workshop proceedings. They should report on obtained results rather than intended work. These papers will undergo double-blind peer-review, and should thus be anonymized. Archival papers will be included in the workshop proceedings and the ACL anthology.

- <b>Extended abstracts</b>. These may report on work in progress or may be cross submissions that have already appeared in a non-NLP venue. The extended abstracts are of maximum 2 pages + references. These submissions are non-archival in order to allow submission to another venue. The selection will not be based on a double-blind review and thus submissions of this type need not be anonymized. Abstracts will be posted on the workshop website but will not be included in the proceedings.

Both papers and abstracts should follow the official EMNLP 2020 style guidelines and should be submitted via softconf:

[https://www.softconf.com/emnlp2020/blackboxnlp2020/](https://www.softconf.com/emnlp2020/blackboxnlp2020/)

Accepted submissions will be presented at the workshop: most as posters, some as oral presentations (determined by the program committee).

## Dual submissions and preprints 
Dual submissions with the main conference are allowed, but authors must declare dual submission by entering the paper's main conference submission id.
The reviews for the submission for the main conference will be automatically forwarded to the workshop and taken into consideration when your paper is evaluated.
Authors of dual-submission papers accepted to the main conference should retract them from the workshop by September 20.

Papers posted to preprint servers such as arxiv can be submitted
without any restrictions on when they were posted.

## Program committee

 - Samira Abnar 
 - Željko Agić 
 - Antonios Anastasopoulos 
 - Leila Arras - Fraunhofer Heinrich Hertz Institute
 - Jasmijn Bastings - Google
 - Lisa Beinborn - University of Amsterdam
 - Laurent Besacier - Laboratoire d'Informatique de Grenoble
 - Stergios Chatzikyriakidis - University of Gotheburg
 - Barry Devereux - Queen's University
 - Ewan Dunbar - Université Paris Diderot
 - Allyson Ettinger - University of Chicago
 - Antske Fokkens - Vrije Universiteit Amsterdam
 - Robert Frank - Yale University
 - Alexander Fraser - LMU Munich
 - Richard Futrell - University of California, Irvine 
 - Sebastian Gehrmann - Harvard University
 - Kristina Gulordava - University Pompeu Fabra
 - David Harwath - MIT 
 - John Hewitt - Stanford University
 - Cassandra Jacobs - University of Wisconsin
 - Yair Lakretz - NeuroSpin
 - Shalom Lappin - University of Gothenburg
 - Miryam de Lhoneux    - Uppsala University
 - Tal Linzen - Johns Hopkins University
 - Nelson F. Liu - University of Washington
 - Pranava Madhyastha - Imperial College London
 - Arya McCarthy - Johns Hopkins University
 - Paola Merlo - University of Geneva
 - Raymond Mooney - UT AUstin %University of Texas at Austin 
 - Joakim Nivre - Uppsala University
 - Sebastian Padó - University of Stuttgart
 - Ellie Pavlick - Brown University
 - Rudolf Rosa - Charles University
 - Carolyn Rose - CMU %Carnegie Mellon University
 - Sebastian Ruder - DeepMind
 - Wojciech Samek - Fraunhofer Heinrich Hertz Institute
 - Naomi Saphra - University of Edinburgh
 - Sabine Schulte im Walde - University of Stuttgart
 - Rico Sennrich - University of Zurich
 - Pia Sommerauer - Vrije Universiteit Amsterdam
 - Ivan Titov - University of Edinburgh
 - Francesca Toni - Imperial College London
 - Reut Tsarfaty - Open University
 - Sarah Wiegreffe -  Georgia Tech
 - Adina Williams - New York University
 - Diyi Yang - Georgia Tech
 - Fabio Massimo Zanzotto - University of Rome
 - Willem Zuidema - University of Amsterdam

## Anti-Harassment Policy
BlackboxNLP 2020 adheres to the [ACL Anti-Harassment Policy](https://www.aclweb.org/adminwiki/sphp?title=Anti-Harassment_Policy).
