Prerequisites

    Kubernetes 1.19+
    Helm 2.12+ or Helm 3.0-beta3+
    PV provisioner support in the underlying infrastructure
    ReadWriteMany volumes for deployment scaling
   
This deployment configured with Jenkinsfile as a pipeline , this build reuired the inputs as mentioned below:
   
SERVICE_PRINCIPAL="xxxx-xxx-xxx-xxx"
SERVICE_PRINCIPAL_SECRET="xxxx-xxx-xxx-xxx"
TENTANT_ID="xxxx-xxx-xxx-xxx"
SUBSCRIPTION="xxxx-xxx-xxx-xxx"


Note: In this present deployment I haven't use the ingress controller, to enable the ingress controller change the value in values.yaml file and update the actual to route the traffic.
