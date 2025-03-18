# CD12352 - Infrastructure as Code Project Solution
# Emily Cutler-Ames
URL - http://udacit-loadb-26bpqnbys2im-2051418031.us-east-1.elb.amazonaws.com/

## Spin up instructions
Check your AWS account is set up in the command line by running the following commands
aws configure list
aws iam list-users 

Then to spin up both stacks run

./run.sh create

## Tear down instructions
If you want to delete both stacks then run

./run.sh delete

## Other considerations
Once created if you want to make changes to either stack you may do so and then update them using

./run.sh update