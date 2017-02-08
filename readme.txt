Legends:
aws configure has been properly done on the server where this script is supposed to run. 
This playbook has been designed to run locally. 
This has been prepared to monitor EBS valumes under same AWS account and region.

How to run:
ansible-playbook aws-ebs-monitor.yml --extra-vars='{"instances":[vol-01baf063395601029 vol-030ca55ee0359ef89 vol-01947905a4b639b0d]}'
Enhancements:
This script can be enhanced to monitor n no.of EBS volumes. Pass them as variables in extra vars section seperated by a blank space. Samle output can be seen from sample-output.
