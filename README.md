# kubectl-ai prompts collection for yaml manifests generating

| NAME                 | PROMPT                             | DESCRIPTION                                       | EXAMPLE                                             |
|----------------------|------------------------------------|---------------------------------------------------|-----------------------------------------------------|
| app.yaml | create manifest for pod named app. container using image gcr.io/k8s-k3s/demo:v1.0.0. expose port 8000, labels are app: demo and run: demo | This manifest defines a Kubernetes Pod resource | [app.yaml](yaml/app.yaml) |
| app-livenessProbe.yaml | prompt | desc |[app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)|