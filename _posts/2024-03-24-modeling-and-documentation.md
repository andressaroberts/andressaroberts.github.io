---
title: Modeling and documenting system requirements and solutions
date: 2025-03-24 11:33:00 +0800
categories: [documentation]
tags: [UML, DRAW.IO, PLATUML, USECASE]
---

## 🇬🇧 Modeling and documenting system requirements and solutions
Documentation is a crucial part of software development, and one of the first steps is modeling the system requirements. For **Denotas**, I started by creating a use case diagram to visualize the interactions between the user and the system.

The use case diagram is a powerful tool for understanding the functional requirements of the system. It helped me identify the main actors (in this case, the "Reader") and the use cases (functionalities) of **Denotas**. It is attached at the end of the post and was created with the help of [Draw.io](https://app.diagrams.net/) and [PlantUML](https://www.plantuml.com/).

Through the diagram I was able to visualize the following interactions:

- **Register**: Creation of a new user account.
- **Login**: Access to the system by a registered user.
- **Import HTML**: Import of notes from Kindle. The platform provides an HTML document that I needed to analyze and map the available information.
- **Review import**: Allows the user to add tags, classify excerpts as notes, or exclude parts of the import during the HTML import process.
- **Create note**: Addition of notes directly on the site.
- **Edit note**: Modification of existing notes.
- **Delete note**: Removal of notes from the system.
- **Add tag**: Addition of tags to notes.
- **Group information**: Grouping of notes by title or author.
- **Filter by Tag**: Filtering of notes by tags.
- **View note**: Viewing of notes created and/or imported into the system.
- **Search**: Search for notes, whether by content, title, or author.
- **Manage tags**: Management of tags (create, edit, delete).

The diagram also allowed me to visualize the relationships between the use cases, such as the login dependency for most functionalities, the extend relationship between _Register_ and _Login_ and the include relationship between _Import HTML_ and _Review Import._

This first step of documentation helped me have a clear view of the project scope and plan the next development steps. In future posts, I intend to share more about the **Denotas** documentation process, including some other diagrams.

![Use Case](/assets/casousoen.svg){: width="500" height="500" }
_Use Case of the System (modeled in Draw.io)_

## 🇧🇷 Modelando e documentando requisitos e soluções do sistema
A documentação é uma parte crucial do desenvolvimento de software e uma das primeiras etapas é modelar os requisitos do sistema. Para o **Denotas**, comecei criando um diagrama de caso de uso para visualizar as interações entre o usuário e o sistema.

O diagrama de caso de uso é uma ferramenta poderosa para entender os requisitos funcionais do sistema. Ele me ajudou a identificar os principais atores (no caso, o "Leitor") e os casos de uso (funcionalidades) do **Denotas**. Ele está anexado no final do post e foi feito com a ajuda do [Draw.io](https://app.diagrams.net/) e do [PlantUML](https://www.plantuml.com/).

Através do diagrama pude visualizar as seguintes interações:

- **Cadastrar**: Criação de uma nova conta de usuário.
- **Logar**: Acesso ao sistema por um usuário já cadastrado.
- **Importar HTML**: Importação de anotações do Kindle. No caso, a plataforma fornece um documento HTML que precisei analisar e mapear as informações disponibilizadas.
- **Revisar importação**: Permite que o usuário adicione tags, classifique trechos como notas ou exclua trechos durante o processo de importação do HTML.
- **Criar nota**: Adição de anotações diretamente no site.
- **Editar nota**: Modificação de anotações existentes.
- **Excluir nota**: Remoção de anotações do sistema.
- **Adicionar tag**: Adição de tags às anotações.
- **Agrupar informações**: Agrupamento de anotações por título ou autor.
- **Filtrar por tag**: Filtro de anotações por tags.
- **Visualizar nota**: Visualização das anotações criadas e/ou importadas no sistema.
- **Buscar**: Busca por anotações, seja pelo conteúdo, título ou autor.
- **Gerenciar tags**: Gerenciamento de tags (criar, editar, excluir).

O diagrama também me permitiu confirmar as relações entre os casos de uso, como a dependência de login para a maioria das funcionalidades além da relação de extensão entre _Cadastrar_ e _Logar_ e da relação de inclusão entre _Importar HTML_ e _Revisar importação_.

Esta primeira etapa de documentação me ajudou a ter uma visão clara do escopo do projeto e no planejamento das próximas etapas do desenvolvimento. Nos próximos posts, pretendo compartilhar mais sobre o processo de documentação do **Denotas**, incluindo alguns outros diagramas.

![Caso de uso](/assets/casousopt.svg){: width="500" height="500" }
_Caso de Uso do Sistema (modelado no Draw.io)_