# Harness Kustomize
    Example: deploy web application using kustomize and harness

### Usage
+ Create Harness Account
+ Create a project
+ Create Environment

+ Start Minikube
    ```
    minikube start
    ```

+ Install Helm Delegate
![Install Helm Delegate](./images/harness-delegate.png)

+ Create Kubernetes Cluster
![Create Kubernetes Cluster](./images/harness-create-kubenetest-cluster.png)

+ Create Service and GitHub Connection
![Create Service](./images/harness-create-service.png)

+ Run Pipeline
![Run Pipeline](./images/harness-kustomize-pipeline.png)


### Result
+ Port Forwarding Service in Minikube
    ```
    minikube service the-service --url
    ```
+ Result
![Result](./images/result.png)