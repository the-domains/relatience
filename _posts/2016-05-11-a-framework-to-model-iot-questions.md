---
inFeed: true
hasPage: true
inNav: false
inLanguage: null
keywords: []
description: 'A key communal aspect of questions pertaining to IoT is that they are often about coordination of actions with an ultimate relevance for (groups of) humans. A natural place to look at models that deal with relational questions that involve humans is social network analyses (SNA). '
datePublished: '2016-05-11T10:48:22.353Z'
dateModified: '2016-05-11T10:48:01.647Z'
title: ''
author: []
authors: []
publisher:
  name: null
  domain: null
  url: null
  favicon: null
starred: false
sourcePath: _posts/2016-05-11-a-framework-to-model-iot-questions.md
url: a-framework-to-model-iot-questions/index.html
_type: Article

---
In this brief exposure a generic way to frame questions relate to internet-of-things issues is presented. It is based on the pivotal work by Kathleen Carley and David Krackhardt ([1998][0]; 1999) from Carnegie Mellon University (CMU).

A key communal aspect of questions pertaining to IoT is that they are often about coordination of actions with an ultimate relevance for (groups of) humans. A natural place to look at models that deal with relational questions that involve humans is social network analyses (SNA). 

## Background

Social network analyses, which has roots in mathematical graph theory, sociology, social psychology, statistics, ecology among others, focuses on the analyses of data with a dyadic nature. Dyadic data is characterized by the fact that observations are based on two objects. Usually in SNA these objects are individuals or groups of individuals. Data is organized, in terms of matrices, where row and column indices identify objects. In case, row and column indices refer to the same set of objects, hence the matrix is square, the matrix is called a socio-matrix. The socio-matrix is defined on a specific relation between the objects, and can be undirected (e.g. similarity) or directed (e.g., information exchange). Observations are usually referred to as ties between objects, while the objects are referred to as nodes. 

Another form of representation is in graphs, which offers a more holistic visual assessment of social network data-sets.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/a5d11a24-bb0a-488f-a566-c3d11f5f5467.png)

Above graph is a representation of the interactions (ties) between characters (nodes) in the screen play "_The Dark Knight_" by [Joseph Blue][1].

## PECANS Model

The PECANS model, initially developed by [Krackhardt and Carley (1998)\*][0], extends the socio-matrix concept by allowing differentiation in groups of nodes. More specifically, nodes are uniquely grouped in people, resources and tasks, as they identified these as the fundamental building blocks of organizations. These three groups of nodes subsequently allow to define six primitive matrices (3 square matrices defined on the nodes belonging to the same group, and 3 matrices defined on the nodes belonging to different groups). These relationships can have different contents, which brings great flexibility to the model.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/2e0ad82a-fe23-42a5-8922-2d2ad9bd7410.png)

The benefit of the PECANS model is that it allows analyses of direct and indirect dependencies between the building blocks of organizations. Taking transformations of the sub-matrices from the larger meta-matrix that include the nodes in all three groups present direct insights in formal and emergent dependencies. As such, it is a focused tool tailored for the study and analyses of organizational coordination.

The Center for Computational Analysis of Social and Organizational Systems (CASOS) at CMU has developed the [software package ORA][2] that allows analyses of PECANS like data.

## Applying PECANS to IoT data

IoT data can be seen as a specific form of PECANS data, where resources can transmit information. In the original PECANS model the resources matrices (people-resources, and, task-resources) were conceptualized mainly as ownership, and dependency matrices. As IoT facilitates communication between resources this further expands the scope of the PECANS model to include information flows, resources-people, resource-tasks, and resource-resource, respectively. In essence the PECANS-framework can be directly applied, although we need to consider that the nature of resources has changed with respect to its original conceptualization as innate entity. Resource as nodal object have gained an aspect that within a specific instantiation can send and receive information about a state. 

[\*Krackhardt, David and Kathleen Carley 1998 "A PCANS Model of Structure in Organizations." Proceedings of the 1998 International Symposium on Command and Control Research and Technology. June. Monterey, CA.][0]  

\*\*Carley, Kathleen M., and David Krackhardt 1999 "A Typology for C2 Measures." In Proceedings of the 1999 International Symposium on Command and Control Research and Technology, June, Newport, RI.

[0]: http://www.andrew.cmu.edu/user/krack/documents/pubs/1998/1998%20PCANS%20Model%20Structure%20in%20Organizations.pdf
[1]: https://www.mapr.com/blog/author/joseph-blue
[2]: http://www.casos.cs.cmu.edu/projects/ora/