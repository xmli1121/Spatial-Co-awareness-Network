# The workflow to generate spatial co-awareness networks in buildings

The repository contains exemplar codes and supportive files to generate **spatial co-awareness networks** (SCN) in buildings.

## About SCN

The SCN is a network in which nodes are objects inside building spaces and links indicate visibility relations between nodes. The nodes could be either *behavioural carriers* people stay, such as seats in office buildings, beds in hospitals or care facilities, or *attractors* that induce aggregation and interaction, such as coffee machines, tea points or televisions.

By structuralised description of visual relations between various behavioural carriers or attractors through a network perspective, the SCN illustrates the ways or opportunities persons inside buildings are aware of each other that are regulated by the placement of objects such as seats. When objects belonging to different categories of persons are specified, the SCN could also indicate characteristics of 'interfaces', e.g., spatial relations between inhabitants and visitors.

The idea of SCN is inspired by the classic *visibility graph model* in Space Syntax studies. However, the SCN complements space syntax method in the way that, space syntax models focus on 'spaces' inside buildings, while SCNs model objects embedded in spaces.

## About the codes and materials

1. The core part of the codes (the `.ipynb` file) in this repository uses functions of DepthmapX to generate isovists for objects. More details about how to the function works and how to retrieve the function using Python codes could be found in official repository of DepthmapX ([GitHub - varoudis/depthmapX: depthmapX is a multi-platform Spatial Network Analysis Software](https://github.com/varoudis/depthmapX)), and a basic workflow developed by pklampro ([pklampros/depthmapWorkflowPython: Sample workflows for working with the depthmaX CLI and python (jupyter) (github.com)](https://github.com/pklampros/depthmapWorkflowPython)).
  
2. This repository uses a layout plan of an elderly care facility as an exemplar case. The SCN of the facility is generated to model spatial relations between *public seats* and *nursing beds*.
