# AV-POC

The goal of this project is to implement a Proof of Concept of the PAIR (Projects - Actors - Ideas - Resources) vision on top of a LDP compatible system.
The source of the data to display and browse through is the LDP-based Wordpress plugin currently under development.

The idea is to get a MVP (Minimal viable product) to be able to convince more and more people that both the technological stack and our vision can help them to better organize their projects.

## The technology
This POC is using the LDP-Framework library developed and maintained by Sylvain Lebon for communicating with LDP-based servers.

The code is mainly HTML and CSS. The templating parts are handled by Javascript using the HandlebarsJS framework.

To install and use it, you will first need to get the Wordpress plugin mentioned above.

## Current state

For now this interface is only displaying a list of People (simplified version of the Actors concept)

## Nexts steps

Two importants steps are to be taken.
- Being able to display both Actors, Projects, Ideas and Resources based on their own ontology located on the AV website
- Being able to browse data from two different LDP servers (big parts of this step will be covered in the Wordpress plugin project)
