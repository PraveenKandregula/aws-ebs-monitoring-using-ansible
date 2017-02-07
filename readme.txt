Legends:
aws configure has been properly done on the server where this script is supposed to run. 
This playbook has been designed to run locally. 
This has been prepared to monitor EBS valumes under same AWS account.

How to run:
ansible-playbook aws-ebs-monitor.yml -e instance1="" -e instance2="vol-030ca55ee0359ef89" -e instance3="vol-01947905a4b639b0d" -e instance4="" -e instance5=""

Enhancements:
This script can be enhanced to monitor n no.of EBS volumes. Add these in playbook acordingly and pass them while running the playbook. Passing all variables is mandatory. Pass null("") as shown above if any instance to be skipped.
