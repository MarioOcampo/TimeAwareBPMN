# TimeAwareBPMN-js
This is a Google-findable repository of the original [TimeAwareBPMN](https://gitlab.com/univr.di/TimeAwareBPMN)
# 

**TimeAwareBPMN-js** is a tool for editing and verifying time-aware BPMN models, BPMN models having temporal constraints.

It is a web-application and consists of a graphical editor ([bpmn.io](https://bpmn.io/toolkit/bpmn-js/)) where it is possible to create or edit time-aware BPMN models
and to select and run a plug-in for *verifying* temporal constraints.

Plug-in architecture allows the execution of different programs for verifying different temporal properties.

As a proof-of-concept, the application contains the *CSTNU plug-in*, that allows verifying if the model is *dynamically controllable*,
i.e., it is possible to execute it whatever the duration of some activities, called *contingent* activities.
Each contingent-activity duration is limited to stay in a temporal range, but the exact duration is decided at run-time by the external "agent" executing it.
CSTNU plug-in verifies the dynamic controllability property using an external Java library.

This is a screenshot of the interface of the TimeAwareBPMN-js showing the graphical editor and the tool with buttons for the possible actions. 

![Screenshot of the interface](https://gitlab.com/univr.di/TimeAwareBPMN/-/raw/main/examples/screenshots/screenshotInterface_diagramExample.png)

#

See original repository [TimeAwareBPMN](https://gitlab.com/univr.di/TimeAwareBPMN).


## References
[TimeAwareBPMN-Js: an editor and temporal verification tool for time-aware BPMN processes](https://doi.org/10.1016/j.softx.2021.100939) <br>
Mario Ocampo-Pineda, Roberto Posenato, Francesca Zerbato <br>
SoftwareX, 17 (2022), p. 100939, 

[CSTNU Tool: A java library for checking temporal networks](https://doi.org/10.1016/j.softx.2021.100905) <br>
Roberto Posenato <br>
SoftwareX, 17 (2022), p. 100905
