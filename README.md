# ocp-liquibase-demo
OpenShift Liquibase DB Migration Demo

1) Clone this repo
2) minishift start
3) oc new-project liquibase
4) Create a PostgreSQL service in the OpenShift GUI
5) oc create configmap sql-configmap --from-file=changelog.sql
6) oc create -f job.yaml
