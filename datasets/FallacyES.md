# FallacyES files description
This document provides a description of the FallacyES ``csv`` files, which collects examples of prototypical and spontaneous fallacies in Spanish, as presented in the paper *"Detección y clasificación de falacias prototípicas y espontáneas en español"*.

## FallacyES-prototypical.csv
Each line contains an example of a prototypical fallacy and, in some cases, a non-fallacy rephrasing of the previous example. 

Columns:
* ``label``: the type of fallacy 
* ``fallacy_example``: an example of fallacy of that type
* ``non-fallacy_example``: a non-fallacy rephrasing of the fallacy example (missing in some instances).

Types of fallacies (between parentheses, the name in Spanish used in the paper):
* faulty generalization (generalización apresurada)
* false causality (falsa causalidad)
* circular reasoning (razonamiento circular)
* ad populum (ad populum)
* ad hominem (ad hominem)
* deductive fallacy (deducción errónea)
* appeal to emotion (apelación a las emociones)
* false dilemma (falso dilema)
* fallacy of extension (hombre de paja)
* fallacy of relevance (pista falsa)
* fallacy of credibility (credibilidad)
* intentional (intencional)


## FallacyES-spontaneous.csv
Each line contains an example of a spontaneous fallacy or a non-fallacy example.

Columns:
* ``label``: the type of fallacy, or ``non-fallacy`` if it is a non-fallacy example. 
* ``text``: an example of fallacy or non-fallacy.
* ``source_link``: the link to the *old.meneame.net* source page the example was extracted from.
* ``news_title``: the title of the news being commented.
* ``news_summary``: the summary of the news being commented.
* ``news_link``: the link to the news being commented. 

Types of fallacies (between parentheses, the name in Spanish used in the paper):
* faulty generalization (generalización apresurada)
* ad populum (ad populum)
* ad hominem (ad hominem)
* deductive fallacy (deducción errónea)
* appeal to emotion (apelación a las emociones)
* false dilemma (falso dilema)
* fallacy of extension (hombre de paja)
* fallacy of credibility (credibilidad)
