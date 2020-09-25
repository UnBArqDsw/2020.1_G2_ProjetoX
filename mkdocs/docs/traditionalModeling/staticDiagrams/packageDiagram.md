<span id="dc"></span>
# **<a href="#dc">Package Diagrams</a>**

The Package Diagram, defined by the UML, describes the packages or pieces of the system divided into logical groupings showing the dependencies between them. This diagram is widely used to illustrate the architecture of a system showing the grouping of its classes.

## Frontend

The frontend will be built using React, a frontend framework in JavaScript language. Below you can view two frontend package diagrams.

[Package diagram General Strcuture - version 2](./images/structureV2.png)  
[Package diagram General Strcuture - version 1](./images/structure.png)  
[Package diagram Pages and Components - version 1](./images/pages_components.png)


## Backend

The back-end will be built by services made with the Express microframework in NodeJs, using JavaScript language and Hexagonal architecture. Each of the microservices has a corresponding diagram.

### Overview

At the image below, it is possible to see two main packages, 'Users' and 'Database'. The other packages have dependency relation with the main packages.

- [Version 1](./images/package_diagram.png)
- [Version 2](./images/package_diagram2.png)

## Tracking Requirements

| Source | Destiny |
|------|-------|
|  [Prototype](../../../base/designSprint/prototype.md) | General Structure, Pages and Components |
| [Backlog - User](../../../base/requirements/modeling/backlogEpics/dataCreation.md) [Prototype](../../../base/designSprint/prototype.md) | General Structure, Pages and Components |
| [BrainStorm](../../../base/requirements/elicitation/brainstorm/)  | General Structure, Pages and Components |


---
## References
---


- **[Moodle]** Serrano, Milene. Vídeo Aula : Modelagem, Diagrama de Classe, Dependência & Associação, Classe Concreta & Abstrata & Sobrescrita & Sobrecarga, Agregação & Composição, Herança & Realização
- **[Moodle]** Serrano, Milene. Vídeo Aula : Diagrama de Pacotes
- **[WebSite]** <a href="https://www.uml-diagrams.org/package-diagrams-overview.html">UML site</a>
- **[WebSite]** <a href="https://homepages.dcc.ufmg.br/~amendes/GlossarioUML/glossario/conteudo/pacotes/diagrama_de_pacotes.htm">Diagrama de Pacotes</a>


---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 21/09/2020 | Lorrany Azevedo | Document creation | 0.1 |
| 22/09/2020 | Guilherme and Lorrany Azevedo | Adding description and diagrams | 0.2 |
| 25/09/2020 | Guilherme and Lorrany Azevedo | Adding tracking | 0.3 |
| 24/09/2020 | Mikhaelle Bueno| Adding Paper Service diagram | 0.3 |
| 25/09/2020 | Vitor Meireles | Add backend diagram | 0.4 |
