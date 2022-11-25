# Scala Devcontainer

A [VS Code](https://code.visualstudio.com) [devcontainer](https://containers.dev) 
to be used for [Scala](https://www.scala-lang.org) (Version 3) development. The
devcontainer includes all required tools and example code as well as tests to get
quickly started or try our Scala.

## Running the devcontainer

To run the devcontainer, check out the the git repository, open the folder in
VS Code and execute the task `>Dev Containers: Open Folder in Container...`.

You can also use GitHub Codespaces to run the devcontainer. On GitHub, open the
git repository, click on `Code`, then `Codespaces`, and select `Create codespace
on main`.

## Starting a Scala script

Scala can be used to write scripts. If you want to try out using Scala in scripts,
you can start with the file `scripts.scala`. To run the script, run the following
command inside of the devcontainer.

```
$ scala script.scala
```

## Compiling the Scala code

The devcontainer includes [sbt](https://www.scala-sbt.org) as build tooling. To
compile the provided Hello World example, run the following command inside of 
the devcontainer:

```
$ sbt compile
```

To execute the resulting program, use the following command:

```
$ sbt run
```

## Running tests

The devcontainer includes a basic sketch of [ScalaTest](https://www.scalatest.org)
for unit testing. To run the provided example tests, execute the following command
inside of the devcontainer:

```
$ sbt test
```