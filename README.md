<!-- $! -->

# Chisel Project Template

You've done the [Chisel Bootcamp](https://github.com/freechipsproject/chisel-bootcamp), and now you
are ready to start your own Chisel project.  The following procedure should get you started
with a clean running [Chisel3](https://www.chisel-lang.org/) project.

## Getting Started

You can create a project from this template using the [command line](#command-line) or using the [Github UI](#github-ui) to create a repository from this one.

Please see the <TODO website link\> for instructions on installing dependencies.

### Command Line

This repository is a [Giter8](https://www.foundweekends.org/giter8) template so can be used via the various tools' APIs.

**Using [Scala CLI](https://scala-cli.virtuslab.org)**

```sh
scala-cli --power new jackkoenig/chisel-template.g8
```

**Using [Mill](http://mill-build.com/mill/Intro_to_Mill.html)**

```sh
mill init jackkoenig/chisel-template.g8
```

**Using [SBT](https://www.scala-sbt.org)**

```sh
sbt new jackkoenig/chisel-template.g8
```

**Using [Giter8](https://www.foundweekends.org/giter8)**

```sh
g8 jackkoenig/chisel-template.g8
```

### Github UI

#### Create a repository from the template

You can create your own repository from this template by clicking the green `Use this template` in the top right.
Please leave `Include all branches` **unchecked**; checking it will pollute the history of your new repository.
For more information, see ["Creating a repository from a template"](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template).

#### Wait for the template cleanup workflow to complete

After using the template to create your own blank project, please wait a minute or two for the `Template cleanup` workflow to run which will removes some template-specific stuff from the repository (like the LICENSE).
Refresh the repository page in your browser until you see a 2nd commit by `actions-user` titled `Template cleanup`.

## Problems? Questions?

Check out the [Chisel website](https://www.chisel-lang.org/docs) for documentation and the [users community](https://www.chisel-lang.org/community.html) page for links to get in contact!

------------------------------------------

**The below is used to generate the README for projects using this template**

<!-- !$ -->

# $name$

This project was created from https://github.com/jackkoenig/chisel-template.g8

## Basic Use

Compile everything and run the included test:

**Using Mill**

```sh
mill $name;format="camel"$.test
```

**Using SBT**

```sh
sbt test
```
