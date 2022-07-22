This project is to demo the issue where VSCode does not recognize gradle API's when developing gradle plugins.

The project was creating using gradle init:

```
gradle-classpath-vscode-issue % gradle init

Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 4

Select implementation language:
  1: Groovy
  2: Java
  3: Kotlin
Enter selection (default: Java) [1..3] 2

Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Generate build using new APIs and behavior (some features may change in the next minor release)? (default: no) [yes, no]yesProject name (default: gradle-classpath-vscode-issue):
Source package (default: gradle.classpath.vscode.issue):

> Task :init
Get more help with your project: https://docs.gradle.org/7.4.2/userguide/custom_plugins.html

BUILD SUCCESSFUL in 25s
2 actionable tasks: 2 executed
```
