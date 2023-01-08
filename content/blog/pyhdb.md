---
title: "New article about *pyHDB* tool! / Novo artigo sobre a ferramenta *pyHDB*"
date: 2023-01-08T15:25:04-00:00
toc: false
images: ../static/img/pyhdb.png
tags:
  - publications
---
## English version

On the last day of 2022, the new issue of the [História da Historiografia](https://www.historiadahistoriografia.com.br/revista/issue/view/45) journal came out with an article of mine called ["pyHDB - Ferramenta Heurística para a Hemeroteca Digital Brasileira: utilizando técnicas de web scraping para a pesquisa em História"](https://doi.org/10.15848/hh.v15i40.1904).

It is my darling!

In the article, I present pyHDB, a methodological support tool for research in the [Brazilian Digital Newspaper Library](http://memoria.bn.br/hdb/periodico.aspx), of the National Library. I analyze its relationship with the theory, methodology, and epistemology of history, focusing on the selection, collection, organization, and criticism of sources.

pyHDB is a command-line program written in Python that generates reports, spreadsheets, and data sets from the results of the Brazilian Digital Newspaper Library. The Local, Period, and Term parameters of the search are defined by the user:

![parameters](../static/img/pyhdb_par.png)

Then, pyHDB searches and beggins to gather and organize the data.

![scrape](../static/img/pyhdb_scrape.png)

The parameters, time and date of the search, results, number of occurrences, number of pages of each collection, frequency of occurrences per page, information of each occurrence, error reports, and the download of the image when legally allowed are recorded.

Here is an example of the data collected and organized by pyHDB in a .csv file:

![csv](../static/img/pyhdb_sheet.jpeg)

This is the directory structure created by pyHDB:

![directories](../static/img/pyhdb_dir.png)

And the downloaded images:

![images](../static/img/pyhdb_imgs.png)

One of the examples used in the article was Monteiro Lopes. The data confirms the intense debate around the elections of the black lawyer in 1903 for the municipal council of Rio de Janeiro and in 1909 as a federal deputy.

![Monteiro Lopes](../static/img/pyhdb_graph.jpeg)

To top it all off, Pedro Silveira's amazing *ad hoc* review on the article was also published in the issue. It is not just a reading of my article but a sophisticated reflection on historiographical practice in the digital age.

I thank the members of LabhdUfba, especially Gabriel Andrade, for the tips and help with Python, and its coordinator, Leonardo F. Nascimento, for the partnership, reading, and for suggesting the name pyHDB. I thank Yaci Farias and Luara Santos for reading and comments during the writing of the article. I thank Ana Carolina Veloso and Priscila Valverde Silveira for the work as undergraduate students between 2020 and 2021 at History course of the UNILAB, Bahia. I would like to acknowledge Alexandra Elbakyan, the creator of Sci-Hub, for her struggle for the open science. I thank the members of the editorial board of the journal for the support and  the anonymous reviewers for the valuable suggestions.

All documentation is available on the [pyHDB](https://ericbrasiln.github.io/pyHDB/) page.

*Data set* used in the article: https://doi.org/10.5281/zenodo.5699000

Interactive graphs, images, and scripts: https://ericbrasiln.github.io/analise_pyHDB/

If you have any questions, please contact me or open an issue on [Github](https://github.com/ericbrasiln/pyHDB/issues).

---

## Versão em português

No último dia de 2022 saiu novo número da Revista [História da Historiografia](https://www.historiadahistoriografia.com.br/revista/issue/view/45) com um artigo meu chamado ["pyHDB - Ferramenta Heurística para a Hemeroteca Digital Brasileira: utilizando técnicas de web scraping para a pesquisa em História"](https://doi.org/10.15848/hh.v15i40.1904). 

É meu xodó!

No artigo apresento a pyHDB, ferramenta de suporte metodológico para a pesquisa na [Hemeroteca Digital Brasileira](http://memoria.bn.br/hdb/periodico.aspx), da Biblioteca Nacional. Analiso sua relação com teoria, metodologia e epistemologia da história, focando na seleção, coleta, organização e critica das fontes.

A pyHDB é um programa em linha de comando escrito em Python que gera relatórios, planilhas e data sets a partir dos resultados da Hemeroteca Digital Brasileira. Os parâmetros de Local, Período e Termo da busca são definidos pelo usuário e a pyHDB busca e inicia o processo de coleta de informações.

![parameters](../static/img/pyhdb_par.png)

São registrados os parâmetros, a hora e data da busca, os resultados, o nº de ocorrências, o nº de páginas de cada acervo, a frequência de ocorrências por páginas, as informações de cada ocorrência, relatórios de erros e o download da imagem quando legalmente permitido.

![scrape](../static/img/pyhdb_scrape.png)

Veja um exemplo dos dados coletados e organizados pela pyHDB em um arquivo .csv:

![csv](../static/img/pyhdb_sheet.jpeg)

Aqui a estrutura de diretórios criada pela pyHDB:

![diretórios](../static/img/pyhdb_dir.png)

E as imagens baixadas:

![imagens](../static/img/pyhdb_imgs.png)

Um dos exemplos utilizados no artigo foi Monteiro Lopes. Os dados confirmam o intenso debate em torno das eleições do advogado negro em 1903 para o conselho municipal do RJ e em 1909 como deputado federal.

![Monteiro Lopes](../static/img/pyhdb_graph.jpeg)

Pra fechar com chave de ouro, [o parecer incrível do Pedro Silveira sobre o artigo também foi publicado na revista](https://www.historiadahistoriografia.com.br/revista/article/view/2071). Não é apenas uma leitura do meu artigo, mas uma reflexão sofisticada sobre o próprio fazer historiográfico na era digital.

Agradeço aos membros do LabhdUfba, especialmente a Gabriel Andrade, pelas dicas e ajuda com Python, e ao seu coordenador, Leonardo F. Nascimento, pela parceria, leitura e por ter sugerido o nome pyHDB. Agradeço a Yaci Farias e Luara Santos pela leitura e comentários durante a escrita do artigo. Agradeço a Ana Carolina Veloso e Priscila Valverde Silveira pelo trabalho desenvolvido como bolsistas de iniciação científica no curso de História da Unilab, campus dos Malês ao longo de 2020 e 2021. Agradeço a Alexandra Elbakyan por sua atuação na ciência livre. Gostaria de agradecer aos membros do conselho editorial da revista pelo apoio e aos revisores anônimos pelas valiosas sugestões.

Toda a documentação está disponível na página da [pyHDB](https://ericbrasiln.github.io/pyHDB/).

*Data set* utilizados no artigo: https://doi.org/10.5281/zenodo.5699000

Gráficos interativos, imagens e scripts: https://ericbrasiln.github.io/analise_pyHDB/

Qualquer questão entrem em contato ou abram uma issue lá no [Github](https://github.com/ericbrasiln/pyHDB/issues).