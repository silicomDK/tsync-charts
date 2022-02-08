# tsync-charts

* The daemonsets need the correct nodeSelector labels (example: pci.sts.silicom.com/card: "true").
  * Which nodes have the cards.
* The daemonsets need the correct nodeSelector labels (example: sts.silicom.com/mode: "gm").
  * What mode of the tsyncd should be started/used.
* The daemonsets pods need privileged rights.

These default values are in values.yaml
