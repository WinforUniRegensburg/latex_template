# Purpose of this repository

This repository contains both a [latex](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/LatexVorlage.tex) ([PDF version](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/LatexVorlage.pdf)) and a [Word](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/WordVorlage.docx) template for  theses and seminar papers. Below is a guideline that outlines the different aspects of a thesis or seminar paper.

# Abstract

The abstract acts as a point-of-entry for the reader, providing a first overview of the research study, namely, the motivation for the study, the methodological approach taken and a summary of the main results. In addition, the purpose of the research study should be clearly defined. Typically, an abstract consists of around 150 words. In the case of online databases, the abstract allows readers to quickly decide on the relevance of the study for their own work.

# Chapter 1 – Introduction

The introduction should precisely outline the purpose of the study as well as the research question that is sought to be answered. By briefly outlining the context of the study in terms of content and time, the reader acquires a quick overview. A key aspect of the introduction is the presentation of the motivation for conducting the study. This gives the reader a basic understanding of the topic and underpins the relevance and importance of the study. The relevance as well as the purpose can further be highlighted by using an appropriate quotation. The final paragraph of the introduction gives an outline of the structure of the study, that is, the approaches taken in each step of conducting the research study are briefly described. This gives the reader a clear picture of the composition of the study, i.e., what can and what cannot be expected of the study.

# Chapter 2 – Background and Literature Review

This section sets the theoretical and conceptual context of the study and grounds the leading assumptions in theories. This is done by outlining and citing pertinent work. Here, the author can present the acquired background knowledge that is relevant for the following sections of the study. This background knowledge also helps in building the conceptual framework of the study.

# Chapter 3 – Conceptual Framework

In this section, the author defines the conceptual framework of the research study. A graphical representation of the framework helps to illustrate complex theoretical constructs as well as the boundaries of the research study. The explicit statement of the conceptual framework not just informs the reader, it also guides the author in conducting the research. This is especially important for novices, as "getting lost" in research and straying away from the actual research question are common pitfalls.  

# Chapter 4 – Methodology

The  methodology section describes a systematic and goal-oriented approach to answer the research question. The application of this approach is essential and transforms human action into a scientific construct. The author can freely choose the methodological approach; however, the author should evaluate which approach is best to answer the research questions. The approach may be, for example, empirical, analytical, comparative, systematic, historic, or hermeneutic ([Goethe Universität](https://www.uni-muenster.de/imperia/md/content/didaktik_der_chemie/wissenschaftlichesarbeiten/leitfaden.pdf)).

# Chapter 5 – Results

In this section the author presents the results of the study. In case they are presented by means of figures and/or tables, the results should be clearly legible. Furthermore, in the case of figures, it is recommended to use vector graphics as this ensures good readability without the need to pre-specify the font size within the figures. An example figure and table can be found in the [latex](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/LatexVorlage.tex)  and  [Word](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/WordVorlage.docx) template contained in this repository.

# Chapter 6 – Discussion

In this section the author provides a discussion of the results and is thus able to draw an informed conclusion. More precisely, the discussion is an evaluative summary of the research study in relation to the research question. In general, the discussion can be divided in three parts. First, the results should be tied to the research question, thus presenting the reader a solution or improvement to the identified problem space. Here, for example, the author can draw on empirical findings introduced in the Results section to support his or her argument. Next, the author should outline the limitations of the research study by critically examining the used research approach. Limitations might comprise, for example, a limited time frame considered in the research study, or the individual refinement of a specific research method due to time constraints. Finally, suggestions for future research avenues should be provided. These suggestions may be in line with the limitations, as this allows other researchers to build on the present work by extending or analyzing it. In summary, the Discussion section presents the results in relation to the research question as well as restrictions of the study and suggestions for future research in the respective domain.

# Chapter 7 – Conclusion

The conclusion contains a summary of the research study. In contrast to the Discussion section, in which the main results are presented, here the key contributions of the work are showcased. A well-crafted conclusion answers the research question stated in the Introduction. By so doing, the author clarifies to what extent the research study has presented a solution or improvement to the examined problem space.

# General Information

## References and Citing

Citations are managed using [JabRef](http://www.jabref.org/) ([Wikipedia article](https://en.wikipedia.org/wiki/JabRef)) with a [BibTex file](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/references.bib). In Microsoft Word, the Plugin [Docear4Word](http://www.docear.org/software/add-ons/docear4word/download/) is used to cite directly from the [BibTex file](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/references.bib). The [MISQ author-year citation style](https://misq.org/manuscript-guidelines) is the citation style to be used. For example, indirect citations e.g., (Webster and Watson 2002) or direct citations e.g., Webster and Watson (2002). For further guidelines regarding the reference section refer to the above link.

## Environment

The tex files were created under the following setup
- Ubuntu 16.04 LTS (Xenial Xerus)
- TeXstudio 2.10.8

The following packages may need to be installed in order to build the template successfully
- texlive/xenial-updates
- texlive-bibtex-extra/xenial
- texlive-lang-german/xenial
- texlive-lang-english/xenial
- texlive-publishers/xenial
- texlive-publishers-doc/xenial
- texlive-science/xenial
- texlive-science-doc/xenial

In Ubuntu 16.04, this can be done with:
``
sudo apt install PackageName -y
``
