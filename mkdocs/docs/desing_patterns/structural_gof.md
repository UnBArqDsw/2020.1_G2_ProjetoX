<span id="sp"></span>
# **<a href="#sp">Structural Patterns</a>**

The structural gofs patterns are concerned with how objects will be organized to form larger structures, these patterns aim to decrease the coupling between these objects. Below we put a small definition of the existing standards and we will explain better those used in the project.

- **Adapter**: Allow an object to be replaced by another that despite performing the same task has a different interface
- **Bridge**:  Separate one abstraction of your representation, so that both may vary and produce types of different objects.
- **Composite**: Group objects that are part of a part-whole relationship in order to treat them without distinction. polimorfismo todo-parte
- **Decorator**: Add functionality a an object dynamically
- **Facade**: Provide a simplified interface capable of centralizing the use of several interfaces of a system.
- **Flyweight**: Efficiently share objects that are used in large quantities.
- **Proxy**: Control calls to an object through another object on the same interface.


<span id="adp"></span>
## <a href="#adp">Adapter</a>

The adapter design pattern as the definition already tells us, allows us to replace one object with another without complications with our client, it is characteristic of objects with similar behaviors due to the fact that we use polymorphism to overwrite the behavior of these objects. A great use of the adapter is to allow us to change the behavior of a given object without touching its code, avoiding, for example, a new version of it. Below is an adapter implementation of our project:

Código de adapter

---
## References
---

- **[Moodle]** Serrano, Milene. Vídeo Aula : Gofs Estruturais


---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 10/23/2020 | Lorrany Azevedo | Document creation | 0.1 |
| 10/25/2020 | Lorrany Azevedo, Gabriel Fillipe | Add adapter concept | 0.1 |