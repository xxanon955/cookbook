# Paper proceedings archive officer

Main roles:

1. Archive the proceedings on nime.org and Zenodo
2. Index the papers in DBLP, ACM DL, Scopus, and others

The paper proceedings archive officer will work closely with each year's [Paper Chair](../Chairs/paper_chair.md).

Officers:

- Benedikte Wallace (Zenodo lead)
- Andrew McPherson
- Balandino Di Donato


## General info about the proceedings

### Name of the proceedings

Before 2011 the proceedings title (often) also included the location and/or the date of the conference. This is no longer possible with the ISSN numbers, so then the location and date should be listed in a subheader, e.g.:

   Proceedings of the International Conference on New Interfaces for Musical Expression
   30 May - 1 June 2011, Oslo, Norway

### ISSN

From 2011 we acquired ISSN numbers for the NIME proceedings. Since ISSN registers publication series, they also require that the title of each publication stays the same. We currently have 3 ISSN numbers, for different publication types:

* Print: ISSN 2220-4792 = Proceedings of the International Conference on New Interfaces for Musical Expression
* Online: ISSN 2220-4806 = Proceedings of the International Conference on New Interfaces for Musical Expression
* CD-ROM/USB: ISSN 2220-4814 = Proceedings of the International Conference on New Interfaces for Musical Expression

### ISBN

It is possible (and advisable) to also acquire ISBN numbers for the proceedings. This can usually be done through the library of the host institution, which probably already has a range of possible ISBN numbers to choose from. There is no problem having both ISBN and ISSN numbers for the same publication. The ISSN number represents the conference series, while the ISBN number represents the specific publication.


## Upload to Zenodo

NIME has decided to use Zenodo for archival of papers. All previous NIME papers was uploaded to Zenodo in 2018 by Benedikte Wallace. This was done using a script based on [this script](https://github.com/darvasd/upload-to-zenodo). More info about the procedure on the [Zenodo developer site (REST API)](https://developers.zenodo.org/?python#rest-api).

Todo:

- Add DOIs from each Zenodo paper to the BibTeX entries, so that we can link to Zenodo from the archive on nime.org
- Work with Music Proceedings Officers to make a unified archive


## Indexing

Indexing of the proceedings is important for the visibility of the papers. We will work more on improving this in the future.

### Indexing in Google Scholar

The [papercite](https://wordpress.org/plugins/papercite/) plugin used on nime.org contains metadata information that is indexed by Google Scholar. So nothing else should be needed than getting the papers on nime.org.

It may be worth checking the latest [Google description](https://scholar.google.com/intl/en/scholar/inclusion.html) on how to make a cite searchable for indexing in Scholar.


### Indexing in DBLP

NIME indexing in [DBLP](http://www.informatik.uni-trier.de/~ley/db/conf/nime/index.html) seems to be up-to-date: 2001--2019.

Here is [info](https://dblp.uni-trier.de/faq/How+can+I+submit+meta+data+for+a+complete+journal+or+conference.html) on how to submit to DBLP.

So far, none of the NIME proceedings have _references_ included in the DBLP, perhaps this could be arranged through adding things to the OpenCitations.net database, but not sure if that is actually possible [arxiv:1906.11964](https://arxiv.org/abs/1906.11964).

### Indexing in ACM

The same is true for ACM, with which we have not been able to index for several years either. This is important to work on, hence the need for someone to work on this in particular.

There is some discussion of ACM DL indexing on the [academia stackexchange](https://academia.stackexchange.com/questions/90832/do-non-acm-events-conferences-publish-index-their-final-proceedings-in-the-acm) that suggests that only a "small number" of conferences have proceedings indexed (as opposed to published) on the ACM DL. A current question is: is this actually possible or supported by ACM?

### Scopus

A request to register NIME in Scopus ([Engineering Village](https://suggestor.ei.engineeringvillage.com/faq/index)) was sent in June 2018. In June 2019 we got a reply that they are looking into the case. In March 2020 we were informed that they will include NIME in Scopus. Waiting for it to show up.
