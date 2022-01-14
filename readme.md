# java gradle



## 新建工程



```
mkdir javaGradle
cd javaGradle/
gradle init
# 通通通一通选择
Select type of project to generate:
  1: basic
  2: application
  3: library
  4: Gradle plugin
Enter selection (default: basic) [1..4] 3

Select implementation language:
  1: C++
  2: Groovy
  3: Java
  4: Kotlin
  5: Scala
  6: Swift
Enter selection (default: Java) [1..6] 3

Select build script DSL:
  1: Groovy
  2: Kotlin
Enter selection (default: Groovy) [1..2] 1

Select test framework:
  1: JUnit 4
  2: TestNG
  3: Spock
  4: JUnit Jupiter
Enter selection (default: JUnit 4) [1..4] 1

Project name (default: javaGradle): javaProxys
Source package (default: javaProxys):
```



## 工程结构



```
[~/Desktop/javaGradle$]tree
.
├── gradle
│   └── wrapper
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── gradlew
├── gradlew.bat
├── lib
│   ├── build.gradle
│   └── src
│       ├── main
│       │   ├── java
│       │   │   └── javaProxys
│       │   │       └── Library.java
│       │   └── resources
│       └── test
│           ├── java
│           │   └── javaProxys
│           │       └── LibraryTest.java
│           └── resources
├── readme.md
└── settings.gradle

12 directories, 9 files
```

