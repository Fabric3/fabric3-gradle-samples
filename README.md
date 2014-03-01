Fabric3 Gradle Plugin Samples
=============================

This repository hosts example projects that use the Fabric3 core Gradle plugins. Further information on can be found at http://www.fabric3.org.


Building the Source
------------------------

Requirements are JDK 7.

To build the source, execute the Gradle script, e.g.: *./gradlew* (\*Nix) or *gradle* (Windows)


Projects
------------------------

- *services* - Contains a service exposed as a ZeroMQ endpoint. Can be deployed to a Fabric3 runtime or as a webapp. Demonstrates the Fabric3 contribution
plugin for bundling services in a deployable unit.


- *distribution* - Builds and configures a Fabric3 runtime with the *services* project. Demonstrates the Fabric3 assembly plugin for creating runtime
images.


- *webapp* - Bundles the *services* project in a web application. Demonstrates how to use the Fabric3 packaging plugin to deploy to a servlet container.
