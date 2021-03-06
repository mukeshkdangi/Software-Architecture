# Software-Architecture
# Soft Arch Visulazation and arch comparison  of log4j 2.2 and 2.7 system

Aspects that are possible for you to cover include, but are not limited to: 
• A summary of the most noticeable differences between the two versions of log4j 2.2 and 2.7 according to the recovered architectural views. 
• Why does this recovery method(out of ARCADE RELAX,ARC and ACDC ) show these changes and not others? 
• Do you think the differences accurately reflect the changes in the system that have taken place between the two versions? 
• Based on the results of the recovery, what conclusions would you draw about the future of the system?

# Assignment 1, 2, 3 and final project report 

Aim
The software aims to provide a visualization that is meaningful for the architect, developer and the user. Neither of the three recovery methods provide a clear visualization of the system’s abstract/overall architecture. We propose building a visualization tool that will provide hierarchy and levels to the system’s architecture. Along with this, the visualization will highlight areas of vulnerability in the software which will provide the architect with a better understanding of the system’s core components.

Visualization Details:
The visualization will provide three layers to the system:

Level 1
An abstract overview of the system architecture in terms of clusters and components categorized. This level will primarily be helpful to the users and the stakeholders in explaining the software system.

Level 2
Files belonging to each cluster/component and their dependencies in a directory structure (both outgoing and incoming). This level will assist the architect in identifying architectural erosion and drift that has been introduced in the system through implementation.

Level 3
Details of each individual file (such as file size, inheritance, lines of code, dependencies) along with the class diagram of the file. This layer will help the developer in particular as it describes each individual file.

Along with this we propose to implement the following a visualization for the n most coupled nodes. This would be in the form of a word cloud. Each name would be associated with a list of key features of the file such as lines of code, dependencies and source files which would help identify why the file has been flagged as vulnerable.

As inputs, we propose to use the output provided by the RELAX recovery method as well as third party libraries to elicit class diagrams of files. The software itself will be built using D3.js.




