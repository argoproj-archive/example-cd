Repo for example-cd based on sock-shop

ASSUMPTIONS:

You have a kubectl installed and configured. You have argo2 installed and available

To run:

cd workflows
argo2 submit logging-workflow.yaml
argo2 submit sock-shop-workflow.yaml
argo2 submit monitoring-workflow.yaml

To cleanup:

argo2 submit monitoring-cleanup-workflow.yaml
argo2 submit sock-shop-cleanup-workflow.yaml
argo2 submit logging-cleanup-workflow.yaml

