# AV-POC

The goal of this project is to implement a Proof of Concept of the PAIR (Projects - Actors - Ideas - Resources) vision on top of a LDP compatible system.
The source of the data to display and browse through is the LDP-based Wordpress plugin currently under development.

The idea is to get a MVP (Minimal viable product) to be able to convince more and more people that both the technological stack and our vision can help them to better organize their projects.

## The technology
This POC is using the LDP-Framework library developed and maintained by Sylvain Lebon for communicating with LDP-based servers.

The code is mainly HTML and CSS. The templating parts are handled by Javascript using the HandlebarsJS framework.

To install and use it, you will first need to get the Wordpress plugin mentioned above.

## Architecture
Based on what is assumed above (aka you also installed the Wordpress Plugin), the current POC architecture looks as the following:

<p align="center">
  <img src="https://github.com/assemblee-virtuelle/AV-POC/blob/master/wiki/img/AV-POC.png" alt="Architecture schema" />
</p>

## Current state

For now this interface is only displaying a list of People (simplified version of the Actors concept)

## Nexts steps

Two importants steps are to be taken.
- Add the fluidgraph library to be able to view the data in a graph
- Add edit capabilities for data coming from a LDP compliant server (not a WP-LDP one).
