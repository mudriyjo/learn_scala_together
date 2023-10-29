## Preparing environment

Before we start learning Scala 3 language we should prepare our local environment to comfortable work. We should install a local Java virtual machine, IDE for writing and running code, and Git to pull projects locally

### Set up Java SE

Why we should install Java SE when we want to learn Scala 3?

- Scala Runs on the Java Virtual Machine (JVM), so to execute Scala code, you'll need a JVM installed. Also, we need a Java Development Kit (JDK) because Scala uses it under the hood

#### Installation:

1. Go to the Java official site [link](https://www.oracle.com/id/java/technologies/downloads/). You will see the next screen
   [![Java official](/images/java.png)](https://www.oracle.com/id/java/technologies/downloads/)

2. Choose Download, and JDK 17

3. After that you should choose your operation system and process architecture. MacOS, Linux, or Windows. After that follow the installation for your system
   [![Java official](/images/java_2.png)](https://www.oracle.com/id/java/technologies/downloads/)

4. Check that your installation is correct. Open the terminal and type the next command

```
java --version
```

You should see something like this

```
java 17.0.9 2023-10-17 LTS
Java(TM) SE Runtime Environment (build 17.0.9+11-LTS-201)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.9+11-LTS-201, mixed mode, sharing)
```

If you don't have a message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Scala 3

We should install Scala version 3.3.1

#### Installation:

1. Go to Scala’s official site [link](https://www.scala-lang.org/)

2. Choose Scala 3.3.1
   [![Scala official](/images/scala.png)](https://www.scala-lang.org/)

3. After that follow instructions. [link](https://www.scala-lang.org/download/3.3.1.html)

4. Check that your installation is correct. Open the terminal and type the next command

```
scala --version
```

You should see something like this. Check that your version is 3.3.1 this is important

```
Scala code runner version 3.3.1 -- Copyright 2002-2023, LAMP/EPFL
```

If you don't have a message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up IDE (Intelij Idea)

IDE (Integrated Development Environment) is our main application where we will work with code and test. We will use the IntelliJ Idea community edition at this moment it has the best Scala 3 support

#### Installation:

1. Go to Intelij Idea offical site [link](https://www.jetbrains.com/idea/download/?section=mac)

2. After that you should choose your operation system and process architecture. MacOS, Linux, or Windows. After that follow installation for your system.

   [![Idea official](/images/idea.png)](https://www.jetbrains.com/idea/download/?section=mac)

3. Check that your installation is correct. Open IntelliJ Idea, you should see something like this.

   ![Intelij Idea](/images/idea_2.png)

If you don't have a message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Git

We should locally install Git. Git is a distributed version control system (VCS) used primarily for tracking changes in source code during software development.

#### Installation:

1. Go to Git’s official site [link](https://git-scm.com/)

2. After that you should choose your operation system and process architecture. MacOS, Linux, or Windows. After that follow installation for your system.

   [![Git official](/images/git.png)](https://git-scm.com/)

3. Check that your installation is correct. Open the terminal and type the next command

```
git --version
```

You should see something like this

```
git version 2.39.3 (Apple Git-145)
```

If you don't have a message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Github (Optional)

You can contribute to this project and ask any questions in Github. GitHub is a web-based platform that provides version control using Git

#### Sign up:

1. Go to Gitgub’s official site [link](https://github.com/)

2. After that you should see a welcome screen like that.

   [![Github](/images/github.png)](https://github.com/)

3. Follow the instructions to finish the registration

If you don't have a message with runtime and java version, look at [potential problem section](#potential-problem)

#### Set up Ssh key:

1. Open the GitHub SSH key page [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

2. Choose your operating system (MacO, Windows, or Linux).

[![ssh key](/images/ssh_key.png)](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

3. Following the instruction

### Test setup

1. Prepare a new folder for a project. For example, on Mac, you can create a project folder in your home directory. The full path would be: `/Users/Alex/project`

2. Open your terminal/console and past next commands:

```
cd project
git clone git@github.com:mudriyjo/learn_scala_together.git
```

3. Open the project in your IDE. Click open and choose 00_tools_set_up folder. First-time project initialization may take time. [open project](/images/open_project.png)

4. Go to `src/main/scala/Main.scala` and click on the green arrow and choose `run 'hello'` [open project](/images/test_run.png)

You should see the next output

```
Hello world!
I was compiled by Scala 3. :)
```

**Congratulations, we finished setting up the project and all the tools!**

### Potential problem

### Useful links

More about JVM, JDK: [link](https://medium.com/jay-tillu/what-is-jdk-jvm-and-jre-the-exact-difference-between-them-ce39d591a925)

And what is the difference between JDK and JVM [link](https://www.digitalocean.com/community/tutorials/difference-jdk-vs-jre-vs-jvm)
