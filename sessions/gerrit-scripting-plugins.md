# How to extend Gerrit using Scripting Plugins

Gerrit Code Review has a robust set of API that can be used
to extend its functionalities and provide a more integrated
development workflow for the Teams.

You do neither need to be a Gerrit contributor nor to have
a fully working build environment to provide some basic
extensions: just use one of the scripting languages you know
or, if you don't like any of them, write your own!

In this talk, you will learn what Gerrit provides as
high-level API and how to use them to leverage some basic
functionality, such as commit validations or event
processing.

The scripting languages we will use are:
- Python (Jython inside the JVM)
- Groovy
- Scala

*Luca Milanesio / GerritForge*

Gerrit Contributor for over five years, my first commit
was cf5cd23d (the PluginLoader), maintainer of
GerritHub.io, the Open Service for Gerrit Code Review
on top of GitHub repositories.
