# Order Request Process in BPMN 2.0
## Using BPM BonitaSoft
Prototype: The Order Request Process mapped in BPMN and built in Java(Groovy) on SQL using a simple Web interface.
[Link](https://www.bonitasoft.com/)

## The manual process
![BPMN_Before](https://github.com/davesdere/bonita_orderRequest/blob/master/BPMN_beforeOpt.png)

## The Optimized Project
### The End of the 3rd sprint
The client was already using a pretty awesome GUI for his clients but the lack of a data management platform was to be fixed.
The external service provider used the snipcart platform and the beautiful interface, the Glove Creator[Link](https://www.invictusgloves.com/gloves-creator), was only returning a simple data object per transaction. The output were fed to Bonita and a client database and user management platform was in place. Bonita manages the clients and the main integrity(with a bit of help) of the database while enabling us to send actionable automated emails.
![BPMN_Final](https://github.com/davesdere/bonita_orderRequest/blob/master/BPMN_final.png)
