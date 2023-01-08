---
author:
  name: "Eric Brasil"
title: New article about pyHDB tool!
date: 2023-01-08
linktitle: New article about pyHDB tool
toc: false
draft: false
type: post
images:
tags:
  - publications
  - digital tools
---

{{< image src="/img/pyhdb.png" alt="logo pyHDB" position="left" style="border-radius: 8px;" >}}

On the last day of 2022, the new issue of the [História da Historiografia](https://www.historiadahistoriografia.com.br/revista/issue/view/45) journal came out with an article of mine called ["pyHDB - Ferramenta Heurística para a Hemeroteca Digital Brasileira: utilizando técnicas de web scraping para a pesquisa em História"](https://doi.org/10.15848/hh.v15i40.1904).

It is my darling!

In the article, I present pyHDB, a methodological support tool for research in the [Brazilian Digital Newspaper Library](http://memoria.bn.br/hdb/periodico.aspx), of the National Library. I analyze its relationship with the theory, methodology, and epistemology of history, focusing on the selection, collection, organization, and criticism of sources.

pyHDB is a command-line program written in Python that generates reports, spreadsheets, and data sets from the results of the Brazilian Digital Newspaper Library. The Local, Period, and Term parameters of the search are defined by the user:

{{< image src="/img/pyhdb_par.png" alt="parameters" position="left" style="border-radius: 8px;" >}}

Then, pyHDB searches and beggins to gather and organize the data.

{{< image src="/img/pyhdb_scrape.png" alt="scrape" position="left" style="border-radius: 8px;" >}}

The parameters, time and date of the search, results, number of occurrences, number of pages of each collection, frequency of occurrences per page, information of each occurrence, error reports, and the download of the image when legally allowed are recorded.

Here is an example of the data collected and organized by pyHDB in a .csv file:

{{< image src="/img/pyhdb_sheet.jpeg" alt="csv" position="left" style="border-radius: 8px;" >}}

This is the directory structure created by pyHDB:

{{< image src="/img/pyhdb_dir.png" alt="directories" position="left" style="border-radius: 8px;" >}}

And the downloaded images:

{{< image src="/img/pyhdb_imgs.png" alt="images" position="left" style="border-radius: 8px;" >}}

One of the examples used in the article was Monteiro Lopes. The data confirms the intense debate around the elections of the black lawyer in 1903 for the municipal council of Rio de Janeiro and in 1909 as a federal deputy.

{{< image src="/img/pyhdb_graph.jpeg" alt="Monteiro Lopes" position="left" style="border-radius: 8px;" >}}

To top it all off, Pedro Silveira's amazing *ad hoc* review on the article was also published in the issue. It is not just a reading of my article but a sophisticated reflection on historiographical practice in the digital age.

I thank the members of LabhdUfba, especially Gabriel Andrade, for the tips and help with Python, and its coordinator, Leonardo F. Nascimento, for the partnership, reading, and for suggesting the name pyHDB. I thank Yaci Farias and Luara Santos for reading and comments during the writing of the article. I thank Ana Carolina Veloso and Priscila Valverde Silveira for the work as undergraduate students between 2020 and 2021 at History course of the UNILAB, Bahia. I would like to acknowledge Alexandra Elbakyan, the creator of Sci-Hub, for her struggle for the open science. I thank the members of the editorial board of the journal for the support and  the anonymous reviewers for the valuable suggestions.

All documentation is available on the [pyHDB](https://ericbrasiln.github.io/pyHDB/) page.

*Data set* used in the article: https://doi.org/10.5281/zenodo.5699000

Interactive graphs, images, and scripts: https://ericbrasiln.github.io/analise_pyHDB/

If you have any questions, please contact me or open an issue on [Github](https://github.com/ericbrasiln/pyHDB/issues).