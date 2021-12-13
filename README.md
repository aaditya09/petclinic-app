# petclinic-app 

* The clusters/ contains the GitOps config. It will command KubeVela to watch the specified repo and apply latest changes.

* The apps/ contains the Application yaml for deploying the user-facing app.

* The infrastructure/ contains infrastructure tools, i.e. MySQL database.

STEPS: 

1). Add config repo and define app.yaml and infra.yaml (which checks for any content change in the yamls and apply changes)
2). Define app.yaml 
3). Define infra.yaml 
4). Apply cluster/infra.yaml
5). 
