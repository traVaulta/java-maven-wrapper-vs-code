## Java Maven Wrapper VS Code project template

Project template for running Java Maven Wrapper in VS Code

### Requirements

- installed JDK version 24
- installed Maven version 3.8.x

### Running wrapper (Windows machine)

```shell
.\\mvnw.cmd clean install
```
```shell
.\\mvnw.cmd compile exec:java -Dexec.mainClass="cvrk.matija.sample.Application"
```

### Open template in StackBlitz (just for show)

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/traVaulta/java-maven-wrapper-vs-code)

### Add archetype locally

```shell
mvn archetype:create-from-project
```

## Author

- [Matija Čvrk](https://hr.linkedin.com/in/matija-%C4%8Dvrk-1388b3101/)

## License

- [GNU AGPL Version 3](./LICENSE)
