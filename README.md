## Examples of generated manifests using kubectl-ai

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
|------|--------|-------------|---------|
| Application | `kubectl ai "create pod for basic app"` | Basic manifest for application deployment | [app.yalm](yaml/app.yaml)|
| Liveness probe | `kubectl ai "create application liveness probe"` | A Kubernetes manifest with a liveness probe which determines if an application within a Pod is running as expected | [app-livenessProbe.yalm](yaml/app-livenessProbe.yalm)|
| Readiness probe | `kubectl ai "create application readiness probe"` | A Kubernetes manifest with a readiness probe which determines when an application inside a Pod is ready to serve traffic | [app-readinessProbe.yalm](yaml/app-readinessProbe.yalm) |
| Volume mounts | `kubectl ai "add volume mounts"` | A Kubernetes manifest with volume mounts allows you to specify the volumes and their associated mount paths within containers running in a Pod. | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
| Cronjob | `kubectl ai "add cronjob"` | A Kubernetes manifest with a CronJob which defines a scheduled job to be executed at specific intervals or times within a Kubernetes cluster. | [app-cronjob.yaml](yaml/app-cronjob.yaml) |
| Job | `kubectl ai "add one-time job"` | A Kubernetes manifest with a job defines a one-time or batch task that runs to completion in a Kubernetes cluster. | [app-job.yaml](yaml/app-job.yaml) |
| Multicontainer app | `kubectl ai "create multicontainer pod"` | It is a configuration file that describes multiple containers and their specifications within a single Kubernetes resource, usually within a Pod. | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| Resources | `kubectl ai "set resources of pod"` | It defines the resource requests and limits for the workload. | [app-resources.yaml](yaml/app-resources.yaml) |
| Secret-env | `kubectl ai "define secret environment variables"` | This manifest allows you to inject sensitive information or configuration into your application containers without exposing them directly in your code or configuration files. | [app-secret-env.yaml](yaml/app-secret-env.yaml) |