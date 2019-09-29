# kubernetes-nginx

Deploy Nginx loadbalancer via pulumi infrastructure as code. This allows multi-cloud, AWS, Azure, Gcloud and metal Kubernetes cluster. Pulumi is an open-source cloud object model that is inherently language- and cloud-neutral.

In this case we will use Python, so to deploy you must create a venv and install the requirements -

```

virtualenv -p python3 venv
source venv/bin/activate
pip3 install -r requirements.txt
pulumi up
