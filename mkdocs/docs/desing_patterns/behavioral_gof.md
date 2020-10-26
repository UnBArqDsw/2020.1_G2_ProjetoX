<span id="sp"></span>
# **<a href="#sp">Behavioral Patterns</a>**

Os padrões comportamentais são padrões voltados para a alterações no nível de comportamento de objetos. Neste documento nós daremos um breve overview sobre os padrões existentes e iremos explicar mais afundo os padrões que utilizamos no nosso projeto.

- **Command**: Control calls to a specific component, modeling each request as an object. Allow operations to be undone or recorded.
- **Iterator**: Provide an efficient way to cycle through the elements of a collection sequentially, without exposing the internal structure of the collection.
- **Mediator**: Reduce the number of "connections" between objects by introducing a mediator, who will carry out all communication.
- **Observer**: Define an efficient mechanism to react to changes made to certain objects.
- **State**: Change the behavior of a given object according to the state it is in.
- **Strategy**: Allow, in a simple way, the variation of the algorithms used in the
solving a particular problem.
- **Template Methods**: Define the order in which certain steps must be taken to solve a problem and allow these steps to be carried out in different ways depending on the situation.
- **Visitor**: Allow specific updates to a collection of objects according to the particular type of each updated object.
- **Memento**: It allows to store the internal state of an object at a certain time, so that it is possible to return it to this state, without causing problems with the encapsulation. A class is responsible for saving the state of the desired object; while another class is responsible for storing all these copies.
- **Chain of Responsability**: Avoid dependency between a receiving object and a requesting object. The base maintains a pointer as "next". Each derived class implements its own contribution to handle the request.


<span id="adp"></span>
## <a href="#adp">Strategy</a>

The strategy is a behavioral design pattern that allows us to define a family of algorithms, make each algorithm become a class and make the objects of those classes interchangeable. This pattern helps us to encapsulate decision-making algorithms at runtime, this means that instead of implementing an algorithm with all pre-defined decision-making, our code can receive instructions at runtime and from choose which strategy he will follow.

![](./images/)


File: <a href="" target="blank"></a>


<span id="OB"></span>
### <a href="#OB">Objectives and problems solved</a>

Reunir com o grupo

<span id="dec"></span>
## <a href="#dec">Chain of Resposability</a>

<span id="OB"></span>
### <a href="#OB">Objectives and problems solved</a>


---
## References
---

- **[Moodle]** Serrano, Milene. Vídeo Aula : Gofs Estruturais
- **[WebSite]** <a href="deco">https://refactoring.guru/design-patterns/decorator</a>


---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 10/23/2020 | Lorrany Azevedo | Document creation | 0.1 |
| 10/26/2020 | Lorrany Azevedo| Add document structure | 0.2 |
| 10/26/2020 | Lorrany Azevedo, Ygor Galeno | Add strategy definition | 0.3 |
| 10/26/2020 | Lorrany Azevedo, Gabriel Fillipe | Add behavioral patterns definition | 0.4 |