# Fullstack part 11 excercise 1

My answer to exercise 1 assumes the application is written in Java. There are several linting tool options for Java applications. For example:

- Checkstyle has plugins for all major IDEs, and predefined configs for most coding standards.
- Spotbugs is a program which uses static analysis to look for bugs in Java code.
- Java IDEs like IntelliJ or Eclipse have built-in tools that comply with good code standards

Some popular Java test frameworks include:

- JUnit allows you to write tests that are run automatically at build time. JUnit was also used in University of Helsinki's Introduction to programming course.
- Selenium is a powerful tool that allows you to perform GUI automation and it supports multiple languages using the Driver model. Once you know Selenium, you are not just bound to test Java application but also you can test web applications written in any programming language
- REST Assured is well suited for REST API integration tests.

Building Java apps is done with a Java compiler that compiles Java code into byte code. Several compilers exist, Javac, EDG Compiler, and GCJ to name a few.

Some CI tools in addition to GitHub Actions and Jenkins include Travis CI, Circle CI, GitLab, Atlassian Bamboo and TeamCity

Based on the introduction text to part 11, I would say that the CI/CD pipeline of a small-ish application developed by a team of six developers would be better hosted in a cloud-based solution, assuming that the project does not have any special requirements that the cloud-based solution could not provide. These requirements could be for example a need for some specific hardware resources to run the tests. A cloud-based solution would be cheaper and easier to configure.
