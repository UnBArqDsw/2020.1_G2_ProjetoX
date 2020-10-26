# Tests and Continuous Integrations

Test-driven development is a software development practice advocated in XP and consists of the practice of test-driven development and in TCLDL we inherit this from DDD (domain-driven desing).

Using TDD we program the tests in the extension codes _.Spec.ts_ in order to know the type of result we would like to obtain, with that done the extension code _.Ts_ is done.

As expected from TDD, the project code does unit tests to check every minor part of the system that is decoupled, evaluating the results of classes and methods.


## Jest

The technology used for _Js_ and _Ts_ tests is Jest to mitigate redundancies and couplings in a backend with node and express, which are some of our technologies. The Jest tool was choosen because it`s fast safe and easy mocking.

- [Tests directory example](./images/tests_folder.png)

- [Jest test file](./images/jest.png)
- [File](./images/jest2.png)


## Commitlint

Based on a commits convention, it is used to validate messages with relatively little red tape. This is useful for standardizing team commits. 

- [Lint](./images/lint_rc.png)

- [Lint Staged](./images/lint_staged_rc.png)

- [Lint Ignore](./images/lint_ignore.png)

### Husky hook

Husky supports Commitlint and is being used to lint commit messages.

- [Husky](./images/husky_rc.png)


## Github actions

GitHub Actions is the tool of choice for automating and executing workflows and software development, including CI / CD.

The project has a Node.js base and database and test integration is managed by the GitHub Actions configuration files.

- [Pipeline default](./images/pipeline_default.png)

- [Pipeline Development](./images/pipeline_development.png)

- [Pipeline Master](./images/pipeline_master.png)


## Code Quality && Coverage 100%

This is used as metric to put in numbers or letters how good the code is being constructered.

- [Coverage](./images/code_quality.png)

### Code Climate

Codeclimate is a static code quality analysis tool. This tool scans the code for duplication problems, code smells and other miscellaneous problems, thus raising the quality of the code. This is useful for avoid mistakes that makes code clean.

- [Code climate](./images/code_climate.png)


---
## References
---
- **[WebSite]** <a href="https://jestjs.io/">Jest site</a>
- **[WebSite]** <a href="https://www.conventionalcommits.org/en/v1.0.0/">Conventional commits site</a>
- **[WebSite]** <a href="https://codeclimate.com/">CodeClimate site</a>
- **[WebSite]** <a href="https://typicode.github.io/husky/#/">Husky doc site</a>
---

## Document Versioning

| Date | Author(s) | Description | Version |
|------|-------|-----------|--------|
| 10/25/2020 | Vitor Meireles | Document creation | 0.1 |
| 10/25/2020 | Vitor Meireles | Adds concepts  | 1.0 |
| 10/26/2020 | Vitor Meireles | Adds images  | 1.1 |
| 10/26/2020 | Vitor Meireles | Adds reference  | 1.2 |
| 10/26/2020 | Vitor Meireles | Adds code climate  | 1.3 |
| 10/26/2020 | Vitor Meireles | Makes documentation cleaner  | 1.4 |

