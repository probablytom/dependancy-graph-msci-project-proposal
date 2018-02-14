# One of Tim's examples for comparison

* Suitable for both IT/SD and CS+.
*Project may require participation from people other than the student and the supervisor as part of the evaluation.

Description:

How many of us have sent an email without the claimed attachment? The Thunderbird mail client has a feature that addresses exactly this problem. If we compose an email containing the word 'attachment' and we try and send it without one, we get a prompt asking us if there is anything we have forgotten. 

Normally, user interface designers attempt to make their systems as intuitive and convenient as possible. However, sometimes it might be useful if an application was a little bit obstructive, in order to give us a chance to reconsider an action before we commit to it, but not prevent us if we are absolutely determined. 

Obstructive user interfaces [http://eprints.gla.ac.uk/82453/] realises this idea by providing a framework for developers to incorporate widgets in a user interface that can be more or less obstructive to a task, depending on the task context. 

For example, if a user attempts to transfer a file to a shared folder on an unknown cloud storage provider, the user might be asked to confirm the action several times, rather than once. Conversely if they try to send the file to another device that they own they are not asked to authenticate at all. 

The objectives for this project are: 
- Implement a library of obstructive interface widgets for the Android platform. The library should be designed so that the widgets can be used as part of the user interface of any Android application. The widgets should be configurable so that their obstructiveness can be varied according to the context of a task. 
- Develop or re-develop a demonstrator application for the library. 
- Evaluate the effectiveness of obstructive interfaces in encouraging secure behaviour in a user study.

---

# Our 1st draft proposal

* [Suitable/Not Suitable] for IT/SD and CS+

Description:

How often do we edit a function in a large software project, only to find that we suddenly have a plethora of bugs in seemingly unrelated parts of our codebase? Often it's not possible to loosely couple pieces of software, or technical debt builds in an older project, leading to complicated dependancies across various functions.

Usually we try either to engineer loosely coupled systems, or spend time wading through stack traces to understand how different parts of our code relate when we break an implementaiton. This would be easier, however, if we could predict the potential impact of changing a function, by looking at the parts of our code which depend on the function we're about to change. 

This project attempts to help software engineers understand how different parts of their codebase depend on others, and potentially predict / visualise technical debt and coupling, by producing dependancy graphs of the functions in a codebase. The project will then attempt measurements of the graph which might identify properties of the codebase it represents, such as coupling, potential modularisation, and the potential impact of editing code through observing density and tracing paths.

The objectives for this project are:
- Implement a dependency graph generator for Python code
- Produce a library of graph measurements and assess whether they can be useful to a developer in understanding their codebase
- Evaluate the effectiveness of these graph measurements
