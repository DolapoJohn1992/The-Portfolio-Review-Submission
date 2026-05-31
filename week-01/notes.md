# Week 01 Notes – Incident Response and Forensic Recovery

## Objective

The purpose of this exercise was to perform incident response and forensic recovery within a compromised Linux environment. The scenario involved restricted forensic evidence, malicious interference, and the need to recover attacker intelligence from protected system files.

## Technical Activities

The investigation required identifying and accessing a hidden evidence repository located within the Linux file system. Administrative permissions were necessary to restore analyst access and repair damaged permissions. File access was re-established through the use of Linux permission and ownership commands.

The investigation relied on command-line forensic processing using grep, sed, and awk. These tools were used to process a large forensic log and isolate malicious activity indicators. Stream editing techniques enabled the extraction of attacker information while removing irrelevant entries and duplicate data.

## Tools and Environment

* Ubuntu Linux
* Bash shell
* grep
* sed
* awk
* chmod
* chown
* sudo

## Key Learning Outcomes

This exercise strengthened foundational incident response skills and demonstrated the importance of Linux permissions during forensic investigations. It also reinforced the value of command-line automation for processing large datasets efficiently and accurately.

## Reflection

This lab highlighted how attackers may attempt to conceal evidence through permission manipulation and log contamination. Recovering access required both technical troubleshooting and analytical thinking. The exercise increased confidence in using Linux administrative commands and demonstrated how forensic workflows depend on precise command-line operations.

## Reference

Shotts, W. E. (2019). *The Linux command line: A complete introduction* (2nd ed.). No Starch Press.

