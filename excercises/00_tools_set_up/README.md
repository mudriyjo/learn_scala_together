## Preparing environment

Before we start learn Scala 3 language we should prepare our local environment to comfortable work. We should install local Java virtual machine, IDE for write and run code, Git to pull project localy

### Set up Java SE

Why we should install Java SE when we want to learn Scala 3?

- Scala Runs on the Java Virtual Machine (JVM), so to execute Scala code, you'll need a JVM installed. Also we need Java Development Kit (JDK), because Scala using it under the hood

#### Installation:

1. Go to Java offical site [link](https://www.oracle.com/id/java/technologies/downloads/). You will see next screen
   [![Java official](/images/java.png)](https://www.oracle.com/id/java/technologies/downloads/)

2. Choose Download, and JDK 17

3. After that you should choose your operation system and process architecture. MacOs, Linux or Windows. After that folow installation for your system
   [![Java official](/images/java_2.png)](https://www.oracle.com/id/java/technologies/downloads/)

4. Check that your installation is correct. Open terminal and type next command

```
java --version
```

You should see somethin like this

```
java 17.0.9 2023-10-17 LTS
Java(TM) SE Runtime Environment (build 17.0.9+11-LTS-201)
Java HotSpot(TM) 64-Bit Server VM (build 17.0.9+11-LTS-201, mixed mode, sharing)
```

If you don't have message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Scala 3

We should install Scala version 3.3.1

#### Installation:

1. Go to Scala offical site [link](https://www.scala-lang.org/)

2. Choose Scala 3.3.1
   [![Scala official](/images/scala.png)](https://www.scala-lang.org/)

3. After that follow instruction. [link](https://www.scala-lang.org/download/3.3.1.html)

4. Check that your installation is correct. Open terminal and type next command

```
scala --version
```

You should see somethin like this. Check that your version is 3.3.1 this is important

```
Scala code runner version 3.3.1 -- Copyright 2002-2023, LAMP/EPFL
```

If you don't have message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up IDE (Intelij Idea)

IDE (integrated Development evnironment) our main application where we will working with code and test. We will use Intelij Idea community edition at this moment it has best Scala 3 support

#### Installation:

1. Go to Intelij Idea offical site [link](https://www.jetbrains.com/idea/download/?section=mac)

2. After that you should choose your operation system and process architecture. MacOs, Linux or Windows. After that folow installation for your system.

   [![Idea official](/images/idea.png)](https://www.jetbrains.com/idea/download/?section=mac)

3. Check that your installation is correct. Open Intelij Idea, you should see something like this.

   ![Intelij Idea](/images/idea_2.png)

If you don't have message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Git

We should localy install Git. Git is Git is a distributed version control system (VCS) used primarily for tracking changes in source code during software development.

#### Installation:

1. Go to Git offical site [link](https://git-scm.com/)

2. After that you should choose your operation system and process architecture. MacOs, Linux or Windows. After that folow installation for your system.

   [![Git official](/images/git.png)](https://git-scm.com/)

3. Check that your installation is correct. Open terminal and type next command

```
git --version
```

You should see somethin like this

```
git version 2.39.3 (Apple Git-145)
```

If you don't have message with runtime and java version, look at [potential problem section](#potential-problem)

### Set up Github (Optional)

You can contribute into this project and ask any question in Github. GitHub is a web-based platform that provides version control using Git

#### Sign up:

1. Go to Gitgub offical site [link](https://github.com/)

2. After that you should see welcome screen like that.

   [![Github](/images/github.png)](https://github.com/)

3. Folow the intrusction to finish registration

If you don't have message with runtime and java version, look at [potential problem section](#potential-problem)

#### Set up Ssh key:

1. Open Github ssh key page [link](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

2. Choose your operation system (MacOs, Windows or Linux).

[![ssh key](/images/ssh_key.png)](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)

3. Following the instruction

### Test setup

1. Prepare new folder for a project. For example on Mac you can create project folder in your home direcectory. Full path would be: `/Users/Alex/project`

2. Open you terminal/console and past next commands:

```
cd project
git clone git@github.com:mudriyjo/learn_scala_together.git
```

3. Open project in your IDE. Click open and choose 00_tools_set_up folder. First time project initialization may take time. [open project](/images/open_project.png)

4. Go to `src/main/scala/Main.scala` and click to green arrow and choose `run 'hello'` [open project](/images/test_run.png)

You shoud see next output

```
Hello world!
I was compiled by Scala 3. :)
```

**Congratulations, we finished set up project and all tools!**

### Potential problem

### Usefull links

More about JVM, JDK: [link](https://medium.com/jay-tillu/what-is-jdk-jvm-and-jre-the-exact-difference-between-them-ce39d591a925)

And what is the difference between JDK and JVM [link](https://www.digitalocean.com/community/tutorials/difference-jdk-vs-jre-vs-jvm)
