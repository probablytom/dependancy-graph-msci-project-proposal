* [Suitable/Not Suitable] for IT/SD and CS+

Description:

Consider the scenario: you've developed a small project which quickly gained traction and turned out to be rather successful, and what was once a hastily hacked-together codebase requires major refactoring and careful architectural engineering! However, the code as it exists is brittle and breaks in lots of unexpected places when even small edits are made. If only a tool existed which could help to refactor the codebase and work out a better architecture...

One way to do this could be to build a graph of dependencies between functions. If we know which parts of our code rely on other parts to operate properly, we could construct a graph representing how different parts of our code interact! Then, we might analyse various properties of the graph to learn about our codebase, and how it could be refactored. A question is left to be answered: how do we build this dependancy graph, and what can we learn about our code by measuring the graph's properties?

This project attempts to help software engineers understand how different parts of their codebase depend on others, and potentially predict / visualise technical debt and coupling, by producing dependancy graphs of the functions in a codebase. The project will then attempt measurements of the graph which might identify properties of the codebase it represents, such as coupling, potential modularisation, and the potential impact of editing code through observing density and tracing paths.

The objectives for this project are:
- Implement a dependency graph generator for Python code
- Produce a library of graph measurements and assess whether they can be useful to a developer in understanding their codebase
- Evaluate the effectiveness of these graph measurements
