<span id="grasp"></span>
# **<a href="#grasp">General Responsibility Assignment Software Patterns</a>**


GRASP standards are guidelines that assign responsibility to classes and objects in object-oriented designs. The following standards are part of GRASP:

- **Creators**: Class responsible for instantiating objects.
- **Information Expert**: Assigns responsibilities to specialist classes. 
- **Low Coupling**: Coupling is a measure of how strong two elements are connected, that is, how dependent they are on each other. Therefore, the more independent the elements are, the better, as this makes the code more maintainable and reusable.
- **High coeshion**: Elements that are created with a well-defined purpose and are limited to implementing only what they actually need to do. They are objects with highly related and highly focused responsibilities, having a high cohesion is almost synonymous with a code with low coupling.
- **Polymorphism**: Also known as superscript, it is a concept where child classes override superclass methods, they are methods that will contain the same signature but will have different implementations.
- **Protected Variations**: It protects elements from variations of other objects. For this, polymorphism and the use of interfaces are used to help maintain the stability of the element.
- **Pure Fabrication**: Classes created from a project need.
- **Controllers**: Assigns responsibility for handling system events for classes other than UI, it delegates the work that needs to be done to other objects.
- **Indirection**: Mediating object between two elements, this makes the coupling smaller. 


---
## References
---

- **[WebSite]** <a href="https://www.uml-diagrams.org/package-diagrams-overview.html">UML site</a>

- **[Moodle]** Serrano, Milene. Vídeo Aula : GRASP


---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 10/23/2020 | Lorrany Azevedo | Document creation | 0.1 |
| 10/23/2020 | Lorrany Azevedo, Gabriel Filipe | Add grasp concept | 0.2 |