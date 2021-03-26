# Barnacle (aka Heijunka)
A heijunka is a Kanban board with several projects shown at the same time. The goal is to provide an interface where you can analyse the state of Kanban for the whole organization, teams and individuals. It's main usage is to integrate changes to Kanban boards in other systems. That said, you can use it as a Kanban board on its own as well (and that's what I'm doing as well).

If you just want the software, you can get it either as an [application to install on a local machine](https://github.com/axelkr/solid-barnacle) or as a [single-page application to install on a server](https://github.com/axelkr/sterling-barnacle). Software architecture is documented in [SoftwareArchitecture.md](./SoftwareArchitecture.md).

This also serves as a playground application for me to apply product management techniques. You find more details at [ProductManagement.md](./ProductManagement.md).

## Features
- Define per project a set of stages
- Changes by a user are propagated to other users as well.

## Milestones
### 1.2 Contexts
- User can define contexts and filter the displayed cards based on them.

### 1.1 Cumulative flow diagram
- User sees a projects cumulative flow diagram (CFD) on the project page.

### 1.0 Eat my own dogfood
- Software can be installed on Debian and Windows as well as hosted on a web server as a single page application. 
- User can setup new projects
- User can add new Kanban cards in a project and moving it through the stages