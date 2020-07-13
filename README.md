# snapshot-manager

Test project to manage AWS EC2 instance snapshots

## About

Demo uses boto3 to manage AWS EC2 instance snapshots


## Configuring

snapshot manager uses the aws cli profile configuration file. 
E.g.

`aws configure --profile snapshot-manager`

## Running

`pipenv run "python snapshot-manager/snapshot-manager.py <command>
<--project=PROJECT>"`

*command* is list, start, or stop
*project* is optional to filter based on AWS Tag = "project"