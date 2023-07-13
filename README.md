# Design of an External Applications Execution Environment

## Objective:

We want you to design a system that allows the building and execution of third-party applications on our existing platform, with its own unique URL (myapp.apps.myplatform.io). Here, 'myapp' represents the third-party application and 'myplatform' represents our primary platform's URL.

## Requirements:

### System Scope:

The system should be language-agnostic, but for the purpose of this design, we are focusing on .NET and Python applications.

![systemdesign drawio](https://github.com/buhlergroup/dev-challenge-02/assets/1763806/0778f41e-c3c1-4719-9ab6-bc005a1fe9ba)

### UI Development:

Third-party applications can expose a UI which must be developed using Angular. This UI should be packaged alongside its backend logic.

### Application URLs:

Every application should have its own URL that follows this format - myapp.apps.myplatform.io.

### Authentication:

Authentication should be managed at the ingress point of this execution environment, not within the frontend of the application.

### API Access:

Applications should be able to access the existing platform API in one of two ways:

* As a technical user specifically assigned to the application
* As a logged-in platform user

## Instructions:

Your task is to design this External Applications Execution Environment. Discuss the architecture, the components needed, how they interact, and the pros and cons of your design. Also, detail any security considerations and explain how to maintain high availability and scalability.

## Considerations:

Please consider trade-offs in your design choices and be ready to discuss alternative solutions. We also expect a deep understanding of how the system would work, addressing aspects such as potential bottlenecks, points of failure, and performance metrics.

## Deliverables:

A system design diagram along with a comprehensive explanation of how the various components of your system interact, the technology choices you've made, and the reasoning behind those decisions.

## Note:

Keep in mind that while we're focusing on .NET and Python applications for now, the system should be designed with the flexibility to potentially support other programming languages in the future.
