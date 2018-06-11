# oracledb-on-k8s
#### This helm chart helps you deploy an Oracle Database 12c Enterprise Edition, Single instance on Oracle Container Engine.
The Oracle Database container is configured to use a Persistent Volume created via a Persistent Volume Claim using oci provider (OCI block volume).

To install this helm chart, clone or download the repository, then customize the values.yaml to setup the required variables.

**helm install --name [release name] oracledb**

Please before running the chart, create a namespace to host the db and a registry secret to hold the docker credentials needed to download the Oracle Database Docker image.

For further information on how to accomplish this please see the Kubernetes documentation.
