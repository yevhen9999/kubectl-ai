# kubectl-ai prompts collection for generating yaml manifests 

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|----------------------|--------------------------------------------------------------------|-----------------------------------|-------------------------------------|
| app.yaml | create manifest for pod named app. container using image gcr.io/k8s-k3s/demo:v1.0.0. expose port 8000, labels are app: demo and run: demo | This manifest defines a Kubernetes Pod resource|[app.yaml](yaml/app.yaml) |
| app-livenessProbe.yaml | add livenessProbe | with use of reprompt option add livenessProbe | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | add readinessProbe | with use of reprompt option add readinessProbe | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | add volumeMounts | with use of reprompt option add volumeMounts | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
| app-cronjob.yaml | create cronjob to print Hello World | manifest for a simple cron job | [app-cronjob.yaml](yaml/app-cronjob.yaml) |
| app-job.yaml | create Job to use google/cloud-sdk container to sync data from a GCP bucket to a GCE persistent disk mounted at /data/input | manifest to sync data | [app-job.yaml](yaml/app-job.yaml) |
| app-multicontainer.yaml | create Pod with nginx and debian containers, shared volume, debian has index.html with date record every 1 sec | manifest for pod with two containers | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
|  |  |  |  |