# Decomposing strategies

## What is the microservice architecture exactly?

The **architecture of a software application** is its high-level structure, which consists of constituent parts and the dependencies between those parts.
The architecture determines the application's software quality attributes.

#### A definition of software architecture

> The software architecture of a computing system is the set of structures needed to reason about the system,
> which comprise software elements, relations among them, and the properties of both.
> 
> *Documenting Software Architectures by Bass et al.*

Decomposition is important because:
- it facilitates the division of labor and knowledge. It enables multiple people with possibily specialized knowledge to work productively together on an application;
- it defines how the software elements interact.

#### The 4+1 View model of software architecture

The 4+1 model defines four different views of a software architecture:
- *Logical view*: the software elements that are created by developers (i.e. classes, packages);
- *Implementation view*: the output of the build system (i.e. packaged code, components, and so on);
- *Process view*: the components at runtime (i.e. processes);
- *Deployment*: how the processes are mapped to machines;
- *Scenarios* (+1): how the various architectural components within a particular view collaborate to handle a request.

#### Why architecture matters

- *Functional requirements*: what the application must do;
- *Quality of service*: attributes which define the runtime qualities including maintainability, testability, and deployability.

