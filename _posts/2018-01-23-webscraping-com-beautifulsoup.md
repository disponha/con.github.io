---
layout: post
title: Webscraping com BeautifulSoup
feature-img: "assets/img/img01.jpg"
thumbnail: "assets/img/img01.jpg"
---

## Iniciando 

Aqui está um documento _HTML_ que vou usar como exemplo ao longo deste documento. Faz parte de uma história de Alice no País das Maravilhas:



Executar o documento "três irmãs" através do Beautiful Soup nos dá um ``BeautifulSoup`` objeto, que representa o documento como uma estrutura de dados aninhada:



Aqui estão algumas maneiras simples de navegar naquela estrutura de dados:



Uma tarefa comum é extrair todos os URLs encontrados nas tags ``<a>`` de uma página:


Outra tarefa comum é extrair todo o texto de uma página: