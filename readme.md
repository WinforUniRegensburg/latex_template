# Template for Theses and Seminars

This repository contains both a [latex](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/LatexVorlage.tex) ([PDF version](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/LatexVorlage.pdf)) and a [Word](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/WordVorlage.docx) template for theses and seminar papers. For simplicity, we refer to theses exclusively, but the guidelines also apply to seminar papers. Below is a guideline that outlines the different aspects of a thesis.

# Structure of the Thesis

The default structure outlined below may need to be adapted to the thesis. Concerning the writing style, it is possible to use "We" instead of passive voice.

## Abstract

The abstract acts as a point-of-entry for the reader, providing a first overview of the research study, namely, the motivation for the study, the methodological approach taken and a summary of the main results. In addition, the purpose of the research study should be clearly defined. Typically, an abstract consists of around 150 words.

## Introduction

The introduction should precisely outline the purpose of the study as well as the research question that is sought to be answered. By briefly outlining the context of the study in terms of content and time, the reader acquires a quick overview. A key aspect of the introduction is the presentation of the motivation for conducting the study. This gives the reader a basic understanding of the topic and underpins the relevance and importance of the study. The relevance as well as the purpose can further be highlighted by using an appropriate quotation.

The final paragraph of the introduction gives an outline of the structure of the study, that is, the approaches taken in each step of conducting the research study are briefly described. This gives the reader a clear picture of the composition of the study, i.e., what can and what cannot be expected of the study.

## Background

This section (could also be named Literature Review or Conceptual Framework) sets the theoretical and conceptual context of the study and grounds the leading assumptions in theories. This is done by outlining and citing pertinent work. Here, the author can present the acquired background knowledge that is relevant for the following sections of the study. This background knowledge also helps in building the conceptual framework of the study.

The literature review should focus on concepts as opposed to authors and historical development (cf. Webster and Watson, 2002). It is also possible to use a conceptual framework to structure the literature synthesis. Provide precise definitions of those concepts that are central to your work, emphasize concepts rather than authors, and do not include your own judgment in the background section. Use established definitions and concepts and provide a justification when adapting them.

A graphical representation of the framework helps to illustrate complex theoretical constructs as well as the boundaries of the research study. The explicit statement of the conceptual framework not just informs the reader, it also guides the author in conducting the research.

Relevant background literature can be found in journals such as those listed in
- the [AIS Senior Scholars' Basket of Journals](https://aisnet.org/general/custom.asp?page=SeniorScholarBasket)
- the [VHB Jourqual Ranking](http://vhbonline.org/VHB4you/jourqual/vhb-jourqual-3/teilrating-wi/)
- or conferences such as [ICIS](http://aisel.aisnet.org/icis/) and [ECIS](https://aisel.aisnet.org/ecis).

Papers can be accessed through the [EZB](http://ezb.uni-regensburg.de/), a search on [Researchgate](https://www.researchgate.net), a search on Google, or by contacting the authors.

Guidelines on searching the literature are provided by Webster and Watson (2002).

## Methodology

The methodology section describes a systematic and goal-oriented approach to answer the research question. Hence, the selection of the research method needs to be consistent with the research questions. The approach may be, for example, empirical, analytical, comparative, systematic, historic, or hermeneutic ([Goethe Universität](https://www.uni-muenster.de/imperia/md/content/didaktik_der_chemie/wissenschaftlichesarbeiten/leitfaden.pdf)). The methodological approach needs to be described in detail; it should be possible to understand all methodological procedures based on the thesis. For example, it is necessary to provide the formulas of regression models.

## Results

In this section the author presents the results of the study. In case they are presented by means of figures and/or tables, the results should be clearly legible. Furthermore, in the case of figures, it is recommended to use vector graphics as this ensures good readability without the need to pre-specify the font size within the figures. An example figure and table can be found in the [latex](LatexVorlage.tex)  and  [Word](WordVorlage.docx) template contained in this repository.

## Discussion

In this section the author provides a discussion of the results and is thus able to draw an informed conclusion. More precisely, the discussion is an evaluative summary of the research study in relation to the research question. In general, the discussion can be divided in three parts. First, the results should be tied to the research question, thus presenting the reader a solution or improvement to the identified problem space. Here, for example, the author can draw on empirical findings introduced in the Results section to support his or her argument. Next, the author should outline the limitations of the research study by critically examining the used research approach. Limitations might comprise, for example, a limited time frame considered in the research study, or the individual refinement of a specific research method due to time constraints. Finally, suggestions for future research avenues should be provided. These suggestions may be in line with the limitations, as this allows other researchers to build on the present work by extending or analyzing it. In summary, the Discussion section presents the results in relation to the research question as well as restrictions of the study and suggestions for future research in the respective domain.

## Conclusion

The conclusion contains a summary of the research study. In contrast to the Discussion section, in which the main results are presented, here the key contributions of the work are showcased. A well-crafted conclusion answers the research question stated in the Introduction. By so doing, the author clarifies to what extent the research study has presented a solution or improvement to the examined problem space.

# General Information

You can delete the cover pages that are not applicable to your thesis in the LatexVorlage.tex.

## Submission

When submitting the thesis make sure to
- include the data and the code for your analyses in a digital appendix (a CD that is placed on the corresponding appendix page)
- provide PDFs of the papers you cited (if possible)
- send a PDF version of the thesis to your supervisor via e-mail.

## Pre-Submission Checklist

- [ ] Formulas are indexed.
- [ ] For all (Regression) models, the model formulas are provided.
- [ ] Every figure and table is referenced and described in the text.
- [ ] Choose appropriate formatting of numbers that does not suggest unjustified levels of accuracy (e.g., response times of employees in ms).
- [ ] If feasible, arrange rows/columns/bars in an order of numerical progression; always indicate what numbers are shown, including units (axes, legends).
- [ ] Provide complete reference information in the reference section (e.g., including Authors, Title, Journal, Volume, Issue).
- [ ] Claims of significance require appropriate statistical tests.
- [ ] The writing style should be objective and neutral, in particular in the related work, methodology, and results sections.

## References and Citing

Citations are managed using [JabRef](http://www.jabref.org/) ([Wikipedia article](https://en.wikipedia.org/wiki/JabRef)) with a [BibTex file](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/references.bib). In Microsoft Word, the Plugin [Docear4Word](http://www.docear.org/software/add-ons/docear4word/download/) is used to cite directly from the [BibTex file](https://github.com/WinforUniRegensburg/thesis_seminar_template/blob/master/references.bib). The [MISQ author-year citation style](https://misq.org/manuscript-guidelines) is the citation style to be used. For example, indirect citations e.g., (Webster and Watson 2002) or direct citations e.g., Webster and Watson (2002). For further guidelines regarding the reference section refer to the above link.

## Latex Environment

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

Make sure to use UTF-8 as an encoding (in particular when the tex-template is edited in different environments/operating systems). Consider using a version-control system ([git](https://git-scm.com/)) and an appropriate [.gitignore](https://github.com/github/gitignore/blob/master/TeX.gitignore) file.


# References

Webster, J., & Watson, R. T. (2002). Analyzing the past to prepare for the future: Writing a literature review. MIS quarterly, xiii-xxiii.
