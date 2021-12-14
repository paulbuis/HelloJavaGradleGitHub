This project is intended as a template for sharing Java projects
with students in Ball State University's CS 121 course.

From the student's side, all they need to do in
JetBrains IntelliJ IDEA Community Edition
is use the menu sequence

```
File -> New -> Project from Version Control ...
```
When the dialog `Get from Version Control` pops up
and enter the URL for this repository:
`https://github.com/paulbuis/HelloJavaGradleGitHub.git`

Then, to run the project they to use the `Project` panel
and navigate to the `Hello.java` file that contains
`public static void main` and click on the big green arrow in
the left margin next to the source code. This will trigger
Gradle to "build" then "run" the program producing
output that looks like:

```
9:28:20 AM: Executing ':Hello.main()'...

> Task :compileJava
> Task :processResources NO-SOURCE
> Task :classes

> Task :Hello.main()
Hello Java
Hello Gradle
Hello GitHub
```