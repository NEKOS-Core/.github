## NEKOS
<img src="https://raw.githubusercontent.com/NEKOS-Core/.github/main/img/NEKOS.png" align="right" alt="Logo" title="Logo" width="300" height="300">
NEKOS is a kit of APIs and tools to gather various chat services' bot APIs under one API. NEKOS aims to make it easy to create chat bots which can interoperate across various chat services.
This project is currently a work in progress! Check the [Roadmap](https://github.com/NEKOS-Core/Roadmap) for features to be implemented.

NEKOS is coded mainly in Kotlin and consists of many parts. The current main focus is the Kotlin API, this is the backbone of abstracting the chat services. 
The NEKOS runner uses the API to load everything it needs. In the future, this will also expose a REST endpoint, simple web interface and console commandline. 

You can code plugins for NEKOS in Kotlin or Java, these can be packaged as JAR files and will be loaded by the runner. This is the most direct way to code for NEKOS, without having to use the REST API.
