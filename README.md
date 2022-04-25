Defender CLI

Attribute	Description

[-h]	Prints the help information for the command.
-n NAME	The name of the rule being created.

[-ts TIMES]	The time span for which the rule is active. This should be specified as: xx:yy-xx:yy
You can define more than one time period by using a comma between them. For example: xx:yy-xx:yy, xx:yy-xx:yy.

[-dir DIRECTION]	The direction in which the rule is applied. This should be specified as:
both | src | dst

[-dev DEVICES]	The IP address and the address type of the devices to be excluded by the rule, specified as:
ip-x.x.x.x
mac-xx:xx:xx:xx:xx:xx
subnet: x.x.x.x/x

[-a ALERTS]	The name of the alert that the rule will exclude:
0x00000
0x000001
