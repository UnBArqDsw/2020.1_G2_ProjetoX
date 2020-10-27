# Emerging Pattern Desing

Emerging design patterns are those associated with the latest platforms and technologies. In our project several of them were implemented and will be discussed in this section.

### List:

#### Back-end

* **S.O.L.I.D**

  - **S** - Single-responsiblity principle;
  - **O** - Open-closed principle;
  - **L** - Liskov substitution principle;
  - **I** - Interface segregation principle;
  - **D** - Dependency Inversion Principle;

* **Dependency injection**

## S.O.L.I.D

> **S.O.L.I.D** is an acronym for the first five object-oriented design (OOD) principles by Robert C. Martin, popularly known as Uncle Bob.

These principles, when combined together, make it easy for a programmer to develop software that are easy to maintain and extend. They also make it easy for developers to avoid code smells, easily refactor code, and are also a part of the agile or adaptive software development.

Let’s look at each principle individually to understand why S.O.L.I.D can help make us better developers.

### Single-Responsibility Principle
S.R.P for short - this principle states that:

> A class should have one and only one reason to change, meaning that a class should have only one job.

![single_responsibility](./images/single_responsibility_principle-VerifyIfUserAlreadyExistsMiddleware.png)

### Open-Closed Principle

> Objects or entities should be open for extension, but closed for modification.

![open_closed](./images/open_closed_principle-BadRequestError.png)

### Liskov Substitution Principle

> Let q(x) be a property provable about objects of x of type T. Then q(y) should be provable for objects y of type S where S is a subtype of T.

All this is stating is that every subclass/derived class should be substitutable for their base/parent class.

![liskov](./images/liskov_substitution_principle-CreateUserAdapterDb.png)

---
## References
---

- **[WebSite]** <a href="-">-</a>

- **[-]** -


---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Document creation | 0.1 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Intro | 0.2 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | S.O.L.I.D | 0.3 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Single-responsibility Principle | 0.4 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Open-closed Principle | 0.5 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Liskov substitution principle | 0.6 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Interface segregation principle | 0.7 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Dependency Inversion principle | 0.8 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | Dependency injection | 0.9 |
| 10/26/2020 | Gabriel Filipe, Guilherme Deusdará | References | 1.0 |
