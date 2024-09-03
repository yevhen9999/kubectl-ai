# kubectl-ai prompts collection for generating yaml manifests 

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|----------------------|--------------------------------------------------------------------|-----------------------------------|-------------------------------------|
| app.yaml | create manifest for pod named app. container using image gcr.io/k8s-k3s/demo:v1.0.0. expose port 8000, labels are app: demo and run: demo | This manifest defines a Kubernetes Pod resource|[app.yaml](yaml/app.yaml) |
| app-livenessProbe.yaml | with use of reprompt option add livenessProbe | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml) |
| app-readinessProbe.yaml | add readinessProbe | with use of reprompt option add readinessProbe | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml | add volumeMounts | with use of reprompt option add volumeMounts | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |