# kubectl-ai prompts collection for generating yaml manifests 

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|----------------------|--------------------------------------------------------------------|-----------------------------------|-------------------------------------|
|app.yaml|create manifest for pod named app. container using image gcr.io/k8s-k3s/demo:v1.0.0. expose port 8000, labels are app: demo and run: demo|This manifest defines a Kubernetes Pod resource|[app.yaml](yaml/app.yaml)|
|app-livenessProbe.yaml|pod app-livenessprob in demo namespace with image gcr.io/k8s-k3s/demo:v1.0.0, port 8080, and HTTP liveness probe on / at port 8000|defines a Kubernetes Pod resource with an liveness probe|[app-livenessProbe.yaml](yaml/app-livenessProbe.yaml)|
| app-readinessProbe.yaml | Pod with livenessprob and readinessprobe | define example of manifest for Pod with livenessprob and readinessprobe | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |