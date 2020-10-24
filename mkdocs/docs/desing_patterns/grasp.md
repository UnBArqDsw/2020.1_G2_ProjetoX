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

In our project we used several of the patterns mentioned above, below explain why we use these patterns and show where they were used in our project code. 

<span id="creator"></span>
## **<a href="#Creator">Creators</a>**

As has already been said, creators are the classes responsible for instantiating objects, instantiating objects can be a complicated task and creators are used when some factors occur, one of these factors is when aggregation between two classes occurs.

Put creators example: controller, signupcontroller, signupcontrollerfactory

<span id="sp"></span>
## **<a href="#sp">Information Expert</a>**

Experts are responsible for delegating responsibilities to classes, such as methods, instilling objects, etc. In other words, creators are specialists in instantiating objects. In our code the specialties are.

Put experts example:

<span id="lc"></span>
## **<a href="#lc">Low Coupling</a>**

As it has also been explained, the concept of low coupling is a very important concept when it comes to maintaining the quality of the software, it allows us greater manageability since the classes seek to be as independent as possible. Grasp patterns alone, when properly used, already reduce our coupling, but we can further decrease this coupling using the gof patterns that will be explained in the documents below.


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
| 10/23/2020 | Lorrany Azevedo, Ygor Galeno | Add creators, information expert and low coupling definitions | 0.3 |