# BDSW_Wordnet

Progetto sviluppato durante il corso di Big Data e Tecnologie Semantiche (UniSa - DIEM - Anno accademico 2019/2020)

Obiettivo del progetto: progettazione ed implementazione di un reader di testo intelligente che attraverso l’utilizzo di WordNet e WordNet-Domain aiuti l’utente nella lettura e nella comprensione di un testo. Sono previste tre funzionalità di seguito brevemente descritte con l’aiuto di uno schema ad alto livello di astrazione, ulteriori dettagli sono presenti nella relazione di progetto.

#### 1) Unambiguous Definition
Permette di ottenere il significato di una parola del testo, in coerenza con il contesto della frase in cui si trova la parola stessa.

![](https://github.com/enricosammarco/BDSW_Wordnet/blob/main/imgReadMe/Immagine1.png)

#### 2) Relation finder
Permette di ottenere una possibile relazione tra due parole del testo. In particolare, è possibile trovare tutte le relazioni tra le due parole, oppure solo la relazione più semplice (il concetto di semplicità verrà trattato in seguito).

![](https://github.com/enricosammarco/BDSW_Wordnet/blob/main/imgReadMe/Immagine2.png)

#### 3) Context relation finder
Permette di ottenere la relazione più semplice tra due parole considerando il contesto del paragrafo nel quale esse si trovano, e quindi  il significato specifico delle parole in quel contesto.

![](https://github.com/enricosammarco/BDSW_Wordnet/blob/main/imgReadMe/Immagine3.png)

#### Implementzione
L'applicazione è stata implementata, sia sul lato front-end che sul lato back-end, attraverso il linguaggio di programmazione ad alto livello Python. In particolare per interfacciarsi con il Thesaurus Wordnet sono state utilizzate le librerie 'ntlk' e 'spacy'.
